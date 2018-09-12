# Bootstrap3-Contextual-Modals

## To Use
1) Add `bootstrap/mixins/modals.less` to the standard `bootstrap/mixins/` directory in your local bootstrap install.
2) Update your `bootstrap/mixins.less` file to add the new modals mixin. Example file: `bootstrap/mixins.less`
3) Replace your `bootstrap/modals.less` file with the `bootstrap/modals.less` in this repo. Alternatively just update your `bootstrap/modals.less` with the `.modal-variant`.

When you want a contextual modal, just add the type to the class of the `.modal`.

```
  <div class="modal modal-primary">...</div> 
  <div class="modal fade modal-secondary">...</div> 
  <div class="modal modal-info">..</div> 
```
