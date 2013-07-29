# Intro

composer-packer is a CLI utility for pack `Composer Project` to *.tar.gz package. The package includes composer vendors for production enviorment.

It will useful to:

- Deploy your project to online servers.
- Build artifacts using CI, such as [jenkins](http://jenkins-ci.org), [drone.io](https://drone.io).
- Supply package to your customer.

`It works only under *unix`

# Install

Add `pagon/composer-packer` to your `composer.json`

```
"require-dev": {
  "pagon/composer-packer": "0.1.0"
}
```

Then

```
composer.phar update --dev
```

# Quick Start

Run command in your project root:

```
./vendor/bin/pack 0.1.0
```

Then you'll get the package under `build` direcotry, such as:

```
build/0.1.0.tar.gz
```

# License

(The MIT License)

Copyright (c) 2012 hfcorriez &lt;hfcorriez@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

