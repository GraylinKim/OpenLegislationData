What am I looking at?
=======================

This repository represents a fine grained history of all the changes made to a
small subset of the legislative data that Open Legislation delivers. Each commit
represents the changes parsed from a single SOBI update file. We intend to use
this repository internally for tracking errors to source files but we thought
that others might find it interesting as well.

Hopefully we'll be able to run hook git in through a full reindexing in the near
future. In the meantime, take a look and let us know what you think and most
importantly how we could make it more useful! You can find us via the New York
Senate's `Developer Network`_.

Questions and Answers
========================

How are you using it?
-------------------------

Internally, we are using ``git log <path>`` to track down the offending SOBI
files when we find errors in the legislative data downstream. This information
helps us shake out whatever bugs our parsers may have. We'll hopefully find some
other uses in the near future.


How can I use it?
--------------------

Within the limits of the license, I expect you could do anything you wanted!


Why should I care?
------------------------

We don't really know how, but we suspect that this might be useful to someone
out there. Here are a couple of reasons why you might care:

* You want visualizations of legislative process (using `Gource`_ for example)
* You want a convenient distribution/update system for our raw input data
* You want to host the open legislation API locally for speed/reliability

We're confident that people will come up with more practical and creative uses
for this kind of information. If you've got ideas let us know!

.. _Gource: http://code.google.com/p/gource/
.. _Developer Network: http://www.nysenate.gov/developers
