# Here be dragons!

**Warning**: This repository is **not** actively maintained, and may disapear at any moment.

#Angular Strap Popover

This is just the angular strap popover directive from the AngularStrap project with the following changes:

* The $tooltip service has been renamed to bsTooltip to prevent conflicts with the ui-bootstrap library
* The $popover service has been renamed to bsPopover for consistency
* A popover:hide event is listened on so if you need to close all popovers within the app at once simply emit this event.

This repo was created so that you can use it with the ui-bootstrap project which currently has limited support for popovers.
This module adds support for html in popovers as well as being able to open / show popovers via a custom trigger which ui-bootstrap currently doesn't provide.

All credits go to the original author Olivier Louvignes.

## Documentation and examples

+ Check the [documentation](http://mgcrea.github.io/angular-strap) and [changelog](https://github.com/mgcrea/angular-strap/releases).

## Quick start

+ Install AngularStrap with [Bower](https://github.com/bower/bower).

>
```bash
$ bower install angular-strap-popover --save
```

+ Include the required libraries is your `index.html`:

>
``` html
<script src="bower_components/angular/angular.js"></script>
<script src="bower_components/angular-animate/angular-animate.js"></script>
<script src="bower_components/angular-strap-popover/dist/angular-strap.min.js"></script>
<script src="bower_components/angular-strap-popover/dist/angular-strap.tpl.min.js"></script>
```

+ Inject the `mgcrea.ngStrap` module into your app:

>
``` js
angular.module('myApp', ['ngAnimate', 'mgcrea.ngStrap']);
```


## Authors

**Olivier Louvignes**

+ http://olouv.com
+ http://github.com/mgcrea



## Copyright and license

	The MIT License

	Copyright (c) 2012 - 2014 Olivier Louvignes

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
