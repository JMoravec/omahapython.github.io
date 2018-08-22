Book suggestions for a Perl programmer wanting to learn Python
##############################################################
:date: 2012-10-23 12:14
:author: Steve
:category: info
:slug: book-suggestions-for-a-perl-programmer-wanting-to-learn-python
:status: published

This was on our email list recently:

For a project I'm deciding to branch out and force myself to do much of
it in Python. I'm well versed in Perl (functional and object oriented),
**anyone have any suggestions for a Python book to pick up that isn't
going to spend the first 1/3 of the book describing what a variable is
and other absolute beginner issues?**

For what it's worth, I'm probably going to start with Python 2.7 and
jump into 3 when I'm done with my project (many of the modules are 2.X
only from what I understand).

Thanks!

Dan

| P.S. I'm watching this guys Python tutorial videos. Good video
  production value, and easy enough to follow along as long as you're
  quick with the pause button.
| https://www.youtube.com/watch?v=5uf6wGL8B7g&feature=relmfu

**Chad**: Check out: *a byte of python*

**Jay**: *Dive into python* is probably the best free resource for
learning the language along with the python pocket reference once you've
got the basics down.

**Eli**: *http://docs.python.org/tutorial/* is really good, I leaned
using that and haven't seen anything as else as good for someone who's
already a programer.

With that and the language reference at
*http://docs.python.org/reference/index.html* you have all you need.

**Tim**: Wow, that was timely. I just answered this less than a day ago
for someone off list. My response below (and yes I do write books in
response to IM questions, thank you very much ^\_^):

"*Hitchhikers guide to python"* is better than most of the books I've
purchased for it. It's a lot like Dive Into Python (the good parts of
DIP), but actually updated: *http://docs.python-guide.org*

The "official documentation" is better by far than docs for many other
languages I've seen. Nice examples, good organization (IMHO), etc.
*http://docs.python.org/*

Start with the hitchhikers guide, then use docs.python.org for reference
and further reading. If you do come across someone who needs the "I
wanna program" level stuff, or even just a refresher or project to get
working in the language, the thing that I point to for people to learn
python is *http://learnpythonthehardway.org/*. Goes through it like a
class, free (HTML version), question/answer stuff, self exams, etc.

One of the first things when people start working here that aren't used
to python but might be touching my code is to send them through that
book. Where it falls down is teaching libraries, advanced usage of
things like decorators etc. but lo and behold, that's where the
hitchhiker's guide shines ^\_^

Once you're through the hitchhikers guide and comfortable digging
through the official docs, you're as up to speed as a vast majority of
the non-professional python people I've come across. From that point,
it's maybe hitting PyPi (think CPAN) to check out if there's a library
to do something specific, or digging through the official docs. You
pretty much just keep referencing *docs.python.org* to look up how to do
X or what that one exception type was you used that one time.

FYI - Remember to look in the official lib first. Python is much more
"batteries included" than many languages, perl included (IMHO).

**Matthew**: There is a nice low cost and terse book called "*Python
phrasebook*" by Brad Dayley which does a good job of explaining the
language and demonstrating how to do various common tasks. Reading
through it will help you understand the language and it has lasting
value as a small desk-side reference for those times when you need to
jog your memory.

An answer to a question you didn't ask that you need to be aware of is
that the Python community is in a transition while the language makes a
somewhat major shift. Python 2.7 and Python 3.3 are both supported
versions of Python and are different enough that you can get confused if
you're not aware of it.

I wish I could say, "As a new comer to Python, definitely start with
Python 3.x," but alas there are some really great python modules that
haven't quite yet added Python 3 support. (For example, it is still
experimental with Django)

Worse, there are few good books that focus on Python 3. So there is a
good chance that you will write your code with Python 2.7. There's
nothing wrong with this, but you should be aware of it. For example, if
you're using Ubuntu 12.10 you'll have to install Python 2.7 with apt. If
you're using Windows make sure to download the proper version.

**Jeff**: I would suggest a read over the *Zen of Python
http://www.python.org/dev/peps/pep-0020/*

When coming from another language, understanding the goals of the
language helps when you are transitioning/learning. I believe it helps
resolve the mental dissonance that occur when you encounter "Why to they
do X when I use to to X' or Y in my previous language?"

I get quite a bit out of reading well written code in the target
language. My first experience with Python was an mp3 server script
(edna.py) happily written by Greg Stein (a good programmer). I was
coming from a C, VB, Pascal type languages.
