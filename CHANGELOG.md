# Change Log

## 0.2.1

fix: avoid false syntax errors from comments in include and namespace: with, type in comments

## 0.2.0

- align basic token highlighting with the current Heta PEG grammar
- highlight common syntax errors in identifiers, assignments, dictionary values, titles, notes, and include statements
- improve numeric literals and quoted assignment strings

## 0.1.13

- display `NaN`, `Infinity` as numbers in dictionary
- num and assignments errors highlight
- incorrect title display

## 0.1.12

- highlight unit expressions like `1/hour` as a single token inside dictionary/array values
- fix false-positive highlighting for `true`/`false`/`null` inside longer identifiers
- tune TextMate scopes for better theme compatibility (assignment operator, dictionary keys/braces, single-quoted strings)

## 0.1.11

- fix bug to use strings like this: `"hello \" world"`

## 0.1.10

- highlight `null`

## 0.1.9

- remove pattern from captures in `include`
- fix scopes

## 0.1.8

- fix bug inside arrays
- add Sublime format description

## 0.1.3-0.1.7

- Fix element styles

## 0.1.2

- Initial release
