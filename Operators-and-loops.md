# Comparison Operators
## Evaluating Conditions
A situation can be *evaluated* b comparing one value of the script to what you expect it might be.

* The result will be **Boolean** (true or false)
   * == is Equal
   * != is **Not** Equal

For Example:
3==3 is True.
3!=3 iss false.

*  === is strict Equal
* !== is strict **Not** Equal
   * '3' === 3 false.
   * '3' !== 3 true.
 
 * (>) Greater than
 * (<) Less than

    * 4>3 true.
    * 4>5 false.  
    * 4<3 false.
    * 4<5 true.

* (<=) less than or equal
* (>=) greater than or equal

   * 4>=3 true.
   * 4>=4 true.
   * 3>=4 false.
   * 4<=3 false.

# Logical Operator
## Comparison operators

it returns single value of T or F

## Logical operators
Allow you to compare the result of more than one comparison operator.

* for Example:

(5<2)&&(2>=3)
it is False and false equal false.

&&  logical **AND**
is tests more than one condition.

|| logical **OR**
is tests AT LEAST one condition.

! logical **NOT**

-----
# **LOOPS**
is a check condition. if it returns true then a code block will run & will repeat it untill it is *false* to break.

## **FOR**
if you need to run a code for a specific number of times you will use the **FOR** loop.

Example:
var sum=0;
for(var i=0; i<4; i++)
{
    sum=sum+i
}

## **WHILE**
if you dont know how many times the code should run, then use the **WHILE** loop.

Example:
var i=0,sum=0;
while(i>0)
{
    i--;
    sum=sum+i;
}

## **DO WHILE**

the do while loop is very similar to the while loop but it has oe key difference. it will run the statement *AT LEAST* once, even if the result is Fasle.

Example:
var i=0,sum=0;
while(i>0)
do{
    i++;
} 
else {
    sum=sum+i;
}

A loop **COUNTERS**
A for loop uses counter as a condition.

* INITIALIZER
var i=0;
* CONDITION 
i<10;
* UPDATE
i++;
