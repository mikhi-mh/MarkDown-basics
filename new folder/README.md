# This file uses markdown to create
You can see its raw to learn basics.

# Why
Markdown is a markup language that is easy to use and is commonly used for styling text, such as for web documentation and website creation. Its styling options include commonly used formats, such as italicizing, bolding, and list-making.

Markdown can be seen throughout GitHub, from issues and pull requests to comments and static web page hosting via GitHub Pages. Additionally, tools like AsciiDoctor and Jekyll can take markdown files and generate websites that can be hosted for free on GitHub Pages.

# title 1
## title 2
### title 3
#### title 4
##### title 5
###### title 6
####### title 7.....see this is not working (heading only upto level 6)
--------
Dont put h1 uner h2

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
----------------------------------------------------------------------------

SEE BOLD ITALICS AND STRIKETHROUGH :
**Bold**
_Italics__
~~StrikeThrough~~


Now, list i.e. to-do list like list :

* [ ] item 1 (is not done)
* [x] item 2 (is done)
* [ ] item 3 (its not done)
  * [x] item 3.1 (done)
  * [ ] item 3.2 (not done)  

its over now,

-------------------------------------------

1. Item 1
2. Item 2
3. Item 3
4. Item 4
    1. Item 1 (this is subitem)


-------------------------------------------
# Tables

rows ---> 0, 1,  and columns--->a, b ,c
| Column 0 | Column 1 | Column 2 |
| :-- | :-- | :-- |
| Row 0a | Row 0b | Row 0c |
| Row 1a | Row 1b | Row 1c |


-------------------------------------------


# Links

This is like : [TextToDisplay](github.com)



-------------------------------------------

# Code

this is inline `code`
how we write `command`

now we will write hello in java
```java
public class Main{
    public static void main(String[] args){
        System.out.println("hello !");
    }
}
```

this is hello code for in java

-------------------------------------------



# Quotes
this is example of quote:
> I am here to quote myself

I am normal text talking about above line

> this is another Qoute


-------------------------------------------
###### this is heading 6
> this is quote


-------------------------------------------

# HTML and markdown

**HTML
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

**MARKDOWN**
# titles 1
## titles 2
### titles 3
#### titles 4
##### titles 5
###### titles 6

HTML -> This is <b>Bold</b>
MarkDown -> This is **Bold** or __Bold__

HTML -> This is <i>Italic</i>
MarkDown -> This is _italic_ or *italic* 

HTML -> This is <s>strikeThrough</s>
MarkDown -> This is ~~StrikeThrough~~ or ~this~ 


MarkDown -> This is [Link](github.com)

HTML -> This is <a href = "google.com"> Link </a>


[Link for h1 in this file](#title-1)
click above link to go to H1
-------------------------------------------

[Link fot titles5](#titles-6)


-------------------------------------------

Now # images

MarkDown ![this is image title](https://github.com/techsonu8.png) 

MarkDown
![Title of image](http://mydomain.com/myimage.png)

HTML
<img src = "http://mydomain.com/myimage.png" alt = "Title of image">



-------------------------------------------

# Unorderd List
## Style 1

- item 1
- item 2
- item 3

you can nest it

- item 1
- item 2
- item 3.0
    - item 3.1 (4 spaces required)
    - item 3.2
    - item 3.3
- item 4

## Style 2 ..here we use * instead of -
#### use of - (hyphen is recommended) for lists

* item1
* item2
* item3
    * item 3.0
    * item 3.1
    * item 3.2
 * item 3.4 (no 4 space ---didnt work)
* item 4.0 

HTML  unorederd
<ul>
 <li>item 1</li>
 <li>item 2</li>
 <li>item 3</li>
</ul>


-------------------------------------------

# Ordered List
1. item1
2. item 2
3. item3

or
1. item 1
2. item 2
3. item3
    1. this is subitem of 3 
4. item4

or 

1. item 1
1. item 2
1. item 3

Now  

In **HTML**
<ol>
 <li>item</li>
 <li>item</li>
</ol>



# CheckList
to-do like list

- [ ] item 1
- [ ] item 2
- [x] item 3
- [X] item 4

checeked nested list
- [ ] item 1
    - [ ] item 1.0
    - [ ] item 1.1
    - [x] item 1.2
    - [X] item 1.3
- [ ] item 2
- [ ] item 3


---

# TABLES
3 columns  
| Column 1 | Column 2 | Column 3 |  
only this will not work  

| Column 1 | Column 2 | Column 3 |  
| :--- | :--- | :--- |  

| Heading 1 | Heading 2 | Heading 3 |  
| :--- | :--- | :--- |  


|  |  |  |  
| :--- | :--- | :--- |  

this will be blank
  
| Column 1 | Column 2 | Column 3 |
| :--- | :--- | :--- |
| Row 1, Column 1 | Row 1, Column 2 | Row 1, Column 3 |
| Row 2, Column 1 | Row 2, Column 2 | Row 2, Column 3 |
| Row 3, Column 1 | Row 3, Column 2 | Row 3, Column 3 |  

allignment:  
- ":---" will be left aligned
- ":---:" will be centred aligned
- "---:" will be right aligned   


| LEFT | CENTER | RIGHT |
| :--- | :---: | ---: |
| this is left aligend | this is centre aligend | this is right aligned |
| *LEFT* u can use _italic_ | **CENTER** you can use __bold__ | RIGHT you can use ~~StrikeThrough~~ |    

but u cant use list inside the table in MarkDown , I think
So u must go with html for that 



HTML would be   
<table role="table">
            <thead>
                <tr>
                    <th align="left">Column 1</th>
                    <th align="left">Column 2</th>
                    <th align="left">Column 3</th>
                </tr>
            </thead>
        <tbody>
            <tr>
                <td align="left">Row 1, Column 1</td>
                <td align="left">Row 1, Column 2</td>
                <td align="left">Row 1, Column 3</td>
            </tr>
            <tr>
                <td align="left">Row 2, Column 1</td>
                <td align="left">Row 2, Column 2</td>
                <td align="left">Row 2, Column 3</td>
            </tr>
            <tr>
                <td align="left">Row 3, Column 1</td>
                <td align="left">Row 3, Column 2</td>
                <td align="left">Row 3, Column 3</td>
            </tr>
            </tbody>
        </table>   
 

---   
---  

# Code
### the most awaiting sections
this is a variable declaration  
this is inline `int age = 0;`  

u can write commands also  
`git checkout -b v2.0`  
we can do code blocks also  
```
int age = 18
if(age>=18)
    printf("you are eligible to vote");
else
    print("You are minor ...u cant vote right now");
 ```     
This is code block 
#### But we can do more specific to a language like this

###### this is example of hello world in C++  

```cpp
#include <iostream>
using namespace std;
int main()
{
    cout<<"Hello, World !";
    //print statement
    return 0;
}
```  
this is cpp code  

###### this is example of hello world in Python  
```py
str = "Hello, World !"
print(str)
```  
this is in Python  


we can use diff to seethe difference 
> see follwoing without diff  

Before  
```java
static int numberssss = 10;
int age = 18;
```  

After  
```java
static int number = 10;
int age = 18;
```  

> see following using diff  

```diff
- static int numberssss = 10;
+ static int number = 10;
int age = 18;
```  
we can see the difference  
> The sign + in diff will be in a GREEN colour indicating something has added  
> The sign - in diff will be in a RED colour indicating something has removed  
> Other normal line will be a normal code  


-----
# Quotes

this is normal line   
> THis is quoted line ...  

this is line break   
> This is quote 2  
> This is quote 3 ---> u can use it fo rlike Q&A and lot more things 

this is normal  
> this is quote  

this is normal
> this is quote

there should be a line break to get back to normal text   

---   

# Comments   
this is the line to be shown
if u want to add comment u can use comment tag in **HTML** \<!-- -->
<!--this is comment and this will not be shown in final view-->  
this will be shown in final--      


# Collapsable Content  
we can mminimize here...hide and expand  
we are using two html tags *summary* and *details*   
  
<details>
 <summary>Click here to expand...</summary>
 this is more descrptive way  
 this is also
 </details>
 
this is normal text to read from...
now we will see more example
<details>
 <summary>this line will always visible</summary>
 this is line 1 in description   
 
 this is also second line
 </details>   
 
 
 now one more   
 <details>
  <summary>Click to expand!</summary>  
 
   ## More great tips!  
   - item 1  
   - item 2  
   - please try to do this on your own ...u will be having a fun
   ## please do a try
</details>   

> there should be a line break inside summary sections  
> there should be one and only one blank space   


------   

# HTML Tables--- Lists in Tables  

u have to use html tags to use this feature   


<table role="table">
            <thead>
                <tr>
                    <th align="left">Column 1</th>
                    <th align="left">Column 2</th>
                    <th align="left">Column 3</th>
                </tr>
            </thead>
        <tbody>
            <tr>
                <td align="left">
                    <ul>
                        <li>Item 1</li>
                        <li>Item 2</li>
                        <li>Item 3</li>
                    </ul>
                </td>
                <td align="left">Row 1, Column 2</td>
                <td align="left">Row 1, Column 3</td>
            </tr>
            <tr>
                <td align="left">Row 2, Column 1</td>
                <td align="left">Row 2, Column 2</td>
                <td align="left">Row 2, Column 3</td>
            </tr>
            <tr>
                <td align="left">Row 3, Column 1</td>
                <td align="left">Row 3, Column 2</td>
                <td align="left">Row 3, Column 3</td>
            </tr>
            </tbody>
        </table>


###### Not all html tags are allowed, due to security concerns. The main tags you would probably use will work.    


--------

# Misc  

we can mix and match   
keep in mind, the stack structure   
match tags accordingly u are go to go like :   
- item 1
- item 2 this is **Bold and *italic***  
- item 3 this is ~~not neede any more~~
- # this is heading  
- we can ```inline code here``` as well  
- > u can mix and match and just play arround   

# You are good to go for ***PRACTICE***
