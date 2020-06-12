# Week Two Review: Media Queries and breakpoints
--------------------
# TOTAL POINTS 10

Question 1
Consider the following CSS rules:

```
div{
   width: 80%;
}

@media all and (min-width: 500px){
    div{
       width: 25%;
    }
}
```

What is the width of any div elements on a 350px screen?



- [x] 80%

----------------------------------------

Question 2
Consider the following CSS rules:

```
div{
   width: 80%;
}

@media all and (min-width: 500px){
    div{
       width: 25%;
    }
}
```

What is the width of any div elements on a 750px screen?




- [x] 25%

-------------------------------

Question 3
Consider the following CSS rules:

```
@media all and (min-width: 500px){
    div{
       width: 25%;
    }
}

div{   
   width: 80%;
}
```

What is the width of any div elements on a 750px screen?



The div won't display since media queries must go at the bottom of the screen.


- [x] 80%

---------------------------------------------------

Question 4
Consider the following CSS rule:

```
div{
    width: 80%;
}

@media print {
    div{
       width: 25%;
    }
}
```

Which of the following is a true statement?


- [x] The div elements will have a width of 25% only when the page is printed

--------------------------------------------

Question 5
Which of the following code segments will keep people from being able to zoom in or out on your content?

```
<meta name = ‘viewport’ content=‘width=device-width, initial-scale=1, maximum-scale = 1’>
```
--------------------------------------

Question 6
Breakpoints often correspond with common screen sizes for phones, tablets, and laptops.



- [x] True

----------------------------

Question 7
Wireframes should...





- [x] specify the layout and content of your pages

--------------------------------------

Question 8
A key component of your wireframes should test



- [x] interaction

--------------------------------------

Question 9
Give an example screen width size for a mobile phone using pixels. (Just provide a number, and not the px!!!)


- [x] 500

-------------------------------------

Question 10
Which of the following is a deprecated media type -- meaning they are omitted in later versions. (You will need to search for this online it is not in the notes. But a lot of what you do with web design will require a little searching!)



- [x] braille


-----------------------------------------------

