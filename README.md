# Vue loading overlay Bootstrap 5

## Features / What is it?

Just a simple loading overlay.

## Donate

Find this project useful? You can support me with a Paypal donation:

[Make Paypal Donation](https://www.paypal.com/donate/?hosted_button_id=2XCS6R3CTC5BA)

## Installation

For a quick install, run this from your project root:
```bash
mkdir -p resources/js/tools/pix-overlay
wget -O resources/js/tools/pix-overlay/pix-overlay.js https://raw.githubusercontent.com/pixsil/pix-overlay/main/pix-overlay/pix-overlay.js
wget -O resources/js/tools/pix-overlay/pix-overlay.vue https://raw.githubusercontent.com/pixsil/pix-overlay/main/pix-overlay/pix-overlay.vue
```

Add this to your app.js
```javascript
// import
import PixOverlay from "./tools/pix-overlay/pix-overlay";


// use in vue
Vue.use(PixOverlay);
```

## Usage

```html
<pix-overlay :show="loading">
    // some html
</pix-overlay>
```
