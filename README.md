#Colorizr

Colorizr is a simple Gem that changes the text color of any String on the command line. It extends the `String` class.

##Getting Started

To install Colorizr...

`gem install colorizr` (_Note: You may need to add `sudo` to the beginning_)

...Then, in your project...

`require 'colorizr'`

...That's it!

##How To Use

To create the color methods, run this command during your project's setup:

`String.create_colors`

Then, to format a String in a particular color, just add a color method.
```
test = "Hello world!"
puts test.red
```
You can also see a list of available colors...
```
String.colors
=> [:red, :green, :yellow, :blue, :pink, :light_blue, :white, :light_grey, :black]
```
...Or an example of each color.

`String.sample_colors`

##License

**MIT License**

Copyright (c) [2016] [Mike Johns]

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
