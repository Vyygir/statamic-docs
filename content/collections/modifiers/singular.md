---
id: ef2a1b64-d2a6-4ade-988d-33b279e47bfd
blueprint: modifiers
modifier_types:
  - string
title: Singular
---
Get the singular form of an English word.

```yaml
word: nickles
```

::tabs

::tab antlers
```antlers
{{ word | singular }}
```
::tab blade
```blade
{{ Statamic::modify($word)->singular() }}
```
::

```html
nickle
```
