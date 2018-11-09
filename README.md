# samp-compat

Allow connections from previously incompatible SA-MP clients into newer or older servers
allowing you to have players from 2 versions playing together without additional software

## Supported versions:
* 0.3.7-R2 (both R2-1 and R2-2): Supports clients from 0.3.DL
* 0.3.DL: Supports clients from 0.3.7 (both R1 and R2)

## Installation

Simply install to your project:

```bash
sampctl package install AGraber/samp-compat
```

Optionally, include in your code:

```pawn
#include <compat>
```

## Building
This repo took Southclaws' [SA-MP plugin boilerplate](https://github.com/Southclaws/samp-plugin-boilerplate/blob/master/README.md), very detailed instructions of building can be found there.

## Thanks to
* SA-MP server structures provided by contributors of the
[YSF plugin](https://github.com/IllidanS4/YSF):
files containing this are governed by its MPL 1.1 license
* [Southclaws](https://github.com/Southclaws) for his neat boilerplate
* [SA-MP Team](http://sa-mp.com) for making versions incompatible for some reason,
allowing me to release this plugin
