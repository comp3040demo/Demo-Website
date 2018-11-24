---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
# Regular Expression Documentation
A Regular expression (usually abbreviated as regex) is a distinct collection of characters that establish a search pattern. This guide will help you get started with regular expressions by going over the essential components that can be used to define them.

### The Basic Syntax
Regular expressions are of the format `/pattern/`, where 'pattern' describes an exact arrangement of characters that the regex will search for within a given text.

**Example** (JavaScript):
```
var input = "Look for abc";
var num =  input.search( /abc/ );
console.log(num);
// Output will be 10, since 10 is the location of abc in the string.
```
In the above example, `/abc/` is the regular expression, while `abc` is the pattern of characters to search for.
