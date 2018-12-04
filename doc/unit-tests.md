Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the ar3nad tests manually, launch src/test/test_ar3na .

To add more ar3nad tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the ar3na-qt tests manually, launch src/qt/test/ar3na-qt_test

To add more ar3na-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
