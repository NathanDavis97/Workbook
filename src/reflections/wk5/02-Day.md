# Week 5 Day 2
__1/12/2020__

##  What are the three types of relationships?
The three types of relationships are one to one, one to many, and many to many. Many to many are by far the most complicated, but one to many is the most common.

## What are the benefits of the traditional linking of relationships instead of Embedding?
Embedding forces you to store the information in the object, while linking means storing a key on the objects in order to reference each other. Linking allows you to find the other object with the  first objects information instead of storeing them both together.

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
One of the challenges is that the amount of items that have to connect to each other and how. Depending on how many items you need to connect to, you have to decide how to build out your objects to allow for the connections. One item might need to connect to hundreds of another item, but each of those items might need to connect to a few other items individually. So, depending on how you need to connect them, you first have to decide how to build the objects.


### Daily Project link 
https://github.com/NathanDavis97/winter20-gregslist-server