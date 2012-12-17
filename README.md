Guidelines for writing good libraries/wrappers
==============================================

The Wrapper
-----------

We are all consenting adults
 
 - Start with a wrapper of the API.
 - Expose all the functionality.
 - Don't hide methods or variables.
 - Prepare for change.
 - Make use of the API docs.



Abstraction
-----------

Humanize!
 
 - If justifiable abstract from your wrapper.
 - Simplify the wrapper API
 - Provide sane defaults



Never forget
------------

 - Don't repeat yourself, don't re-invent the wheel.
 - Kill the megamoth - avoid mega monolithic methods
 - No Smurf names - if multiple names begin with the same word, remove it.
 - Are you having fun?



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
