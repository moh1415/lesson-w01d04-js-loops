

# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

 for(let i =0;i<10;i++)
    {
        console.log(i);
    }

<br>

## Print every number from 10 to 0

  for(let i =10;i>=0;i =i-1)
    {
        console.log(i);
    }


<br>

## Print every number from 4 to -16

 for(let i =4;i>=-16;i =i-1)
    {
        console.log(i);
    } 

<br>

## Print every fifth number from 8 to 41

for(let i =8;i<41;i =i+5)
    {
        console.log(i);
    }
<br>

# Exercises: JavaScript loops with array:

Paste your answers into this file.



1. Change all **odd** numbers to be those numbers multiplied by two:
```js
const numbers = [4, 9, 7, 2, 1, 8];

 const numbers = [4, 9, 7, 2, 1, 8];
    for(let i=0;i<numbers.length;i=i+1)
    {
        
        if(numbers[i]%2==0)
    {
        console.log(numbers[i]);
    }
    else {
        console.log(numbers[i]*2);
    }
      
    }

numbers; // => [4, 18, 14, 2, 2, 8]
```

2.  Create an array to hold your favorite colors.  For each choice, log to the screen a string like: `My #1 choice is blue.`
const favoriteColor =["red","black","blue"];
   console.log("My #1 choice is "+favoriteColor[2]);

3.  Create an array of ages.  Loop through and log only the ages that are over 21.

 const ages=[10,20,30,40];
   for(let i =0;i<ages.length;i++)
   {
       if(ages[i]>21)
       {

        console.log("the ages that over 21 is "+ages[i]);
       }
   }

1. Create an array to hold your top five choices of something (music, books, movies, whatever).

    - For each choice, log to the screen a string like: "My #1 choice is blue."
    - **Bonus:** Change it to log "My 1st choice, "My 2nd choice", "My 3rd choice", picking the right suffix for the number based on what it is.
    const topChoices = ["test1","PHP","escape","apple","white"];
    for(let i=0;i<=topChoices.length-1;i++)
    {
      console.log("My #"+i+" choice is blue "+topChoices[i]);
    }
    


## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


for(let i =1;i<=100;i++){
    if(i % 3 ==0 )
    {
        console.log("Fizz "+i);
    }
     if(i % 5 ==0)
    {
        console.log("Buzz "+i);
    }if(i % 3 ==0  && i % 5 ==0)
    {
        console.log("Fizzbuzz "+i);
    }
}

<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

for(let i =0;i<=20;i++)
{
    if(i % 2 !=0)
    {
        console.log(i+" is odd")
    }
    else {
        console.log(i+" is even")
    }
}

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


for(let i=1;i<=10;i++)
{
    for(let j=0;j<=10;j++)
    {
        console.log(i+" * "+j+" = "+i*j)
    }
}

<br>

## The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

for(let i =60;i<=100;i++)
{
    if(i<70)
    {
        console.log("got a D "+i);
    }
    else if(i<80)
    {
        console.log("got a C "+i);
    }
    else if(i<90)
    {
        console.log("got a B "+i);
    } 
    else{
        console.log("got a A "+i);
    }
}
