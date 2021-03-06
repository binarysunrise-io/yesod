## 1.4.14

* Added `WForm` to reduce the verbosity using monadic forms.
* Added `wreq` and `wopt` correspondent functions for `WForm`.

## 1.4.13

* Fixed `textareaField` `writeHtmlEscapedChar` trim "\r"

## 1.4.12

* Password field does not remember its previous value

## 1.4.11

* Fix warnings
* Fixed spelling errors and wording for `Yesod.Form.Functions.convertField`'s
  documentation

## 1.4.10

* Fixed `identifyForm` to properly return `FormMissing` for empty forms. [#1072](https://github.com/yesodweb/yesod/issues/1072)

## 1.4.9

* Added a `ToValue` instance for `Enctype` [#1296](https://github.com/yesodweb/yesod/pull/1296)

## 1.4.8

* Added Yesod.Form.I18n.Spanish

## 1.4.6

* Functor instances for Option/OptionList

## 1.4.5

* Foldable/Traversable instances for FormResult [#1089](https://github.com/yesodweb/yesod/pull/1089)

## 1.4.4.1

* runFormPost has wrong behavior for empty forms [#950](https://github.com/yesodweb/yesod/issues/950)

## 1.4.4

* Add a `Semigroup` instance

## 1.4.3

Added `jqueryDatePickerDayField`.

## 1.4.2.1

Documentation updates

## 1.4.2

Added `timeFieldTypeTime` and `timeFieldTypeText`, and deprecated `timeField`
itself.
