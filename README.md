# react-bootstrap-multiselect

[![NPM version](https://badge.fury.io/js/react-bootstrap-multiselect.svg)](http://badge.fury.io/js/react-bootstrap-multiselect)
[![Dependency Status](https://david-dm.org/skratchdot/react-bootstrap-multiselect.svg)](https://david-dm.org/skratchdot/react-bootstrap-multiselect)
[![devDependency Status](https://david-dm.org/skratchdot/react-bootstrap-multiselect/dev-status.svg)](https://david-dm.org/skratchdot/react-bootstrap-multiselect#info=devDependencies)


## Description

A multiselect component for react (with bootstrap). This is a react port of:

[bootstrap-multiselect](https://github.com/davidstutz/bootstrap-multiselect)


## Getting Started

1) Install the module with: `npm install --save react-bootstrap-multiselect`

2) Create your module (you need to use something like browserify to build)

```javascript
var React = require('react');
var Multiselect = require('react-bootstrap-multiselect');
var someReactComponent = React.createClass({
    render: function () {
        return (
            <Multiselect />
        );
    }
});
```

3) Include the multi-select CSS in your project somewhere. The CSS file is here: [bootstrap-multiselect.min.css](https://raw.githubusercontent.com/skratchdot/react-bootstrap-multiselect/gh-pages/css/bootstrap-multiselect.min.css) (don't hotlink- download and host your own copy)

```html
<link rel="stylesheet" href="bootstrap-multiselect.min.css" type="text/css" />
```

## Documentation

For in depth documentation, see the original
[bootstrap-multiselect](https://github.com/davidstutz/bootstrap-multiselect) project page.


## Links

- [Source Code](https://github.com/skratchdot/react-bootstrap-multiselect)
- [Live Demo](http://projects.skratchdot.com/react-bootstrap-multiselect/)
- [Original Plugin](https://github.com/davidstutz/bootstrap-multiselect)


## License

Copyright (c) 2014 skratchdot  
Uses the original [bootstrap-multiselect](https://github.com/davidstutz/bootstrap-multiselect) license.
