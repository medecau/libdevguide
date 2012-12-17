Guidelines for writing good libraries/wrappers
==============================================

**APIs should be first level citizens**

 0. Reason
 1. Wrapper
 2. Abstraction

Reason
------

**Do you have an issue?**

If you don't experience the need to solve this problem your self,
don't expect to be able to know how to properly solve it.

 - You have to experience it yourself
 - Build it for you



Wrapper
-------

**We are all consenting adults.**

Adults should behave like adults and be trusted to behave accordingly.

 - Start with a wrapper of the API
 - Expose all the functionality
 - Don't hide methods or variables
 - Prepare for change
 - Make use of the API docs



Abstraction
-----------

**Humanize!**

These libraries are going to be used by other people,
they may not be visual tools but are none the less
interfaces that should be easy for a human to understand.

These tools should be [ergonomic](http://en.wikipedia.org/wiki/Human_factors_and_ergonomics).

 - If justifiable abstract from your wrapper - i.e. if the underlaying code is complex, layer your API
 - Simplify the wrapper API - i.e. "Hello World" in three lines
 - Provide sane defaults



Never forget
------------

**Keep these in mind as you go along.**

 - Don't repeat yourself, don't re-invent the wheel
 - Kill the megamoth - avoid mega monolithic methods
 - No Smurf names - if multiple names begin with the same word, remove it
 - Are you having fun?
 - The API is all that matters (to the end user)



Tools
-----

 - Use the de facto core lib - e.g. python requests for all things HTTP



Reference
---------

 - http://docs.python-guide.org/en/latest/writing/style/
 - http://www.codinghorror.com/blog/2012/07/new-programming-jargon.html
 - http://wynnnetherland.com/journal/what-makes-a-good-api-wrapper
 - https://speakerdeck.com/u/pengwynn/p/json-and-the-apinauts
 - https://speakerdeck.com/kennethreitz/api-driven-development
 - https://speakerdeck.com/holman/open-source-misfeasance
