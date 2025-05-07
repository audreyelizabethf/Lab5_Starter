# Lab 5 - Starter
Audrey Elizabeth Fernandez

[expose](https://audreyelizabethf.github.io/Lab5_Starter/expose.html)
[explore](https://audreyelizabethf.github.io/Lab5_Starter/explore.html)

**1.  Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.**

No because unit tests are good for debugging on a smaller scale. A message feature has a lot of moving parts and thus would not be a good candidate for unit testing.
  

**2.Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.**

Yes because this test would be a quick check on a smaller feature and changing other features in the app probably won't affect the character limit. You could easily check if messages under 80 characters pass and if messages over 80 characters fail.
 
