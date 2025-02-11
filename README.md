# gosort

[![Go Report Card](https://goreportcard.com/badge/github.com/jtpeller/gosort)](https://goreportcard.com/report/github.com/jtpeller/gosort)
[![Release](https://img.shields.io/github/release/jtpeller/gosort.svg?style=flat-square)](https://github.com/jtpeller/gosort/releases)
![GitHub License](https://img.shields.io/github/license/jtpeller/gosort)

## Overview

Sorting algorithms written in Go. This package contains sorts of various performance levels & Big-Os.

## Contents

Contains the following sorts:

- Bitonic
- Bogo
- Bubble
- Bucket
- Cocktail
- Comb
- Counting
- Cycle
- Gnome
- Heapsort
- Insertion
- Merge
- Odd-Even
- Pancake
- Pigeonhole
- Quicksort
- Radix
- Selection
- Shell
- Stooge
- Tim

## Usage

Installation can be achieved by:

1. Use this command to install the package:

    ```sh
    go get -u github.com/jtpeller/gosort
    ```

2. Import it:

    ```go
    import (
        gs "github.com/jtpeller/gosort"
    )
    ```

3. Then use it!

Example use on [my gosort benchmark repo](https://github.com/jtpeller/gosort-benchmark/)
