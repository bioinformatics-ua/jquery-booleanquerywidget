# Boolean Query Widget

===

Bootstrap & Jquery based boolean query widget, with drag-and-drop and serialization / deserialization.

# Plugin options available

| Param  | Description |
| ------ | ----------- |
| inplace  | Controls the plugin display(in place continuing the page flow, or detached as a popup) |
| view_only | Controls if the widget is read-only or editable (useful to show already serialized data) |
| expand_text | Text to show when the plugin is detached and the popup open in edit mode |
| expand_text_read | Text to show when the plugin is detached and the popup open in read mode |
| collapse_text | Text to show when the plugin is detached and the popup closed in edit mode |
| collapse_text_read | Text to show when the plugin is detached and the popup closed in read mode |
| query_text | Text to show when query is empty |
| form_anchor | Reference to the form that relates to this widget, optional, but if defined allows form submission through the widget |
| auto_add | Controls if there should be an intermediary container for concepts, or they should be added imediately to the query |
| default_relation | The kind of relation to be defined on drag-and-drop concepts by default |
| hide_concepts | Show flat list of concepts above query |
| view_serialized_string | Allows passing an previously serialized query to the widget |
| help | Html content to show on the help menu of the widget |
| link_back | Allows providing a link back inside the widget |

# Widget methods

| Method Call  | Description |
| ------------- | ------------- |
| isEmpty()  | Returns the widget fill status  |
| push(id, question, answer)  | Adds a concept to the widget  |
| pushWithDelegate(id, question, answer, delegate)  | Adds a concept to the widget with a delegate function to handle when the concept is removed(p.e. we could also clean the form field) |
| splice(id, question, answer) | Removes a concept from the widget |
| reset() | Resets the widget removing all concepts |
| serialize() | Returns a serialized query to be used later on the widget |


# Disclaimer

This a WIP, so not final in any way. There's still no real documentation available.

We make no warranty and cannot be held responsible for any information retrieved and displayed in this catalogue nor by any damage this software my cause.
