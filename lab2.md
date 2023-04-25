# Lab Report 2

## Part 1

![Image](StringServer.png)

![Image](stringserverex1.png)

The handlerequest method is being called. The relevant argument is the url you give it. The url would be http://localhost:4000/add-message?s=How%20are%20you.
The value of strs would be "Hello" and then after the /add path it would be "Hello \n How are you". The parameters array would be {"s", "How are you"}. The 
parameters array doesn't change at all because it was just created.

![Image](stringserverex2.png)

The handlerequest method is being called again. The argument would still be the url. The url would be http://localhost:4000/add-message?s=Hi%20lab%20grader.
The value of strs would be "Hello \n How are you" and then after the path it would be "Hello \n How are you \n Hi lab grader". The parameters array would be 
{"s", "Hi lab grader"}. This again wouldn't change because it was just created in this instance.

## Part 2

