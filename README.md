commandline-logo
================

Run python's LOGO (Turtle Graphics) implementation from the command line.
Ultra trivial starter code. Running Turtle graphics commands launches a second graphic window in the turtle automatically.

Add to bashrc or bash_profile the following line to jump to interpretative python with turtle imported.

    alias LOGO="python -i path/to/setupTurtle.py"

It will then dump you into the python interpreter and you can run commands like:
    fd(50)
    lt(50)
    rt(50)
    lt(50)
    setposition()
    setx()
    sety()
    home()
    pd()
    pu()
    pensize()
    clear()

Quit with `exit()`.

Much more on python turtle library [reference](https://docs.python.org/2/library/turtle.html) page.

