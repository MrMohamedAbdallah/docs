---
id: 9526d59a-3abe-444f-b9a4-b0a8ed2fa880
blueprint: modifiers
modifier_types:
  - string
title: Backspace
---
Removes a specified number of characters from the end of a string.

```yaml
title: supercalifragilisticexpialidocious
```

::tabs

::tab antlers
```antlers
{{ title | backspace:29 }}
```
::tab blade
```blade
{{ Statamic::modify($title)->backspace(29) }}
```
::

```html
super
```
