Open 'theme.liquid'

UNDER the base.css add a custom css file
{{ 'base.css' | asset_url | stylesheet_tag }}

in Assets/  
```css
<link rel="stylesheet" href="{{ 'added-styles-A.css' | asset_url }}" type="text/css">
```





Sezzle

App app
- activate checkout button 
- second time activate pay link

Settings - Apps and sales channels

Settings - Payments - add Sezzle

