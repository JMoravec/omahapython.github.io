October 18, 2010 Meeting Notes
##############################
:date: 2010-10-19 12:22
:author: Steve
:category: MeetingNotes
:tags: MeetingNotes
:slug: october-18-2010-meeting-notes
:status: published

The attendees of tonight's meeting had been working with Django and the
talks centered around some cool features and extensions.

-  **`django-command-extensions <http://code.google.com/p/django-command-extensions/>`__**
   - "This is a repository for collecting global custom management
   extensions for the Django Framework."  Of particular interest was the
   `graph\_models <http://code.google.com/p/django-command-extensions/wiki/GraphModels>`__
   model which creates a GraphVis dot file (or an image) of your
   models.  You can specify the whole project or specific apps.  The
   code is
   `here <http://github.com/django-extensions/django-extensions>`__.
-  **"`Databrowse <http://docs.djangoproject.com/en/1.2/ref/contrib/databrowse/>`__**\ is
   a Django application that lets you browse your data.  Databrowse
   dynamically creates a rich, browsable Web site by introspecting your
   models."  This comes free with Django, and is similar to the admin
   interface, with the ability to click links to related tables to
   follow how the data is connected.
-  We were discussing how to easily get test data into the Django models
   when building a project and needing to build, test, tear down, build,
   test... and came up with two items:

   -  When your model is not changing much, Django comes with
      **`Fixtures <http://www.djangoproject.com/documentation/models/fixtures/>`__**. 
      "Fixtures are a way of loading data into the database in bulk.
      Fixture data can be stored in any serializable format (including
      JSON and XML)."
   -  When you are just beginning and have a sample set of data, and
      need to build a model, test it, throw it away, create another
      model, and loading the data each time, Jeff suggested using the
      "`writing custom django-admin
      commands <http://docs.djangoproject.com/en/1.2/howto/custom-management-commands/>`__"
      feature to write your own Django manage.py code.  Then you only
      have to tweak this to fit the new model and run to import.  This
      gives a place to put code when it doesn't belong in the finished
      app.

-  `Mercurial <http://hginit.com/>`__\ was suggested as a nice start to
   version control, especially for Windows users.  Jeff explained how
   committing small updates and documenting them helps in several ways:

   -  when a bug is noticed after several changes it is easy to unload
      each change and test to see where the problem is.
   -  you can try something "crazy" without much worry because it will
      be easy to revert to the previous version.
   -  easier to build and test changes before submitting them to a live
      project.

Panera's had good food and outlets near tables, but this particular
location is pretty loud, not a good choice for the future in my
opinion...
