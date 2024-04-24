A widget that allows the user to select a value from a range by dragging a slider.
# Inicialize the variable
```python
scale = Scale(root, from_=0, to=100) 
scale.pack()
```

# Arguments
```python
scale = Scale(root, from_=0, to=100,
    background='white',       # The background color of the scale
    font=('Arial', 20),       # The font to use for the scale's text
    foreground='black',       # The text color of the scale
    borderwidth=5,            # The width of the 3D border around the scale
    relief='solid'             # The style of the 3D border
)
```

