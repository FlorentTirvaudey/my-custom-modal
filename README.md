# My custom modal

This package is used in an Openclassroom Project, it's a simple modal plugin.

Start to import this package to your project :
```sh
    npm i my-custom-modal-p14
```

And use it in your project :
```sh
    import { Modal } from 'my-custom-modal-p14'
```

You can use different custom classe to modify modal's style, by changing :

```
    1. Text
        - modify textStyle prop
    2. Modal
        - modify modaleStyle prop
    3. Overlay
        - modify overlayStyle prop
    4. Button
        - modify buttonStyle prop
```

You can also add a custom content in your modal by modifying `content` prop.

And give to `closeModal` prop a function to close your modal.
