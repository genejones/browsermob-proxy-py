
0.2.0 / 2012-06-18 
==================

  * pep8 --ignore=E501
  * DELETE /proxy/:port/
  * /proxy/:port/limits
  * /proxy/:port/blacklist
  * /proxy/:port/whitelist
  * fixing /proxy/:port/har/pageRef
  * fixing /proxy/:port/har/pageRef
  * fixing passing in a page ref as the name for the page in /proxy/:port/har
  * tests around /proxy/:port/har and some cleanup of the implementation
  * make /proxy/:port/headers work
  * wrapping selenium_proxy with webdriver_proxy since the project is more than just webdriver
  * extending the client to play nice with remote webdriver instances
  * create_proxy sounds and feels like a method to me, let's make it so
  * ensure the self.process exist, to reduce possibilities of AttributeError
  * check the path before attempting to start the server
  * wait longer than 3 seconds for the server to come up

0.1.0 / 2012-03-22 
==================

* Removed httplib2 in preference for requests
* Added support for setting headers

0.0.1 / 2012-01-16
==================

* Initial version
