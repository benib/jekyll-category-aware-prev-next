jekyll-category-aware-prev-next
==============

A jekyll generator to add category aware ```cat_next``` and ```cat_previous``` to ```page``` since jekyll's next and prev do not take the category into account.

This is based on the [gist](https://gist.github.com/stravid/4078840) of [David Strauss](https://github.com/stravid)

## Installation

Place lib/jekyll-category-aware-prev-next.rb in your _plugins folder

Or install it:

    $ gem install jekyll-category-aware-prev-next
    
## Usage

```{{ page.cat_next.url }}``` or ```{{ page.cat_previous.url }}```

## License

Copyright (C) 2013 Beni Buess (http://benel.net/)

The MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the “Software”), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
