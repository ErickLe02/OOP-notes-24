Essential parts of coding style
Indentation
New lines
Whitespace
Comments
Naming conventions

Header and class/method/function comments

### Problems with a coding standard
Lack of formal trainning
Programming language differences
Difficult to formally define check or coorect
Difficult to maintain
Lots of corner cases ??
Religious arguments ??
bike shed painting??

Naming
Proper consistnat naming
Use terms from the problem domain as much as possible

|Category|Semantics|Convention|Example|
|---|---|---|---|
|Classes|_things_ not _actions_|PascalCase|`class Token`|
|Fields/Variables/Parameters|_things_|camelCase|`int totalSize;`|
|C++ Methods/Functions|_actions_|camelCase|`void sortNames();`|
|C Functions|_actions_|under_score/camelCase|`srcml_archive_get_unit()`|
|Constant scalar values|_things_|UPPERCASE|`const int MAX_SIZE = 100;`|
|C-Preprocessor/cpp variables|_things_|UPPERCASE|`#ifndef INCLUDE_XML_HPP`|
Favor doxygen-style function comments

## passing parameter types

|Direction|Primitive|Object|
|---|---|---|
|IN|T|const T&|
|OUT, IN/OUT|T&|T&|
Examples:
int n
const std::string& s
int& total
std::string& palindrome

passing an IN parameter object by value instead of const reference IS BAD

Functions
All functions require a comment before both the declaration and the definition
Favor  doxygen-style function comments
@param For each parameter
@return For the general return purpose
@retval Specific return values

