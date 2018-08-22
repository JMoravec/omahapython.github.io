July 16 Meeting Notes
#####################
:date: 2014-07-19 12:49
:author: Steve
:category: MeetingNotes
:slug: july-16-meeting-notes
:status: published

[caption id="attachment\_332" align="alignright" width="207"]\ |GIL|
GIL[/caption]

We had a good discussion, mainly focused on Global Interpreter Lock.  A
description can be found
`here <https://wiki.python.org/moin/GlobalInterpreterLock>`__, and
article
`one <http://www.jeffknupp.com/blog/2012/03/31/pythons-hardest-problem/?utm_source=feedblitz&utm_medium=FeedBlitzRss&utm_campaign=FeedBlitzRss&utm_content=Python%27s+Hardest+Problem>`__\ and
`two <http://www.jeffknupp.com/blog/2013/06/30/pythons-hardest-problem-revisited/?utm_source=feedblitz&utm_medium=FeedBlitzRss&utm_campaign=FeedBlitzRss&utm_content=Python%27s+Hardest+Problem%2C+Revisited>`__
by Jeff Knupp.

`Eventlet <http://eventlet.net/>`__\ was also introduced -

    a concurrent networking library for Python that allows you to change
    how you run your code, not how you write it.

-  It uses epoll or kqueue or libevent for \ `highly scalable non-blocking I/O <http://en.wikipedia.org/wiki/Asynchronous_I/O#Select.28.2Fpoll.29_loops>`__.

-  `Coroutines <http://en.wikipedia.org/wiki/Coroutine>`__ ensure that
       the developer uses a blocking style of programming that is
       similar to threading, but provide the benefits of non-blocking
       I/O.

-  The event dispatch is implicit, which means you can easily use
       Eventlet from the Python interpreter, or as a small part of a
       larger application.

|eventlet|

 

Finally we had some discussion about adding a bit of structure to the
meetings and advanced notice of the meeting agendas.  If you would like
to share at a meeting, or know about a presenter traveling through Omaha
please email the list and we will set it up.

 

.. |GIL| image:: http://www.omahapython.org/blog/wp-content/uploads/2014/07/killGIL-207x300.jpg
   :class: wp-image-332 size-medium
   :width: 207px
   :height: 300px
.. |eventlet| image:: http://www.omahapython.org/blog/wp-content/uploads/2014/07/eventlet-300x278.png
   :class: aligncenter wp-image-333 size-medium
   :width: 300px
   :height: 278px
   :target: https://github.com/colinhowe/eventlet_visualiser
