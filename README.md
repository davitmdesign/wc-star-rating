# WebComponent Star Rating

[Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)

Webcomponent for displaying star ratings <star-rating> without other dependecies.

## Installation

Import the WebComponent in your <head> section.

`<link rel="import" href="https://davitmdesign.github.io/wc-star-rating/star-rating.html">`

You can use the Github Static Pages (href) or clone the repository for your local environments.

## Usage

To display the stars, you must place the element.

`<star-rating></star-rating>`

That's it.

## Possible attributes

width="400" | percent="90" | stars="4.5" | colors="#aaa,#333"

Example: `<star-rating width="100" stars="4.5" colors="#ddd,#f1cb1"></star-rating>`

Example: `<star-rating width="200" percent="50" colors="#ddd,#f1cb1"></star-rating>`


| attributes        |     values                        |   default      |
| ----------------- |-----------------------------------|----------------|
| width             | numeric (200)                     | 100            |
| percent           | numeric (50)                      | 100            |
| stars             | numeric (4 4.5 4,2)               | 5              |
| colors            | name or hex (grey,#ffff00)        | #ddd,#f1cb14   |


# Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
