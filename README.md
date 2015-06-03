#AngularJs Multiselect Typeahead directive

A simple and easily customizable angularjs directive to a multiselect typeahead input box. No jQuery or AngularUi required!

[Demo](http://codepen.io/kirederik/pen/PqpEYP) 

## Getting started

Download the necessary files as you wish:

* with Bower: `bower install angular-multiselect-typeahead`
* Cloning this repository

## Dependencies

* AngularJS 

## Usage

1. Include the css and the javascript in your app:

```html
<link rel="stylesheet" href="/path/to/angular-multiselect-typeahead.css" />

<script src="/path/to/angular.js"></script>
<script src="/path/to/angular-multiselect-typeahead.js"></script>
```

2. Register the "typeahead" module in your aplication module
```javascript
app.module('myApp', ['typeahead']) ...
```

3. Add the element in your html:
```html
 <typeahead ng-model="select" items="list" displaytag="name" displayitem="name"></typeahead> 
```

Where:

* `ng-model` is the selected items
* `items` is the typeahead list
* `displaytag` is the property that will appear in the tag
* `displayitem` is the property that will appear in the typeahead list 
