# Turtle
Turtle color, pen size and window color
echo "# Turtle" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/ambiemae/Turtle.git
git push -u origin master


import turtle

windowcolor = input("window color: ")
tesscolor = input("tess color: ")
tesspensize = input("tess pensize: ")

# Set up window

window = turtle.Screen()
window.bgcolor(windowcolor)

# Set up turtle

tess = turtle.Turtle()
tess.color(tesscolor)
tess.pensize(tesspensize)

# Draw things

tess.forward(50)
tess.left(120)
tess.forward(50)
