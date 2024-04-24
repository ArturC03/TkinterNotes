A widget that allows the user to select a value from a range by clicking up and down buttons.
# Inicialize the variable
```python
spinbox = Spinbox(root, from_=0, to=100) 
spinbox.pack()
```

# Arguments
```python
spinbox = Spinbox(root, from_=0, to=100,
    background='white',       # The background color of the spinbox
    font=('Arial', 20),       # The font to use for the spinbox's text
    foreground='black',       # The text color of the spinbox
    borderwidth=5,            # The width of the 3D border around the spinbox
    relief='solid'             # The style of the 3D border
)
```

