# Python automation testing basics
Understanding the basics with data driven UI testing with Python, [Selenium](https://pypi.python.org/pypi/selenium) &amp; [nose](https://nose.readthedocs.org/en/latest/) / [unittest](https://docs.python.org/2/library/unittest.html).

Note: '[nose](https://nose.readthedocs.org/en/latest/)' is used only for standalone execution. As I use PyCharm with '[pydev](https://www.jetbrains.com/pycharm/help/remote-debugging.html)' support for debugging and '[unittest](https://docs.python.org/2/library/unittest.html)' module for running the tests, I am actually not using it.

For DDT you have to install '[ddt](https://ddt.readthedocs.org/en/latest/index.html)'.

## Automated unit tests
A testcase is created by subclassing 'unittest.TestCase'. The individual tests are defined with methods whose names start with the letters 'test'. This naming convention informs the test runner about which methods represent tests. (see ui_test_basics.py)

Credits:

- http://selenium-python.readthedocs.org/en/latest/index.html
- http://engineering.aweber.com/getting-started-with-ui-automated-tests-using-selenium-python/
- https://code.google.com/p/selenium/wiki/PythonBindings
- http://scrolltest.com/selenium-testcase-with-nose-in-python/
- http://scrolltest.com/selenium-test-case-using-data-driven-testing-in-python/
- http://seleniummaster.com/sitecontent/index.php/selenium-web-driver-menu/selenium-test-automation-with-python-menu/188-python-selenium-web-driver-data-driven-framework
