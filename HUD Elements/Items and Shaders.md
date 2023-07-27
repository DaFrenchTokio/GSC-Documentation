# GSC - HUD Elements

In this ReadMe, you can learn Items and Shaders[Pics] Elements in GSC.

### createIcon

It's a way to put an image on an assigned position.

```gsc
self.newIcon = self createIcon( name , height , width ); 
```

- name : Put your shader/icon filename in here, example: "hud_suitcase_bomb"
- height : This is the height of the shader, not the position! put in the size in pixels (not sure though)
- width :  This is the length of the shader, not the position! put in the size in pixels


### Creating a bar or square on your HUD


```gsc
self.newBar = createBar( (R, G, B) , width , height );  // Create Element
self.newBar setShader("white", <width> , <height>);     // Set Shader
self.newBar.alignX = <POINT1>;                          // Horizontal "Point" same use as the text
self.newBar.alignY = <POINT2>;                          // Vertical "Point"
self.newBar.x = <X Number>;                             // Horizontal offset (Number)
self.newBar.y = <y Number>;                             // Vertical offset (Number)
```

#### some others properties for HUD Element Bar

```gsc
self.bar.alpha = 0.50;                    
self.bar.HideWhenInMenu = true;            
self.bar.foreground = false;
```


