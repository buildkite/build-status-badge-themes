# Build Status Badge Themes

Themes for your [Buildbox build status badges](https://buildbox.io/docs/guides/build-status-badges).

![](http://media.giphy.com/media/pil2Ej4HWM7aU/giphy.gif)

## Current themes

| theme   | build passed                                                         | build failed                                                         | unknown                                                               |
|---------|----------------------------------------------------------------------|----------------------------------------------------------------------|-----------------------------------------------------------------------|
| default | ![](https://badge.buildbox.io/sample.svg?status=passed)              | ![](https://badge.buildbox.io/sample.svg?status=failed)              | ![](https://badge.buildbox.io/sample.svg?status=unknown)              |
| slack   | ![](https://badge.buildbox.io/sample.svg?status=passed&theme=slack)  | ![](https://badge.buildbox.io/sample.svg?status=failed&theme=slack)  | ![](https://badge.buildbox.io/sample.svg?status=unknown&theme=slack)  |
| github  | ![](https://badge.buildbox.io/sample.svg?status=passed&theme=github) | ![](https://badge.buildbox.io/sample.svg?status=failed&theme=github) | ![](https://badge.buildbox.io/sample.svg?status=unknown&theme=github) |
| saturn  | ![](https://badge.buildbox.io/sample.svg?status=passed&theme=saturn) | ![](https://badge.buildbox.io/sample.svg?status=failed&theme=saturn) | ![](https://badge.buildbox.io/sample.svg?status=unknown&theme=saturn) |
| mono    | ![](https://badge.buildbox.io/sample.svg?status=passed&theme=mono)   | ![](https://badge.buildbox.io/sample.svg?status=failed&theme=mono)   | ![](https://badge.buildbox.io/sample.svg?status=unknown&theme=mono)    |

## Syntax

The syntax for themes is:

```
passed-bg-color,failed-bg-color,unknown-bg-color[,label-bg-color[,text-color[,status-text-color]]]
```

What this means is, you must specify at least the first three colors, but the rest are optional.

![color syntax diagram](color-syntax-diagram.svg)

1. passed background color
2. failed background color
3. unknown background color
4. label background color (optional)
5. text color (optional)
6. status text color (optional)

## Contributing

Simply forking this repository, edit [themes.json](themes.json), and sending a pull request.
