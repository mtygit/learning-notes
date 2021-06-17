## Forms and JS Events

### Forms

Froms are used when you want to collect information from visitors. The input information is sent in name/value pairs.

- form structure: \<form>
- text input:\<input> type="text"
- password input: type="password"
- image button: type="image"
- labelling form controls: \<label>
- date input: type="date"
- search input: type="search"

### List, Tables & Forms

List markers can be given different appearances using the list-style-type and list-style image properties. Table cells can have different borders and spacing in different browsers. Forms are easier to use if the form controls are vertically aligned using CSS.
<br />
<br />
**list-style-type**
- bullet point styles
- images for bullets
- positioning the marker

### Events

- events are used by browsers to indicate when things have happened
- using event delegation to monitor for events that happen on all of the children of an element
- an event occurs on an element will trigger a JavaScript function.
- traditional DOM event handlers: `element.event = functionName`
- event listeners: `element.addEventListener('event', functionName [,Boolean]);`
- the flow of events only matters when the code has event handlers on an element and one of its ancestor or descendant elements

[<==Back](README.md)