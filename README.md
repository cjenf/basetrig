# basetrig
### Do some operations using trigonometric functions
```py
pip install basetrig
```
> [!NOTE]  
> **This module only supports very basic calculations .**

## It can be found $sin𝜃$ $cos𝜃$ $tan𝜃$ ...
```py
from basetrig import trid

degree=30
t=trid()
print(t.sin𝜃(angle=degree))
```
<details>
  <summary>example output:</summary>
  
```py
0.5
```
</details>

## Apply to geometric triangles
```py
from basetrig import geometry

g=geometry(
      a=10,
      b=10,
      𝜃c=30
  )
print(g.area())
```
<details>
  <summary>example output:</summary>

```py
25
```
</details>

> [!NOTE]  
> **You can also ask for a side length**.<br>
