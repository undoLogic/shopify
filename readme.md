Open 'theme.liquid'

UNDER the base.css add a custom css file
{{ 'base.css' | asset_url | stylesheet_tag }}

```css
<link rel="stylesheet" href="{{ 'added-styles-A.css' | asset_url }}" type="text/css">
```
