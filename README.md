# turtle-animation
from turtle import*
color("darkred","aqua")
bgcolor("black")
speed(10)
pensize(2)
begin_fill()
while True:
    forward(300)
    lt(170)
    if abs(pos())<5:
        break
end_fill()
done()
