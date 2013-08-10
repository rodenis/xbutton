xButton
========

Ultra-Light-weight button library for touch devices.

Usage
---------

in html:

		<head>
			<script type="text/javascript" src="../external/xbutton.js"></script>
		</head>
		<body>
			<div id="btn_id">xButton</div>
		</body>

in js:

		var somevar = 'cool';
		var btn = XButton('btn_id', somevar, onBtnClick, 'btn-down-class');

		function onOkBtnClick(rel) {
        	//do something
        	console.log(rel); //this will print 'cool'
    	}

Changelog
---------

### 0.2 ###

 + touch precision is now passed as parameter to constructor

### 0.1 ###

 * initial version


## License

(The MIT License)

Copyright (c) 2013 Denis Rodin &lt;denis.rodin@gmail.com&gt;

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
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.`