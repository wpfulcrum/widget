# Widget Module

[![Build Status](https://travis-ci.org/wpfulcrum/widget.svg?branch=develop)](https://travis-ci.org/wpfulcrum/widget) 
[![Latest Stable Version](https://poser.pugx.org/wpfulcrum/widget/v/stable)](https://packagist.org/packages/wpfulcrum/widget) 
[![License](https://poser.pugx.org/wpfulcrum/widget/license)](https://packagist.org/packages/wpfulcrum/widget)

The Fulcrum Custom Widget Module makes your job easier for adding custom widgets to your project. Pass it a configuration and it handles the rest for you.

## Features

- Registration is handled for you.
- Widget form is handled for you.
- Widget rendering is handled for you.

You build:

- the configuration
- form view file
- widget view file

If you need custom processing, use the `Widget` class as your base class.  Then just build what's different to minimize your work.

## Installation

The best way to use this component is through Composer:

```
composer require wpfulcrum/widget
```

## Dependencies

This module requires:
 
- at least PHP 5.6
- WordPress 4.8+
- Fulcrum 3+

## Contributing

All feedback, bug reports, and pull requests are welcome.