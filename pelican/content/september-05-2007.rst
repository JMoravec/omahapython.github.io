September-05-2007
#################
:date: 2007-09-05 08:05
:author: admin
:category: MeetingNotes
:slug: september-05-2007
:status: published

Well we've managed to maintain a new meeting attendance level. There
were 6 of us again tonight at the meeting, 5 alumni and 1 new attendee.
The meeting started out with some introductions and talk
about \ `Py3K <http://www.python.org/dev/peps/pep-3000/>`__ alpha. We
then turned to talk about the various python implementations
C, \ `Iron <http://www.codeplex.com/Wiki/View.aspx?ProjectName=IronPython>`__, \ `Jython <http://www.jython.org/>`__
and \ `ActiveState's <http://www.activestate.com/Products/activepython/?_x=1>`__.

Talk then turned to available windowing options and what exactly was
built-in for python as opposed to 3rd party
libraries. \ `PythonCard <http://pythoncard.sourceforge.net/>`__, is the
project I was trying to recall. While not a windowing kit — it is based
on wxPython, it offers a nice entry point in to building a client GUI
for a python project for those new to python and GUI kits.

There were some random topics brought up and answered as we munched on
some quite good pizza.

We then broke out some code for
the \ `pyorhythms <http://code.google.com/p/pyorhythms/>`__, group
project. We talked about how the imports had been laid out, the over all
structure of the program and a number of questions from those new to
python were asked. What are those triple commented things
(`docstrings <http://www.diveintopython.org/getting_to_know_python/documenting_functions.html>`__)
how are they used, etc.

We then talked about the use of map statements and what was going to
happen to them in Py3K. Someone asked what does reduce do, and I didn't
have an answer then as I hadn't used it before, but have one now

"reduce(function, sequence)" returns a single value constructed by
calling the binary function function on the first two items of the
sequence, then on the result and the next item, and so on. For example,
to compute the sum of the numbers 1 through 10:

::

    >>> def add(x,y): return x+y
    ...
    >>> reduce(add, range(1, 11))
    55

\* \ `see <http://docs.python.org/tut/node7.html#SECTION007130000000000000000>`__

I did a live demonstration of pyorhythms and there was some pleasant
smiles and nods at seeing how
well \ `pylab <http://matplotlib.sourceforge.net/>`__, graphed
everything.

At the end of the meeting we handed out the door prize, "Beautiful
Code."

After the meeting some of stuck around and pondered the architecture of
the \ `google file
system <http://en.wikipedia.org/wiki/Google_File_System>`__, why doesn't
google offer a google apps appliance? and the possible ramifications
of\ `Grand Central <http://grandcentral.com/home>`__, and the
rumored \ `google phone <http://www.sltrib.com/business/ci_6803112>`__.

For those of you who couldn't attend we hope to see you next month (Brad
et al)

Source: \ `OmahaPythonUserGroup - PythonInfo
Wiki <http://wiki.python.org/moin/OmahaPythonUserGroup>`__
