vendor/bin/phpunit -c core --group mymodule

export SIMPLETEST_BASE_URL='http://sitedomain.com'
vendor/bin/phpunit -c core sites/all/modules/mymodule/tests/src/Functional/MyModuleModelTest.php

vendor/bin/phpunit -c core sites/all/modules/mymodule/tests/src/Unit/MyModuleModelTest.php