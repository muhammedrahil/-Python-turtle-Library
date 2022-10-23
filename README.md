# Python-turtle-Library
 Python turtle Library - Draw a Tree


turtle is a pre-installed Python library that enables users to create pictures and shapes by providing them with a virtual canvas. The onscreen pen that you use for drawing is called the turtle and this is what gives the library its name 


```
import turtle as t

t.speed(0)
t.pensize(2)
t.left(90)
t.backward(100)
t.color('black')

def draw(l):
  if(l<10):
    return
  else:
    t.forward(l)
    t.color('red')
    t.circle(2)
    t.color('black')
    t.left(30)
    draw(3*l/4)
    t.right(60)
    draw(3*l/4)
    t.left(30)
    t.backward(l)

draw(100)
```



https://user-images.githubusercontent.com/89409310/197371100-e0375d74-15eb-4fc6-a413-d943ec6cc69a.mp4

