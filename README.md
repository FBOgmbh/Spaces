# Spaces

| Bezeichnung / Auflösung |       | >= 768 | >= 1024 | >= 1440 | >= 1920 |
|-------------------------|-------|--------|---------|---------|---------|
| xxxs                    |    4  |     4  |     4   |     4   |     4   |
| xxs                     |    8  |     8  |     8   |     8   |     8   |
| xs                      |   12  |    12  |    12   |    12   |    12   |
| s                       |   16  |    16  |    16   |    16   |    16   |
| ms                      |   24  |    24  |    24   |    24   |    24   |
| m                       |   32  |    32  |    36   |    36   |    42   |
| l                       |   36  |    36  |    42   |    48   |    54   |
| xl                      |   42  |    42  |    54   |    64   |    76   |
| xxl                     |   48  |    54  |    64   |    76   |    96   |
| xxxl                    |   54  |    64  |    76   |    96   |   128   |

![Spaces Graph](https://fbogmbh.github.io/Spaces/img/spaces-graph.png)

## Installation

Install via `npm`, `yarn` or `bower`

```
$ npm install @fbo/spaces
```
```
$ yarn add @fbo/spaces
```
```
$ bower install spaces
```

## Usage

```css
var(--spaces-xxxs)
var(--spaces-xxs)
var(--spaces-xs)
var(--spaces-s)
var(--spaces-ms)
var(--spaces-m)
var(--spaces-l)
var(--spaces-xl)
var(--spaces-xxl)
var(--spaces-xxxl)
```

## Example
```css
.element {
  padding: var(--space-xxxs)
}
```
