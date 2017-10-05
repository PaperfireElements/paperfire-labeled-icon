[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/PaperfireElements/paperfire-labeled-icon)

# \<paperfire-labeled-icon\>

An element following material design for bottom navigation

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="paperfire-labeled-icon.html">
    <link rel="import" href="../iron-icon/iron-icon.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paperfire-labeled-icon label="Gallery" active><svg style="width:24px;height:24px" viewBox="0 0 24 24">
    <path fill="#000000" d="M13,3V9H21V3M13,21H21V11H13M3,21H11V15H3M3,13H11V3H3V13Z" />
</svg></paperfire-labeled-icon>
<paperfire-labeled-icon label="Content" ><svg style="width:24px;height:24px" viewBox="0 0 24 24">
    <path fill="#000000" d="M4,5V7H21V5M4,11H21V9H4M4,19H21V17H4M4,15H21V13H4V15Z" />
</svg></paperfire-labeled-icon>
```

Designed to work with `iron-icon` and `iron-selector`

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
