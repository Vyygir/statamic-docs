---
id: ef9c992a-33ed-4b26-84b1-b7e0d9b2b2dd
blueprint: variables
title: 'Current User'
---
The current user.

::tabs
::tab antlers
```antlers
{{ current_user }} {{ name }} {{ /current_user }}

{{ current_user:email }}
```
::tab blade
```blade
{{ $current_user['name'] }}

{{ $current_user['email'] }}
```

```html
Example User

user@example.com
```