# faint-text
Sets the maximum line limit for web pages.

## Install

### Bower

If you are using Bower as your package manager:

```bash
$ bower install faint-text
```


## Usage

Your website's HTML structure has to be similar to this in order to work:

### SASS

```scss
// (line-height, max-line-number, faint-color)
@include faint-text(27, 10, #fff);
```
### jQuery

```js
$('#text').faint_text({
  
  // height of text
  line_height: 15, // -px
  
  // max number of rows
  max_line: 5
});
```
