# Change Log

All notable changes to the "pink-pepper-gin" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

### [0.4.1]
- Fix issue where a % macro would be interpreted as a @ macro when a comma would be added after it.

### [0.4.0]

- Revamp grammar, getting read of python bindings
- Add support for multiline lists and tuples
- Support spaces after parathesis and other brakets
- color modules in imports
- dict support including multiline ones

### [0.3.3]

- Support for lists and tuples of `%`macros.

### [0.3.2]

- Add support for `include` statements.

### [0.3.1]

- Fix scopes within `@` references.

### [0.3.0]

- Fix failing `@` references recognition when a `.` exists un the name
(typically for `@module.Object` style references).

### [0.2.0]

- Add support for comma-separated lists of `@` references

### [0.0.1]

- Initial release