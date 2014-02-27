

<!-- Start test/fixtures/dox-parser.coffee -->

# The parser

This is a incredible parser.

Dox
Copyright (c) 2010 TJ Holowaychuk &lt;tj@vision-media.ca&gt;
MIT Licensed

## parseComments(js)

Parse comments in the given string of `js`.

See: exports.parseComment

### Params: 

* **String** *js* 

### Return:

* **Array** 

## parseComment(str)

Parse the given comment `str`.

 The comment object returned contains the following:

 - `tags`  array of tag objects
 - `description` the first line of the comment
 - `body` lines following the description
 - `content` both the description and the body
 - `isPrivate` true when &quot;@api private&quot; is used

See: exports.parseTag

### Params: 

* **String** *str* 

### Return:

* **Object** 

## parseTag()

Parse tag string &quot;@param {Array} name description&quot; etc.

### Params: 

* **String** ** 

### Return:

* **Object** 

## parseTagTypes(str)

Parse tag type string &quot;{Array|Object}&quot; etc.

### Params: 

* **String** *str* 

### Return:

* **Array** 

## parseCodeContext(str)

Parse the context from the given `str` of js.

This method attempts to discover the context
for the comment based on its code. Currently
supports:

  - function statements
  - function expressions
  - prototype methods
  - prototype properties
  - methods
  - properties
  - declarations

### Params: 

* **String** *str* 

### Return:

* **Object** 

Escape the given `html`.

### Params: 

* **String** *html* 

### Return:

* **String** 

<!-- End test/fixtures/dox-parser.coffee -->

