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

You must specify at least the first three colors:

* passed background color
* failed background color
* unknown background color

You can then optionally specify any number of the following colors (in this order):

* label background color
* text color
* status text color

In other words:

```
passed-bg-color,failed-bg-color,unknown-bg-color[,label-bg-color[,text-color[,status-text-color]]]
```

## Contributing

Simply forking this repository, edit [themes.json](themes.json), and sending a pull request.
