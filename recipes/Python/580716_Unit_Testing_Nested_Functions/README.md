## Unit Testing Nested Functions 
Originally published: 2016-11-10 09:21:38 
Last updated: 2016-11-10 10:23:11 
Author: Alfe  
 
Python allows the declaration of nested functions.  These are typically hard to unit test because using just the normal ways of calling they cannot be called from outside their surrounding function.  So they cannot be considered a clearly separated unit and thus cannot be unit tested.