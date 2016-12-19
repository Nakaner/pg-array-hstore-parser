pg-array-hstore-parser
======================

pg-array-hstore-parser is a header-only C++ 11 library to parse the string representation of arrays and hstore
fields of a PostgreSQL database.

Dependencies
------------

* Catch testing framework (included in this repository)
* cmake (for building the tests)
* no other dependencies  except the standard library and a C++11 capable compiler.


Unit Tests
----------

Unit tests are located in the `test/` directory. The Catch framework is used, all
necessary dependencies are included in this repository.

Build the tests:
```mkdir build
cd build
cmake ..
make```

Run the tests:
```
make test
```


License
-------

see COPYING.md
