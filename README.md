
# Bare Arduino Project

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*

- [About](#about)
- [How to install and use](#how-to-install-and-use)
- [Text editors](#text-editors)
	- [Sublime Text - SublimeClang](#sublime-text---sublimeclang)
	- [Vim - YouCompleteMe](#vim---youcompleteme)
- [Contributing](#contributing)
- [Copyright and License](#copyright-and-license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## About

Ever wanted to start a new [Arduino](http://arduino.cc/) project...

*	**without** using the terrible *Arduino IDE*?
*	**to be able to** organize your `directory tree` as you like?
*	**to be able to** put all your libraries in `libs`, your sources in `src`, your tests in `test` and your binaries in `bin`?
*	**to be able to** use `C++11` and `avr-gcc -v 4.8`?

If you answered **yes** to one of the above, this [Bare Arduino Project](https://github.com/weareleka/arduino-project) is just what you're looking for! :)

Based on what we've learned on our [Moti project](http://github.com/weareleka/moti), this repo will allow you to:

*	move away from the Arduino IDE
*	use `C++11` for your standard coding
*	use `avr-gcc 4.8` to compile your code
*	use `make` to compile, `make upload` to upload, thanks to [Sudar](https://github.com/sudar/)'s incredible project [Arduino-Makefile](https://github.com/sudar/Arduino-Makefile)
*	use your favorite text editor to write your code

To put it in a nuttshell, it allows you to **write Arduino code, as you would write anything else !**

## How to install and use

The full procedure is detailed in [INSTALL.md](./INSTALL.md).

## Text editors

Because we are so awesome, we also provide your with 2 famous text editors configurations!

### Sublime Text - SublimeClang

To code in C/C++, we highly recommend using [SublimeClang](https://github.com/quarnster/SublimeClang), even if the plugin is not maintained anymore. As far as we can tell, it works beautifully well and will save you a lot of time! :)

As [quarnster](https://github.com/quarnster/) puts it:

> Clang plugin for Sublime Text 2 providing auto complete suggestions for C/C++/ObjC/ObjC++. It'll also optionally parse the code as it's typed and show errors and warnings.

The [`bare-arduino.sublime-project`](./bare-arduino.sublime-project) contains all you need to be up and running. Feel free to customize it to your needs with different `flags` for example.

### Vim - YouCompleteMe

Vim is our default text editor and we use [Valloric](https://github.com/Valloric) incredible vim plugin, [YouCompleteMe](https://github.com/Valloric) for errors and code completion.

As Valloric puts it:

> YouCompleteMe is a fast, as-you-type, fuzzy-search code completion engine for Vim. It has several completion engines: an identifier-based engine that works with every programming language, a semantic, Clang-based engine that provides native semantic code completion for C/C++/Objective-C/Objective-C++ (from now on referred to as "the C-family languages"), a Jedi-based completion engine for Python, an OmniSharp-based completion engine for C# and an omnifunc-based completer that uses data from Vim's omnicomplete system to provide semantic completions for many other languages (Ruby, PHP etc.).

The [`.ycm_extra_conf.py`](./.ycm_extra_conf.py) contains everything to be up and running. Beware that you really need to customize it for it to work properly. Each library must be added by hand to use auto completion.

## Contributing

Help is always more than welcome. If you want to take part in this project, please, make sure you read our [Contributing guidelines](./CONTRIBUTING.md).

##Copyright and License

```
The MIT License (MIT)

Copyright (c) 2014 Ladislas de Toldi - ladislas at weareleka dot com

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
```
