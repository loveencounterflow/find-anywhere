
# Find Anywhere


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [What It Is](#what-it-is)
- [How to Use It](#how-to-use-it)
- [Implementation](#implementation)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->



## What It Is

very fast text searching with KWIC-like output, built with ripgrep

## How to Use It

```sh
find-anywhere --glob='*.coffee'  -Pi 'require' path/to/folder another/path
```

## Implementation

Slim wrapper around [ripgrep](https://github.com/BurntSushi/ripgrep/blob/master/GUIDE.md).

