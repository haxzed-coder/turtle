# turtle
Moroccan flag 
from turtle import *

setup(720, 1080)
shape("turtle")
speed(5)

penup()
goto(-300, 150)
pendown()
color("#FF0000")
begin_fill()
for i in range(2):
      forward(600)
      right(90)
      forward(400)
      right(90)
end_fill()

width(13)
penup()
goto(-150, 0)
pendown()
color("green")
for i in range(5):
      forward(300)
      right(144)
      
penup()
goto(-210,  200)
color("black")
write("KINGDOM  OF MOROCCO",
          font=("Arial", 10,
                        "normal"))
penup()
goto(800, 0)
done()
