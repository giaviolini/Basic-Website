# Basic-Website
This is a basic website with several pages. [Visit the site here.](https://giaviolini.github.io/Basic-Website/)  
Assignment 2 of 10

## What I learned/practiced:
### Lists
I learned that Navigations use list elements to travel between pages. I also learned the differences between ordered and unordered lists. 
  ```<li> ... </li>``` is the syntax used for any list element. 
  It is nested inside an order or unordered list.  
                                                    ex. ```<ul>```  
                                                          ```<li>... </li>```  
                                                        ``` </ul>```   
An ordered list will display numbers without any CSS coding, while unordered lists will display bullet points. Both can be used to make a navigation header, however, it is more common to use an unorder listed. The navigation header will also use ```<nav> ... </nav>``` with the list element nested inside. 

### Pages
This was also the first website I made that used multiple pages. This was a challenging process for me, I couldn't get the different pages to link properly, though through many trials and errors (and W3schools) I was able to make it work and fully understand it.  
To link pages in a list you need the following things;   
  - names of your pages
  - where they exist in your root folder -- creating a folder of your pages is standard practice, and should be followed.
     
To link pages you start with a ```<li>``` element. In between your beginning and end selectors, you will need an attribute selector ```<a>```  
To build the link inside the attribute tag you will also need the href tag which will house the link to your page.  
ex. ```<a href="../pages/gia.html">Me</a>``` *the 'Me' in between the tags will be the title of your page.  
The ```...``` are also very important because they show how many folders the computer will need to search through to find the page -- Because my pages folder is set up right in the root folder it only needs one. BUT, if there are multiple folders that the computer must go through such as pages --> page one --> pageone.html it will need two ```...``` so it can find it.   \
ex. ```<a href="../../pages/pages1/gia.html">Me</a>```
