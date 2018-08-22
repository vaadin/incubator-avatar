[![Available in Vaadin_Directory](https://img.shields.io/vaadin-directory/v/vaadinincubator-avatar.svg)](https://vaadin.com/directory/component/vaadinincubator-avatar)
[![Stars in Vaadin_Directory](https://img.shields.io/vaadin-directory/stars/vaadinincubator-avatar.svg)](https://vaadin.com/directory/component/vaadinincubator-avatar)

# &lt;incubator-avatar&gt;

[&lt;incubator-avatar&gt;](https://vaadin.com/components/incubator-avatar) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

[<img src="https://raw.githubusercontent.com/vaadin/incubator-avatar/master/screenshot.png" width="200" alt="Screenshot of incubator-avatar">](https://vaadin.com/components/incubator-avatar)

## Example Usage

```html
  <incubator-avatar header="Unsaved changes" confirm-text="Save" on-confirm="save"
    cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
    Do you want to save or discard your changes before navigating away?
  </incubator-avatar>
```
