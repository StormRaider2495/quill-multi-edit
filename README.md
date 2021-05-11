# Quill-Edit-Multiple

A sample application showing how you can have multiple editable areas of your app using the Quill editor with only one toolbar, moving the editor around.

## How it works

I'm creating one instance of Quill, using a custom toolbar positioned at the top. The editor element is placed in a temporary, hidden, container.
When the user double clicks any of the three text containers (Editables), the editor element will be transplanted form the temporary container to a new location inside the Editable.
If a user hits the escape key, the Editable will be deactivated, moving the editor element back to the temporary container.

## Emoji Support

Added support of Emoji to the quil editor by integrating <https://www.npmjs.com/package/quill-emoji>

## Hosting

The current code is hosted at <https://stormraider2495.github.io/quill-multi-edit/build/index.html>
