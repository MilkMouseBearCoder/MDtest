``` rust
use '*' (
  "Raylib-bear",
  "Types"
)

let windowWidth: i32 = 840
let windowHeight: i32 = 400
  
InitWindow(windowWidth, windowHeight, "Window!")
while !WindowShouldClose()
{
  BeginDrawing()
    ClearBackground(WHITE)
  EndDrawing()
}
CloseWindow()
```
