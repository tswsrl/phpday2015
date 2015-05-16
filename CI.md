Martin Fowler
Step 2: Automate build and tests.
Code quality advantages, use standards
Lots of standards: which one to use? Once you use one stick to it
POPULAR STANDARDS
PHP-FIG
PSR 1 e 2 Code quality
SensioLabs cs.sensiolabs.com
Other standards (zend, wp symphony)
PHP_CodeSniffer
PHP Mess Detector
Codacy
codeclimate.com (SPONSOOOR)
Unit tests
 *  Unit: The minimum part
 *  Unit test: The test for that
If you don’t have time to unit-test everything try at least to add anything you can.
PHPUNIT
SimpleTest No maintained but still runs.
Atoum
Selenium WEB Driver

Automating the build
 1. Phing YE OLDE ONE
 2. Maven PHP www.php-maven.org
 3. phpDocumentor 2
 4. CruiseControl (PHPUnderControl)
 5. Jenkins
 6. Travis CI
 7. SonarQube

Technical debt
 *  Show proof that it is better to do code refectoring than live with the legacy code.

