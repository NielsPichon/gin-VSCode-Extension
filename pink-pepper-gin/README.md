# pink-pepper-gin

Pink pepper gin is a syntax highlighter for the python config manager gin.

Disclaimer: This is by no means an official package and there is no roadmap
for bug fixing.

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

None. If you find any, head out to the github repo and create an issue there.

## Release Notes

### 0.2.0
* Same as 0.0.2 and 0.1.0. Just a hickup in versioning with vsce

### 0.0.2
* Add support more several `@` references in a comma separated list.
* Fix bug where putting an `@` reference in brackets or square brackets would
break the tokenizer.

### 0.0.1
Initial release

