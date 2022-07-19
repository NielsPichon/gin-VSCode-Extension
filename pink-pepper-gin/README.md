# pink-pepper-gin

Pink pepper gin is a syntax highlighter for the python config manager gin.

Disclaimer: This is by no means an official package and there is no roadmap
for bug fixing. But I'll try my best to address issues if you find any. Please
create an issue in the github repo if you find a bug or have a feature request.

## Features

Supports basic gin config syntax:

* python style module imports
* python style comments
* config variables
* scopes
* function calls
* macros (both using % and @) including inside brackets and/or as a
comma-separated list.

## Known Issues

@references within a dict spread over multiple lines don't get detected.

If you find any other issue, head out to the github repo and
create an issue there. Also feel free to create a pull request with a fix ;)

## Release Notes

### 0.4.1
* Fix issue where a % macro would be interpreted as a @ macro when a comma would
be added after it.

### 0.4.0
* Revamp grammar, getting read of python bindings
* Add support for multiline lists and tuples
* Support spaces after parathesis and other brakets
* color modules in imports
* dict support including multiline ones

### 0.3.3
* Support for lists and tuples of `%`macros.

### 0.3.2
* Add support for `include` statements.

### 0.3.1
*  Fix scopes with `@` references.

### 0.3.0
*  Fix failing `@` references recognition when a `.` exists un the name
(typically for `@module.Object` style references).

### 0.2.0
* Same as 0.0.2 and 0.1.0. Just a hickup in versioning with vsce

### 0.0.2
* Add support more several `@` references in a comma separated list.
* Fix bug where putting an `@` reference in brackets or square brackets would
break the tokenizer.

### 0.0.1
Initial release
