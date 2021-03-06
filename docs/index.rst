girc
====
A modern Python IRC library for Python 3.4, based on asyncio. Currently in development

.. WARNING::
    This is barely in alpha right now. This is pre-alpha. If you use this, ANYTHING can change without any notice whatsoever, everything can be overhauled, and development may even stop entirely without any warning.

If you would like to help build this, awesome! Otherwise, I'd stay away for now and use another library like `irc <https://bitbucket.org/jaraco/irc>`_ or `irc3 <https://github.com/gawel/irc3/>`_.


Features
--------
This library is in development, so these features may be in various levels of completion right now.

* Incoming and outgoing events.
* Info and state tracking.
* Dicts, lists, and strings using server-based IRC casemapping.
* IRCv3 capability support.
* Escaping and unescaping IRC formatting for ease-of-use (bold, colours, etc).


Why?
----
I've been using another IRC library for a long time. It's been pretty good, but I need more features. Handling both incoming and outgoing messages, automatic information tracking, converting IRC formatting (bold/colours/etc) to and from an escaped, human-readable and writable format.

I've looked at some other libraries, but they're usually either too low-level, too involved, or too 'magic' for my liking. That said, this one is planning to be pretty magic, but it's going to be magic in a way I think makes sense.

So I decided to write my own. As part of `mammon-ircd <https://github.com/mammon-ircd/mammon>`_, a nice low-level library called `ircreactor <https://github.com/mammon-ircd/ircreactor>`_ was developed. This is also a chance to give that a spin from the client side, rather than the server side.


Library
-------

.. toctree::
   :maxdepth: 2
   :numbered:

   library/reactor
   library/serverconnection
   library/formatting
   library/events


DevNotes
--------

.. toctree::
   :maxdepth: 2

   devnotes/state-tracking


:ref:`genindex`
---------------
