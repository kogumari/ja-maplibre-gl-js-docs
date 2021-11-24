---
<!--
title: Display a map
-->
title: マップを表示

<!--
description: Initialize a map in an HTML element with MapLibre GL JS.
-->

MapLibre GL JSを使ってHTML要素内のマップを初期化します。

topics:
  - Getting started
  - Styles
thumbnail: simple-map
contentType: example
layout: example
hideFeedback: true
language:
- JavaScript
products:
- Mapbox GL JS
prependJs:
- "import Example from '../../components/example';"
- "import html from './simple-map.html';"
---

Initialize a map in an HTML element with MapLibre GL JS.

{{ <Example html={html} {...this.props} /> }}
