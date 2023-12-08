# Project Object

A project object looks like this:

```
{
    "id": /* The project's ID */
    "author": {
        "id": /* The author's user ID */
        "username": /* The author's username */
    }
    "title": /* The title of the project */
    "instructions": /* The project's complete instructions (its Instructions field) */
    "description": /* The project's complete 'description' (its Notes and Credits field) */
    "is_published": /* Whether or not the project is shared */
    "visibility": /* "notvisible" if the project is in the My Stuff trash section; "visible" otherwise */
    "image": /* The URL of the project's thumbnail image */
    "history": {
        "created": /* The timestamp when the project was first created (when the 'create' button was pressed) */
        "shared": /* The timestamp when the project was shared */
        "modified": /* The timestamp of the last time the project was modified */
    }
    "stats": {
        "loves": /* The number of love-its the project has */
        "favorites": /* The number of favorites the project has */
        "views": /* The number of views the project has */
        "remixes": /* The number of remixes the project has */
    }
    "remix": {
        "root": /* The 'root' project in a remix tree; the top level, which is not a remix (null if this project is not a remix) */
        "parent": /* The 'parent' project in a remix tree, which *may* be a remix (unset if this project is not a remix) */
    }
}
```
