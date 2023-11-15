# SassC [![Build Status](https://travis-ci.org/sass/sassc-ruby.svg?branch=master)](https://travis-ci.org/sass/sassc-ruby) [![Gem Version](https://badge.fury.io/rb/sassc.svg)](http://badge.fury.io/rb/sassc)

Use `libsass` with Ruby!

This gem combines the speed of `libsass`, the [Sass C implementation](https://github.com/sass/libsass), with the ease of use of the original [Ruby Sass](https://github.com/sass/ruby-sass) library.

### libsass Version

[3.3.2](https://github.com/sass/libsass/releases/3.3.2)

## Usage

This library utilizes `libsass` to allow you to compile SCSS or SASS syntax
to CSS.  To compile, use a `SassC::Engine`, e.g.:

```ruby
SassC::Engine.new(sass, style: :compressed).render
```