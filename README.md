# circle_surface
computes surface area given radius
def circle_surface():
    radius = int(input("What is the radius? "))
    pi = 3.14159
    surface = (radius * radius) * pi
    print("The surface area of a circle with radius", radius, "is", surface)
