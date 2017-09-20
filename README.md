# jTimer

[![MIT License][license-image]][license-url]

It's a jquery plugin for time that control  the time with a structure like strftime with a high perfomance.

## How it work

When you use jTimer for get time with a structure that contains second you run an interval of 1 second, but when you use it for get time with a structure that contain: (minute you run an interval of 60 second, hours ==> interval of 3600 second, day, month....).
* So it improve perfomance by reducing the interval.

## Licence

jTimer is freely distributable under the terms of the [MIT license](https://github.com/laazebislam/jTimer/LICENSE

[license-image]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
[license-url]: LICENSE
