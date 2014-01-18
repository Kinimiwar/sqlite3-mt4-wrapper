sqlite3-mt4-wrapper
===================

Wrapper DLL for sqlite3 usage from MT4, which is forked from [Shmuma/sqlite3-mt4-wrapper](https://github.com/Shmuma/sqlite3-mt4-wrapper).

## Howto

* Download [zip of develop branch](https://github.com/micclly/sqlite3-mt4-wrapper/archive/develop.zip)
* Extract it
* Copy ``sqlite3_wrapper.dll`` to ``<MT4 root>/experts/libraries/``
* Copy ``sqlite.mqh`` to ``<MT4 root>/experts/include/``
* In your EA/Indicator/Script, add following include

        #include <sqlite.mqh>

* Try sqlite wrapper functions

## Sample

* [test_binding.mq4](https://github.com/micclly/sqlite3-mt4-wrapper/blob/develop/test_binding.mq4) is a sample of insert and fetch, by prepared statements with parameter bindings.
