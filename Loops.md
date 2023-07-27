# GSC - Loops

In this ReadMe, you can learn how to make loops in GSC.

## My Source

[Click Here](https://plutonium.pw/fr/docs/modding/loading-mods/)

## How to create an for-loop?

```gsc
for (initialization; condition; increment)
{
    // Code to execute at each iteration
}
```
- initialization : This is the expression that initializes the control variable.
- condition : This is the expression that specifies the condition to continue the loop.
- increment : This is the expression that increments or decrements the control variable on each iteration.

## How to create an foreach-loop?

```gsc
foreach ( element in table )
{
    // Code to execute for each element of the table
}
```

- element : It is a variable that represents each element of the table at each iteration of the loop. On each iteration, element will take the value of a different element from the table.
- table : This is the container (e.g. array, vector, list, etc.) to loop through using the "for each" loop. At each iteration of the loop, the variable 'element' will take the value of an element from the table.

## How to create an infinite loop?

```gsc
for(;;)
{
    // Instructions to be executed in a loop
}
```

### or

```gsc
while ( true )
{
    // Instructions to be executed in a loop
}
```