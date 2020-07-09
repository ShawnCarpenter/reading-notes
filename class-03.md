# Lists #

Lists are useful for organizing information.

There are three types of lists used in html: 
 1. Ordered lists `<ol>`
 - Unordered lists `<ul>`
 
 <dl><dt>Definition lists</dt> 
 <dd>&ltdl&gt</dd></dl>


 - You can also
    - indent lists
        1. to organize
        1. information




# Little boxes, little boxes made of code. #

All elements on a web page are contained in boxes. 

We can control where and how those boxes are displayed using CSS or JavaScript (by adding CSS properties to them, so it's really CSS all the way down)

# Decisions and loops #

Setting properties with CSS is fine for static pages but to make them sing and dance we need to use JavaScript.

We use Switch statements to choose between  multiple possible options.

```
switch (computerNumber) {
        case 1 :
            return 'Rock';
        case 2 :
            return 'Paper';
        case 3 :
            return 'Scissors';
    }
```
would return a different word based on the value of a number.

We use loops to repeat actions. 
We can use for loops: 
```
for (let i=1; i<= 10; i++ ) {
    console.log(i);
}

```
would log the numbers from one to 10.

There are also while loops and do while loops that run while a condition is true.

A while loop will check the condition before running, a do while loop will always run at least once.
