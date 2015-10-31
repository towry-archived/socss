# socss

## Namespace

* Namespaces are placed in a `_[page_]namespace.scss` file, the `page` is optional.
* Namespaces are ends with an underscore: `_`, for example: `a_`, `b_`, `header_`.
* Namespaces are meaningless, so you can have `a_`, `ksjdfl_` namespace.
* Never have style namespace.
* Namespaces in your namespace file should be in alphabetical order.

## Base and Common style

* Your base and common style should be begin with an underscore: `_`, for example:
`_x-grid`, `_x-row`, `_x-col`.
* Your base and common style should be unique.

## Page specific style

* Must be under a namespace. for example, there is a namespace: `form_`, then, page specific style should be write in this way: `form__page-specific`, note, there are two underscores `__` between namespace and page specific class.

## Other class name

Other class name like `header`, `title` which without underscore, must be place under a page specific style. for example: 

```
// scss
.form__page-specific {
  .title {
      font-size: 20px;
  }
}
```
