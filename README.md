# Twitter Bootstrap 3 Support for Atom

Provides [Twitter Bootstrap 3][1] classes and HTML tags with autocompletion features.

Key Features:

  - Supports autocompletion of all helper classes in JavaScript, CSS and HTML
  - Snippet support for all components.
  - Autocompletion for **Glyphicons** and **Fontawesome**

## Templates

  - `html-`: Generates Basic HTML Template
  - `html-min`: Generates Basic HTML Template without comments

## Components

All components also have autocompletion support for extra options.

### Icons

The plugin has Glyphicon and Fontawesome support.

  - `icon`: Generates glyphicon icon snippet
  - `fa`: Generates fontawesome icon snippet

### Alert

  - `alert`
  - `alert-link`
  - `close`

### Badge

  - `badge`

### Breadcrumb

  - `breadcrumb`
  - `item`

### Buttons

  - `btn`
  - `btn-group`
  - `btn-group-vertical`
  - `btn-toolbar`
  - `btn-modal`

### Menus and Dropdowns

  - `dropdown`
  - `menudivider`
  - `menuheader`
  - `menuitem`

### Forms

  - `form-group`
  - `input-group`

### Labels

  - `label-`

### Lists

  - `list-group`
  - `list-inline`
  - `list-item`
  - `list-unstyled`

### Tabs and Navigations

  - `nav-pills`
  - `nav-tabs`
  - `nav-`
  - `navbar`: Generates standard navbar template
  - `navbar-drop`: Generates navbar dropdown item 

### Other Components

  - `pager`
  - `page-header`
  - `pagination`
  - `panel`
  - `progress-`
  - `table-`
  - `thumbnail`
  - `well`
  - `jumbotron`

## JavaScript Components

  - `modal`: Generates modal HTML
  - `accordion`: Generates accordion HTML
  - `carousel`: Generates carousel HTML

## Grid

  - `row`: Generates column container: `<div class="row"></div>`
  - `col-`: Generates column: `<div class="col-..."></div>`
  - `collg`: Generates large column: `<div class="col-lg-..."></div>`
  - `colmd`: Generates medium column: `<div class="col-md-..."></div>`
  - `colsm`: Generates small column: `<div class="col-sm-..."></div>`
  - `colxs`: Generates extra small column: `<div class="col-xs-..."></div>`
  - `con`: Generates container: `<div class="container"></div>`
  - `conf`: Generates fluid container: `<div class="container-fluid"></div>`

## Typograpgy

- `lead`: Lead class `<p class="lead">`
- `h1-`: Heading 1 `<h1>Text {<small>optional</small>}</h1>`
- `h2-`: Heading 2 `<h2>Text {<small>optional</small>}</h2>`
- `h3-`: Heading 3 `<h3>Text {<small>optional</small>}</h3>`
- `h4-`: Heading 4 `<h4>Text {<small>optional</small>}</h4>`
- `h5-`: Heading 5 `<h5>Text {<small>optional</small>}</h5>`
- `h6-`: Heading 6 `<h6>Text {<small>optional</small>}</h6>`
- `initialism`: Generates "initialism" text
- `blockquote-reverse`: Generates reverse blockquote
- `dl-horizontal`

### Notes
- Snippet funcionality has [some bugs][2], I hope it will be fixed by Atom team.
- More to come :)

### Demo
![Thats how it works!](https://dl.dropboxusercontent.com/u/490540/Images/atom-bs.gif)

[1]: http://getbootstrap.com/
[2]: https://github.com/atom/snippets/issues/15
