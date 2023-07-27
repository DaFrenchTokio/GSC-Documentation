# GSC - HUD Elements

In this ReadMe, you can learn how to make a Text Element [Method 1] in GSC.

## Functions

### CreateFontString

This is the most used way to create some text on screen

```gsc
self.TextName = createFontString( font , fontscale );
```

- font : This is the expression that refers to a property used in the context of programming and text layout. It is best to put the font in uppercase.
- fontscale : This is the expression that refers to a property used that allows the font size to be dynamically adjusted according to certain parameters.

### setPoint

It's a way to choose position of text with coordinates

```gsc
self.TextName = setPoint( p1 , p2 , p3, p4 );
```

- p1 : This is the Horizontal "Point"
- p2 : This is the Vertical "Point"
- p3 : This can either be a Number (X) or a "Point". (Horizontal)
- p4 : This can either be a Number (Y) or a "Point". (Vertical)

- "Point" : This could be used to indicate a specific location in the interface or on the game screen.

- Horizontal:
LEFT
RIGHT
CENTER

- Vertical:
BOTTOM
TOP
CENTER

#### There are still some but they are not recommended to use.

### setText

It's a way to put text on your element

```gsc
self.TextName = setText( text );
```