December-05-2007
################
:date: 2007-12-05 08:09
:author: admin
:category: MeetingNotes
:slug: december-05-2007
:status: published

.. raw:: html

   <div>

We met at Godfather's Pizza (75th & Pacific)

.. raw:: html

   </p>

Burch has arranged for us to meet at Rosken's Hall on the University of
Nebraska at Omaha's campus. Watch for more specific details to follow on
the mail list and on the website.

Jeff gave a presentation/overview of \ `functional
programming <http://www.omahapython.org/multiparadigm.html>`__ in Python

Eli talked about:

-  Google's \ `MapReduce <http://labs.google.com/papers/mapreduce.html>`__
   - a software framework implemented by Google to support parallel
   computations over large (greater than 100 terabyte) data sets on
   unreliable clusters of computers.
-  `HardOCP <http://lucene.apache.org/hadoop/>`__ - Hadoop
   implements MapReduce, using the Hadoop Distributed File SystemHDFS)
   (see figure below.) MapReduce divides applications into many small
   blocks of work.
-  `glusterfs <http://www.gluster.org/glusterfs.php>`__ - a clustered
   file-system capable of scaling to several peta-bytes.

Jeff gave a short presentation on anecdotes about optimizing Python
code.

#. Premature speed optimizations are the root of all evil
#. Enhanced readability is an optimization
#. Follow pep8 and use structured code — you get an automatic speed up
   by just keeping your name spaces clean and local
#. Know where your code is spending it's time and optimize their
   first — when in doubt, optimize the inner loop first
#. Remove the dots - short circuit lookup intensive operations. i.e.
   \_lstappend = lst.append
#. Check out \ `shedskin <http://mark.dufour.googlepages.com/>`__
   — although it can compile entire programs, it is perhaps most useful
   at speeding up a targeted area of code. ShedSkin makes writing a C++
   based importable module child's play compared to using C++, and
   bindings — see "optimize the inner loop first"

We enjoyed some decent pizza and shop talk between talks.

The door prize, "Python in a Nutshell" was won by Burch. A big Thank You
to O'Reilly for the door prizes at our meetings. Thanks to you to
Marsee!

.. raw:: html

   </div>
