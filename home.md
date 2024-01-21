This is my new website and it's using Simple.css. It's really cool. If you want to use it too, you can [visit their site](https://simplecss.org/).

```html
<p>Just trying a codeblock</p>
```

This is a css code block:

```css
/*this is a comment*/
a {
  color: red;
}
```

This is a JS code block:

```JS
/* this is a comment */

export class ZeroMd extends HTMLElement {
  get src() {
    return this.getAttribute('src')
  }

  set src(val) {
    this.reflect('src', val)
  }

  get manualRender() {
    return this.hasAttribute('manual-render')
  }

  set manualRender(val) {
    this.reflect('manual-render', val)
  }

  reflect(name, val) {
    if (val === false) {
      this.removeAttribute(name)
    } else {
      this.setAttribute(name, val === true ? '' : val)
    }
  }

```
