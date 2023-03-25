## Buttons

- **BtnEnable(pin, enable)** - sets up a button to be used <br>
**pin:** pin number, 'a', or 'b' <br>
**enable:** 1 = enable, 0 = disabled  <br>

- **BtnDown(pin)** Returns a value when button is pressed<br>
**pin:** pin number, 'a', or 'b' <br>
**Returns:** 1 if button was pressed and continues to return 1 until the button is released

> [!NOTE] 
> **'a'** is ASCII a or 97, **'b'** is ASCII b or 98

> [!TIP] 
> Will always return zero if not enabled

```basic
BtnEnable('a',1)
@Loop
x=BtnDown('a')
if x=1
    Println("Button A")
end
goto Loop
```
---