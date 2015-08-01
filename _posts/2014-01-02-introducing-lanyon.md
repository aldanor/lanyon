---
layout: post
title: Introducing Lanyon
---

~~~ python
import types

def func():
    pass

assert isinstance(func, types.FunctionType)
assert isinstance(types, types.ModuleType)
~~~
{:.line-numbers}

~~~ python
# Python 2.x
class B:
    pass

# let's just leave it at that
assert type(B) is not type
~~~


~~~ python
# Python 2.x only
class A(object):
    __metaclass__ = M
~~~
