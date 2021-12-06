# unschool-python-project
from turtle import *
from random import randint 
speed(0)
bgcolor('black')
i = 1 
while i < 400:
r = randint(0,255) 
g = randint(0,255)
b = randint(0,255) 
colormode(255) 
pencolor(r,g,b)
fd(50 + i) 
rt(90.911) 
i = i+1 
exitonclick()
