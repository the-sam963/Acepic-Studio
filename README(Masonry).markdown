jquery-masonry-grid
-------------------

Simple, responsive and lightweight Masonry Grid jQuery Plugin.

#### Installation

Add the script before closing the `<body>` tag (make sure you use the right path):
```html
<!-- jQuery -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<!-- Masonry Grid Plugin -->
<script src="js/jquery.masonryGrid.js"></script>
```

#### Usage
There is a demo file `demo/index.html` in the repository you can use as reference.
These options are the default options so this usage would be a little redundant.
```js
<script>
    jQuery(document).ready(function($) {
        $('.my-masonry-grid').masonryGrid({
            'columns': 3,
            'breakpoint': 767
        });
    });
</script>
```


<!-- dist/jquery.masonryGrid.js linguist-language=JavaScript -->


MIT License

Copyright (c) 2019 Peter Breitzler

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
