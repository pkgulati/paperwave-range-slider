[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/paperwave-range-slider)

## \<paperwave-range-slider\>

\<paper-range-slider\> allows users to select a sub-range by moving the slider knobs. It builds up on the official paper-slider component and provides all its the styling properties. The interactive nature of the slider makes it a great choice for picking price or year ranges.

## Usage

### Installation
```
npm i paperwave-range-slider
```
### In a html file
```html
<html>
  <head>
    <script type="module">
      import 'paperwave-range-slider/paperwave-range-slider.js';
    </script>
  </head>
  <body>
    <paperwave-range-slider
        min="0"
        max="150"
        lowValue="30"
        highValue="90"
        minInterval="20">
    </paperwave-range-slider>
  </body>
</html>
```
### In a Polymer 3 element
```js
import {PolymerElement, html} from '@polymer/polymer';
import 'paperwave-range-slider/paperwave-range-slider.js';

class SampleElement extends PolymerElement {
  static get template() {
    return html`
      <paperwave-range-slider
        min="0"
        max="150"
        lowValue="30"
        highValue="90"
        minInterval="20">
    </paperwave-range-slider>
    `;
  }
}
customElements.define('sample-element', SampleElement);
```

### Thank you for your interest :)