# Build Status Badge Themes

Themes for your [Buildkite build status badges](https://buildkite.com/docs/guides/build-status-badges).

![](http://media.giphy.com/media/pil2Ej4HWM7aU/giphy.gif)

## Current themes

| theme   | build passed                                                         | build failed                                                         | unknown                                                               |
|---------|----------------------------------------------------------------------|----------------------------------------------------------------------|-----------------------------------------------------------------------|
| default | ![](https://badge.buildkite.com/sample.svg?status=passed)              | ![](https://badge.buildkite.com/sample.svg?status=failed)              | ![](https://badge.buildkite.com/sample.svg?status=unknown)              |
| slack   | ![](https://badge.buildkite.com/sample.svg?status=passed&theme=slack)  | ![](https://badge.buildkite.com/sample.svg?status=failed&theme=slack)  | ![](https://badge.buildkite.com/sample.svg?status=unknown&theme=slack)  |
| github  | ![](https://badge.buildkite.com/sample.svg?status=passed&theme=github) | ![](https://badge.buildkite.com/sample.svg?status=failed&theme=github) | ![](https://badge.buildkite.com/sample.svg?status=unknown&theme=github) |
| saturn  | ![](https://badge.buildkite.com/sample.svg?status=passed&theme=saturn) | ![](https://badge.buildkite.com/sample.svg?status=failed&theme=saturn) | ![](https://badge.buildkite.com/sample.svg?status=unknown&theme=saturn) |
| flickr  | ![](https://badge.buildkite.com/sample.svg?status=passed&theme=flickr) | ![](https://badge.buildkite.com/sample.svg?status=failed&theme=flickr) | ![](https://badge.buildkite.com/sample.svg?status=unknown&theme=flickr) |
| solarized  | ![](https://badge.buildkite.com/sample.svg?status=passed&theme=solarized) | ![](https://badge.buildkite.com/sample.svg?status=failed&theme=solarized) | ![](https://badge.buildkite.com/sample.svg?status=unknown&theme=solarized) |
| mono    | ![](https://badge.buildkite.com/sample.svg?status=passed&theme=mono)   | ![](https://badge.buildkite.com/sample.svg?status=failed&theme=mono)   | ![](https://badge.buildkite.com/sample.svg?status=unknown&theme=mono)    |

## Syntax

The syntax for themes is:

```
passed-bg-color,failed-bg-color,unknown-bg-color[,label-bg-color[,text-color[,status-text-color]]]
```

You must specify at least the first three colors, but the rest are optional.

<img src="https://dl.dropboxusercontent.com/u/376613/color-syntax-diagram.svg" width="400">

1. passed background color *(required)*
2. failed background color *(required)*
3. unknown background color *(required)*
4. label background color *(optional)*
5. text color *(optional)*
6. status text color *(optional)*

## Contributing

Simply forking this repository, edit [themes.json](themes.json), and sending a pull request.
