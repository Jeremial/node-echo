# node-echo


A shell like echo for node.js with sync and async method

## Usage:

    echo = require('echo');
    echo(args...);

### to `stdout` or `stderr`

##### echo(anything[, echo.STDOUT|STDERR[, callback]])
echo anything to `stdout` or `stderr`, with or without a callback

##### echo.sync(anything[, echo.STDOUT|STDERR])
sync version, echo anything to `stdout` or `stderr`

### to local file

##### echo(anything, flag, fileName, callback)
echo anything to localfile.

flag can be `>` or `>>`, and its default to `>>`, so echo default likes shell's
`echo 'content' >> file`

##### echo.sync(anything, flag, fileName)
sync version, echo anything to localfile.

flag can be `>` or `>>`, and its default to `>>`, so echo default likes shell's
`echo 'content' >> file`

## Test:

    npm install
    npm test

## License

The MIT License (MIT)

Copyright (c) 2013 Jeremial jeremial90@gmail.com

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
