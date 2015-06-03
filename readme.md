# JSS: The JSON Syndication Standard

> Modernizing the aging RSS/Atom standard.
> Relevant xkcd: [https://xkcd.com/927/](https://xkcd.com/927/)

## Copyright Notice

Copyright &copy; Patrick Arthur Brown (2015).

## Abstract

This document defines the JavaScript Object Notation Syndication Standard (JSS), a JSON-based Web content and metadata syndication format.

## Table of Contents

1. [Introduction](/introduction.md)
  1. [Rational](/introduction.md#rational)
  2. [Examples](/introduction.md#examples)
2. JSS Element Definitions
  1. Types
    1. String
    2. URI
    3. Datetime
    4. Version
    5. "Container"
  2. Container Elements
    1. jss
    2. feed
    3. entries
    4. authors
  3. Metadata Elements
    1. id
    2. title
    3. link
    4. updated
    5. published
    6. summary
    7. content
    8. revision
3. Sample Parsers
  1. JavaScript
  2. Elixir
4. References
