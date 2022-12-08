# ScrollbarCss

**Custom scrollbar styling**

<br>

### CDN SOURCE

```html
<link href="https://msfpt.github.io/scrollbarcss/scrollbar.css" rel="stylesheet"/>
```
<br>

### EXAMPLE

<br>

Create a custom scrollbar :

```html
<section scrollbar="true" style="
    --scrollbar-background-color: #dcdcdc;
    --scrollbar-color: #1e1e1ed5;
    --scrollbar-track-rounded: 0;
    --scrollbar-thumb-rounded: 100px;
    --scrollbar-padding: 3px;
    --scrollbar-width: 8px;
"> {{ content }} </section>
```

<br>

Or to hide the scrollbar :

```html
<section scrollbar="hide"></section>
```