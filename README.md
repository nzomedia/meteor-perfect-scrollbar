# Perfect Scrollbar

https://noraesae.github.io/perfect-scrollbar/ version 0.6.16 packaged for **Meteor**
I made this because, i couldn't find an updated version of perfect-scrollbar for meteor.
To use it in your project:
 1. create a folder named "packages" in your project's root dir.
 2. "git clone" the repo in that folder.
 3. Then meteor add nzomedia:perfect-scrollbar.

```
```
___


## Example Usage
#### JavaScript:
```js
$(function() {
    $('#Demo').perfectScrollbar();
});
```

#### HTML:
```html
<div id="Demo">
  <div class="item">......</div>
  <div class="item">......</div>
  <div class="item">......</div>
</div>
```
#### Css:
```sass
#demo {
  position: relative; // Required
  height: 200px; // Optional
}
```

