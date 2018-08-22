Omaha Python Users Group Meeting, Nov 21, 2011
##############################################
:date: 2011-11-22 09:56
:author: admin
:category: code, MeetingNotes, Snippets
:slug: omaha-python-users-group-meeting-nov-21-2011
:status: published

Tonight's Meeting Topics:

-  `Django <https://www.djangoproject.com/>`__
-  Django and RESTful interfaces via
   `Piston <https://bitbucket.org/jespern/django-piston/wiki/Home>`__
   and `XML-RPC <https://launchpad.net/django-xmlrpc>`__
-  Message Queuing - specifically
   `RabbitMQ <http://www.rabbitmq.com/>`__,
   `ActiveMQ <http://activemq.apache.org/>`__ and
   `STOMP <http://stomp.github.com/>`__ and the 5 primary `usage
   patterns <http://www.rabbitmq.com/getstarted.html>`__.  And
   integrating MQs in Django with
   `Celery <http://celeryproject.org/>`__.
-  We also had a "follow me" presentation on getting started with
   `Selenium2 <http://seleniumhq.org/>`__'s
   `webdriver <http://seleniumhq.org/docs/03_webdriver.html>`__.  The
   following are my notes on the presentation:

::

    -- Selenium2 --

    Selenium RC vs Webdriver -
    Selenium - http://seleniumhq.org/
             - http://seleniumhq.org/docs/03_webdriver.html
    Why - http://seleniumhq.org/docs/appendix_migrating_from_rc_to_webdriver.html

    Firefox, Chrome, Ie, iOS, Android, Opera

    -- Setting up an environment --
      virtualenv --no-site-packages Se-Pres(entation)
      cd Se-Pres
      source bin/activate
      easy_install selenium
    Now fire up an interpreter:
      python
      from selenium import webdriver
      b = webdriver.Firefox()
      b.get('http://www.google.com/')
      b.page_source
      dir(b)
      b.name
      b.get_cookies()   (a list of dicts, each containing a cookie and support info)
      b.current_url

    >>> b.find_element_by_name('q')
    <selenium.webdriver.remote.webelement.WebElement object at 0x874b22c>
    >>> sbx = b.find_element_by_name('q')
    >>> sbx.send_keys('omaha python')
    >>> sbx.submit()
    >>> b.title
    u'omaha python - Google Search'

      b.find_element_by_name('foo')
    selenium.common.exceptions.NoSuchElementException

    -- Other Helpful things --
    unittest - http://docs.python.org/library/unittest.html#
    nose - http://readthedocs.org/docs/nose/en/latest/

    nose-testconfig - http://pypi.python.org/pypi/nose-testconfig/

The meeting concluded about 9pm when the venue closed but we continued
with a 15 minute parking lot track that included references to `Code
Complete <http://www.amazon.com/Code-Complete-Practical-Handbook-Construction/dp/0735619670>`__
and general development concepts.  Great Meeting! and everyone is
looking forward to the next.
