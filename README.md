[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/owner/my-element)


# WebComponent Star Rating

Webcomponent for displaying star ratings <star-rating> without other dependecies.

## Demo/Playground

[Demo and Playground Page here ...](https://davitmdesign.github.io/wc-star-rating/index.html)

## Installation

Paste the import link in your "head" section.

```html
<link rel="import" href="https://davitmdesign.github.io/wc-star-rating/star-rating.html">
```

## Usage

To display the stars, you must place the element.

```html
<star-rating width="160" score="2.5"></star-rating>
```

That's it.

## Possible attributes

width="400" | score="50%" | colors="#aaa,#333"

Example:

<!---
```
<custom-element-demo>
  <template>
    <link rel="import" href="https://davitmdesign.github.io/wc-star-rating/star-rating.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<star-rating width="160" score="2.5"></star-rating>
<star-rating width="220" score="4" colors="grey,red"></star-rating>
<star-rating width="300" score="50%" colors="#BDBDBD,#B8860B"></star-rating>
```


| attributes        |     values                        |                |
| ----------------- |-----------------------------------|----------------|
| width             | 200                               | required       |
| score             | 50%, 3, 4.5                       | required       |
| colors            | name or hex (grey,#ffff00)        | optional       |


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
