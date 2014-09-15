MessagePack for Lua (spec v5)
=============================

[![Build Status](https://travis-ci.org/fperrad/lua-MessagePack.png)](https://travis-ci.org/fperrad/lua-MessagePack)

``` lua
local mp = require 'MessagePack'
mpac = mp.pack(data)
data = mp.unpack(mpac)
```

Install
-------

You can use LuaRocks to install lua-MessagePack:

```
$ luarocks install lua-messagepack
```

or from the source, with:

```
$ make install
```

It is a pure Lua implementation, without any dependency.

Links
-----

* [Github](http://github.com/fperrad/lua-MessagePack/)
* [API reference](http://fperrad.github.io/lua-MessagePack/msgpack.html)

Copyright and License
---------------------

Copyright (c) 2012-2014 Francois Perrad [![rank](https://www.openhub.net/accounts/4780/widgets/account_rank.gif)](https://www.openhub.net/accounts/4780)

This library is licensed under the terms of the MIT/X11 license, like Lua itself.
