# bootstrap-table-rails [![Gem Version](https://badge.fury.io/rb/bootstrap-table-rails.png)](http://badge.fury.io/rb/bootstrap-table-rails)

bootstrap-table-rails provides the [bootstrap-table](https://github.com/wenzhixin/bootstrap-table/)
plugin as a Rails engine to use it within the asset pipeline.

## Installation

Add this to your Gemfile:

```ruby
gem "bootstrap-table-rails"
```

and run `bundle install`.

## Usage

In your `application.js`, include the following:

```js
//= require bootstrap-table
```

In your `application.css`, include the following:

```css
/*
 *= require bootstrap-table
 */

```
Dir tree:

``` tree
vendor/
└── assets
    ├── images
    │   └── icon.png
    ├── javascripts
    │   ├── bootstrap-table-locale-all.js
    │   ├── bootstrap-table.js
    │   ├── extensions
    │   │   ├── bootstrap-table-accent-neutralise.js
    │   │   ├── bootstrap-table-angular.js
    │   │   ├── bootstrap-table-auto-refresh.js
    │   │   ├── bootstrap-table-click-edit-row.js
    │   │   ├── bootstrap-table-cookie.js
    │   │   ├── bootstrap-table-copy-rows.js
    │   │   ├── bootstrap-table-defer-url.js
    │   │   ├── bootstrap-table-editable.js
    │   │   ├── bootstrap-table-export.js
    │   │   ├── bootstrap-table-filter-control.js
    │   │   ├── bootstrap-table-filter.js
    │   │   ├── bootstrap-table-flat-json.js
    │   │   ├── bootstrap-table-group-by-v2.js
    │   │   ├── bootstrap-table-group-by.js
    │   │   ├── bootstrap-table-i18n-enhance.js
    │   │   ├── bootstrap-table-jumpto.js
    │   │   ├── bootstrap-table-key-events.js
    │   │   ├── bootstrap-table-mobile.js
    │   │   ├── bootstrap-table-multi-toggle.js
    │   │   ├── bootstrap-table-multiple-search.js
    │   │   ├── bootstrap-table-multiple-selection-row.js
    │   │   ├── bootstrap-table-multiple-sort.js
    │   │   ├── bootstrap-table-natural-sorting.js
    │   │   ├── bootstrap-table-print.js
    │   │   ├── bootstrap-table-reorder-columns.js
    │   │   ├── bootstrap-table-reorder-rows.js
    │   │   ├── bootstrap-table-resizable.js
    │   │   ├── bootstrap-table-select2-filter.js
    │   │   ├── bootstrap-table-sticky-header.js
    │   │   ├── bootstrap-table-toolbar.js
    │   │   ├── bootstrap-table-tree-column.js
    │   │   └── bootstrap-table-treegrid.js
    │   └── locale
    │       ├── bootstrap-table-af-ZA.js
    │       ├── bootstrap-table-ar-SA.js
    │       ├── bootstrap-table-ca-ES.js
    │       ├── bootstrap-table-cs-CZ.js
    │       ├── bootstrap-table-da-DK.js
    │       ├── bootstrap-table-de-DE.js
    │       ├── bootstrap-table-el-GR.js
    │       ├── bootstrap-table-en-US.js
    │       ├── bootstrap-table-es-AR.js
    │       ├── bootstrap-table-es-CL.js
    │       ├── bootstrap-table-es-CR.js
    │       ├── bootstrap-table-es-ES.js
    │       ├── bootstrap-table-es-MX.js
    │       ├── bootstrap-table-es-NI.js
    │       ├── bootstrap-table-es-SP.js
    │       ├── bootstrap-table-et-EE.js
    │       ├── bootstrap-table-eu-EU.js
    │       ├── bootstrap-table-fa-IR.js
    │       ├── bootstrap-table-fr-BE.js
    │       ├── bootstrap-table-fr-FR.js
    │       ├── bootstrap-table-he-IL.js
    │       ├── bootstrap-table-hr-HR.js
    │       ├── bootstrap-table-hu-HU.js
    │       ├── bootstrap-table-id-ID.js
    │       ├── bootstrap-table-it-IT.js
    │       ├── bootstrap-table-ja-JP.js
    │       ├── bootstrap-table-ka-GE.js
    │       ├── bootstrap-table-ko-KR.js
    │       ├── bootstrap-table-ms-MY.js
    │       ├── bootstrap-table-nb-NO.js
    │       ├── bootstrap-table-nl-NL.js
    │       ├── bootstrap-table-pl-PL.js
    │       ├── bootstrap-table-pt-BR.js
    │       ├── bootstrap-table-pt-PT.js
    │       ├── bootstrap-table-ro-RO.js
    │       ├── bootstrap-table-ru-RU.js
    │       ├── bootstrap-table-sk-SK.js
    │       ├── bootstrap-table-sv-SE.js
    │       ├── bootstrap-table-th-TH.js
    │       ├── bootstrap-table-tr-TR.js
    │       ├── bootstrap-table-uk-UA.js
    │       ├── bootstrap-table-ur-PK.js
    │       ├── bootstrap-table-uz-Latn-UZ.js
    │       ├── bootstrap-table-vi-VN.js
    │       ├── bootstrap-table-zh-CN.js
    │       └── bootstrap-table-zh-TW.js
    └── stylesheets
        ├── bootstrap-table.css
        └── extensions
            ├── bootstrap-table-auto-refresh.css
            ├── bootstrap-table-click-edit-row.css
            ├── bootstrap-table-filter-control.css
            ├── bootstrap-table-group-by-v2.css
            ├── bootstrap-table-group-by.css
            ├── bootstrap-table-jumpto.css
            ├── bootstrap-table-multiple-selection-row.css
            ├── bootstrap-table-reorder-rows.css
            ├── bootstrap-table-sticky-header.css
            └── bootstrap-table-tree-column.css
```



## Examples

See the [demo page](http://bootstrap-table.wenzhixin.net.cn) for examples how to use the plugin

## License

* The [bootstrap-table](https://github.com/wenzhixin/bootstrap-table/) plugin is licensed under the
[MIT License](http://opensource.org/licenses/mit-license.html)
* The [bootstrap-table-rails](https://github.com/bjevanchiu/bootstrap-table-rails) project is
 licensed under the [MIT License](http://opensource.org/licenses/mit-license.html)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
