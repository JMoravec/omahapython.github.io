the Google Command Line Tool
############################
:date: 2010-06-22 00:30
:author: admin
:category: code, PythonApps
:slug: the-google-command-line-tool
:status: published

Google just
announced, \ `GoogleCL <http://code.google.com/p/googlecl>`__ a
command-line utility that provides access to various Google services.
GoogleCL is a pure Python application that uses the \ `Python gdata
libraries <http://code.google.com/p/gdata-python-client/>`__ to make
Google Data API calls from the command line.  It streamlines tasks such
as posting to a Blogger blog, adding events to Calendar, or editing
documents on Google Docs.

For example:

::

    $ google blogger post --blog "My blog" --tags "python, googlecl, development" my_post.html
    $ google calendar add "Lunch with Jason tomorrow at noon"
    $ google docs edit --title "Shopping list" --editor vim

Read more at the \ `GoogleCL project
page <http://code.google.com/p/googlecl>`__, or jump right to
the \ `examples <http://code.google.com/p/googlecl/wiki/ExampleScripts>`__.

I think this is cool, because I just started reading up on the
`gdata-python-services <http://code.google.com/p/gdata-python-client/>`__
to interactively retrieve information from a google docs spreadsheet.
