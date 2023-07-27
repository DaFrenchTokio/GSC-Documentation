# GSC - Loops

In this ReadMe, you can learn how to make loops in GSC.

## My Source

You can look at my source for more information and if my documentation is incorrect.

[Click Here](https://plutonium.pw/fr/docs/modding/gsc/how-to-gsc/)


## How to create an for-loop?

```gsc
for (initialization; condition; increment)
{
    // Code to execute at each iteration
}
```

### or

```gsc
initialization = 0;
while ( initialization < condition )
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

# Examples

You can learn all examples of each type of loop.

## Examples for-loop

```gsc
for (int i = 0; i < 5; i++) {
    iprintln(i + 1);
}
```

```gsc
i = 0;
while ( i < 5 )
{
    iprintln(i+1);
    i++;
}
```

it will print 1 to 5

## Example foreach-loop

```gsc
foreach ( player in level.players )
{
    iprintln( player.score )
}
```

it will print for each player their score.

## Examples infinite loop

```gsc
for(;;)
{
    iprintln("GSC On Top")
}
```

```gsc
while ( true )
{
    iprintln("GSC On Top")
}
```

It will print "GSC On Top" forever

