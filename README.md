# sure
> Version 0.1.0

# What

a assertion toolbox that works fine with [nose](http://code.google.com/p/python-nose/)

# Usage

    from sure import that

    assert that("something").is_a(str)
    assert that("something").like("some")
    assert "thing" in that("something")

    class FooBar:
        attribute_one = "simple"

    assert "attribute_one" in that(FooBar)
    assert that(FooBar).equals(FooBar)

    # and so on ...

# license

sure is under MIT license, so that it can be embedded into your
project, and ran within your sandbox. It can also be put together with
[py-dom-xpath](http://code.google.com/p/py-dom-xpath/)

    Copyright (C) <2010>  Gabriel Falcão <gabriel@nacaolivre.org>

    Permission is hereby granted, free of charge, to any person
    obtaining a copy of this software and associated documentation
    files (the "Software"), to deal in the Software without
    restriction, including without limitation the rights to use,
    copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the
    Software is furnished to do so, subject to the following
    conditions:

    The above copyright notice and this permission notice shall be
    included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
    OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
    NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
    HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
    WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
    FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
    OTHER DEALINGS IN THE SOFTWARE.
