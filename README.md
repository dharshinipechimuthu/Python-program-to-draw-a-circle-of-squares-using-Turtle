# Python-program-to-draw-a-circle-of-squares-using-Turtle
import turtle
x=turtle.Turtle()
def square(angle):
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle+10)
for i in range(36):
    square(90)


OUTPUT:

<img width="389" height="309" alt="image" src="https://github.com/user-attachments/assets/b4ce5a15-b4f4-4509-a950-f1b4b2b799e1" />
