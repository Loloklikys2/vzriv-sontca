# vzriv-sontca
x1 = 0
x2 = 0
def setup():
    size(800,600)

def draw():
    global x1
    global x2
    x1 = x1 + 2
    x2 = x2 + 2
    ellipse(10,10,x1,x2)
    fill(229,187,95)
