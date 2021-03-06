# tlc
This tool can clean up the list output from `OneTab` of Google Chrome extension.

see also:

- OneTab - Chrome Web store 
    - https://chrome.google.com/webstore/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall

## Description
`tlc` is the initial letter of the tab list cleaner.

You can delete duplicate URLs and same name from the list output from `OneTab` of Google Chrome extension. In addition, you can also check whether the URL is accessible at the same time and delete it from the list.

## Demo

![](https://user-images.githubusercontent.com/6448792/29307394-abc87114-81dc-11e7-9ef1-7516a639a985.gif)


## Features
- It is made by golang so it supports multi form.
- Easy operation just by specifying the file.

## Requirement
- Go 1.8+
- spf13/cobra: A Commander for modern Go CLI interactions 
	- https://github.com/spf13/cobra
- cheggaaa/pb: Console progress bar for Golang 
	- https://github.com/cheggaaa/pb
- And that file output from your `OneTab`

## Usage

```	console
$ ./tlc run your_file -w
```
Please see the help.

```	console
$ ./tlc --help                                                   
This tool is OneTab URL list cleaner

Usage:
  tlc [command]

Available Commands:
  run         Clean the list of "OneTab"
  version     Print the version number of tlc

Use "tlc [command] --help" for more information about a command.
```

## Installation

```	console
$ go get github.com/uchimanajet7/tlc
```

## Author
[uchimanajet7](https://github.com/uchimanajet7)

- OneTab のTabリストを整理するCLI をgolang で作ってみた #golang #onetab - uchimanajet7のメモ 
	- http://uchimanajet7.hatenablog.com/entry/2017/08/16/120000

## Licence
[Apache License 2.0](https://github.com/uchimanajet7/tlc/blob/master/LICENSE)
