# Week 3 Day 4
__12/17/2020__

## What problems does the Observer Pattern seek to solve?
The observer pattern tries to solve the issue of keeping your page updated with the most current information. The pattern allows you to change different parts of your page and have other pieces be updated to show the new content.

## What are the three mechanisms of the observer pattern?
The three methods are subscribe, unsubscribe, and Brodacast. Subscribe grabs the new content and adds it to the array. Unsubscribe filters out specific content. Broadcast will run callback functions.

## Review the code generated form the bcw-templateand reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

With the template, you are able to set up easily manipulated proxy objects via the observer pattern. You can call to private objects and are able to modify them with different content as it is added on the webpage. The template allows us to keep information more private and secure from the user while being able to seamlessly update the user with current information as the observer pattern is used in tandem.