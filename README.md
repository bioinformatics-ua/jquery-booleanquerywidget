# Boolean Query Widget

===

# About

Bootstrap & Jquery based boolean query widget, with drag-and-drop and serialization / deserialization.

# Plugin options available

>{
>    // Controls the plugin display(in place continuing the page flow, or detached as a popup)
>    inplace: false
>    // Controls if the widget is read-only or editable (useful to show already serialized data)
>    view_only: false,
>    // Text to show when the plugin is detached and the popup open in edit mode
>    expand_text: 'To define the relations between the terms click here',
>    // Text to show when the plugin is detached and the popup open in read mode
>    expand_text_read: 'To see the relations defined in this search click here',
>    // Text to show when the plugin is detached and the popup closed in edit mode
>    collapse_text: 'Click here to close this panel',
>    // Text to show when the plugin is detached and the popup closed in read mode
>    collapse_text_read: 'Query in effect (Click here to close this panel)',
>    // Text to show when query is empty
>    query_text: 'Start filling the questionnary to start building a query...',
>    // Reference to the form that relates to this widget, optional, but if defined allows form submission through the widget
>    form_anchor: null,
>    // Controls if there should be an intermediary container for concepts, or they should be added imediately to the query
>    auto_add: true,
>    // The kind of relation to be defined on drag-and-drop concepts by default
>    default_relation: BOOL['AND'],
>    // Show flat list of concepts above query
>    hide_concepts: true,
>    // Allows passing an already serialized query to the widget
>    view_serialized_string: null,
>    // Html content to show on the help menu of the widget
>    help: null,
>    // Allows providing a link back inside the widget
>    link_back: null,
>}

# Methods available from the widget returned object

| Method Call  | Description |
| ------------- | ------------- |
| isEmpty()  | Returns the widget fill status  |
| push(id, question, answer)  | Adds a concept to the widget  |
| push(id, question, answer)  | Adds a concept to the widget  |
| pushWithDelegate(id, question, answer, delegate)  | Adds a concept to the widget with a delegate function to handle when the concept is removed(p.e. we could also clean the form field) |
| splice(id, question, answer) | Removes a concept from the widget |
| reset() | Resets the widget removing all concepts |


# Disclaimer

This a WIP, so not final in any way. There's still no real documentation available.

We make no warranty and cannot be held responsible for any information retrieved and displayed in this catalogue nor by any damage this software my cause.
