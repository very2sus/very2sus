import turtle


def draw_square(shape):
  if shape == "square":
    for i in range(4):
      turtle.forward(100)
      turtle.left(90)
  elif shape == "triangle":
    for i in range(3):
      turtle.forward(100)
      turtle.left(120)
  elif shape == "circle":
    turtle.circle(50)
  else:
    print("Invalid shape")
shape = input("Enter a shape (square, triangle, or circle):")
draw_square(shape)
