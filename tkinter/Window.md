The window or frame that serves as the base for the application. It is the main container for all other widgets.
# Inicialize the variable
```python
root = Tk() # Create the window 
root.mainloop() # Open the window
```

# Arguments
```python
root = Tk(
    className='MyTkWindow',  # The name of the widget class
    background='red',         # The background color of the window
    borderwidth=5,            # The width of the 3D border around the window
    class_='CustomTk',        # The class name for the window
    colormap='new_colormap',  # The colormap to use for the window
    cursor='dot',             # The cursor to use for the window
    displayof='my_display',   # The display to use for the window
    font=('Arial', 20),       # The font to use for the window's text
    height=500,               # The height of the window
    highlightbackground='blue',# The color to use for the window's highlight ring
    highlightcolor='green',   # The color to use for the window's highlight ring
    highlightthickness=3,     # The thickness of the window's highlight ring
    takefocus=False,          # If True, the window will take the focus when it is realized
    width=800,                # The width of the window
    x=100,                    # The x coordinate of the window's top left corner
    y=100,                    # The y coordinate of the window's top left corner
)

root.title("My Window") # Set the title of the window
```

