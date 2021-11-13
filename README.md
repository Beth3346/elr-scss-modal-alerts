# elr-scss-modal-alerts

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-modal-alerts.svg?style=flat)](https://npmjs.com/package/elr-scss-modal-alerts)

a library of sass mixins

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-modal-alerts --save
yarn add elr-scss-modal-alerts
```

This package contains styles only. It's up to you to wire up the JavaScript. This allows these styles to be used with any JavaScript framework. Or no framework at all!

## Documentation

```scss
.dialog-blackout {
  @include elr-dialog;
}

.modal-alert {
  @include elr-modal-alert;
}
```

```html
<dialog role="alert" class="dialog-blackout">
  <div class="modal-alert">
    <header class="elr-modal-alert-header">
      <span class="elr-modal-alert-icon">
        <i class="fa fa-exclamation-circle" aria-hidden="true"></i>
      </span>
      <h2 class="elr-modal-alert-heading">This Is an Alert!</h2>
    </header>
    <div class="elr-modal-alert-content">
      <p>
        Are you sure you want to continue? This will delete all of your data and
        your account.
      </p>
    </div>
    <footer class="elr-modal-alert-footer">
      <menu>
        <button class="elr-button">Confirm</button>
        <button class="elr-button elr-button-ghost">Cancel</button>
      </menu>
    </footer>
  </div>
</dialog>
```

## License

SEE LICENSE IN LICENSE.md
