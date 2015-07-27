# more-css plugin for [Hexo](https://hexo.io)
> Compress CSS with [more-css](https://www.npmjs.com/package/more-css).

## Install
```bash
$ npm install hexo-more-css --save
```

## Options
You can configure this plugin in `_config.yml`.

```yaml
more_css:
  enable  : true
  exclude : *.min.css
  radical : true
```

- **enable** - Enable the plugin. Defaults to `true`.
- **exclude** - Exclude files.
- **radical** - Apply further minimization. Defaults to `true`.

## Alternatives
- [hexo-clean-css](https://www.npmjs.com/package/hexo-clean-css)

See the [CSS minification benchmark](https://goalsmashers.github.io/css-minification-benchmark/) for a comparison of CSS compressors.

## Changelog
See the [Changelog](./CHANGELOG.md) for a list of changes.

## License
    The MIT License (MIT)

    Copyright (c) 2015 Mark van Seventer

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.