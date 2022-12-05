Adds an option to search engine that allows to filter cards by field's text length. It works by modifying the search under the hood.

[Download from AnkiWeb](https://ankiweb.net/shared/info/1488259640)

## Usage:
`len(FieldName) operator length`

## Available operators:
```
==
!=
>=
>
<=
<
```
## Examples:

```
len(FieldName) >= 2
=
FieldName:__*
```
```
len(FieldName) == 2
=
FieldName:__
```
```
len(FieldName) < 2
=
-FieldName:__*
```
```
len(FieldName) != 2
=
-FieldName:__
```


