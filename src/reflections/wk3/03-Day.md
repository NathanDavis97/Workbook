# Week 3 Day 3
__12/16/2020__

## What are the two common operations that we will set in the handler?
Two common operations for the handler are checking true value and validation. The handler can check the value and make sure it truly is what it is supposed to be and whether or not you ar etrying to set the right thing.

## What do you have to make sure you are doing every Get to insure the value does not become undefined?
When you simply console.log a value that is in a proxied object you will get the console log in the handler, but not the object you wanted. This is because you need to return the proxied object from the handler so you can console.log it later.

## are some of the benefits of the proxy object that we are using in our structure for applications?
Proxy objects are helpful because they allow you to have an object that represents data that can be set up to be accessed only in certain ways. These proxy objects can be a huge help in keeping privacy.
