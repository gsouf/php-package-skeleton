CONTRIBUTING
============

Any contribution is welcome.

Tests
-----

All contributions must be tested following as much as possible the current test structure:
- One class = one test file in ``test/suites`` and the class must be annotated with ``@covers``
- One class method = one method in the test class
- Complex tests must be placed in the ``scenario`` directory

Look at current tests in ``test/suites`` for more details


Coding standards
----------------

- Check standards: run ``./test/bin/phpcs.bash``
- fix standards: run ``./test/bin/phpcbf.bash``
