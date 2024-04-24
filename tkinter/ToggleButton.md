A widget that acts like a check button but looks like a button.
# Inicialize the variable
```python
toggle_button = ToggleButton(root, text="Toggle Button") 
toggle_button.pack()
```

# Arguments
```python
toggle_button = ToggleButton(root, text="Toggle Button",
    background='white',       # The background color of the togglebutton
    font=('Arial', 20),       # The font to use for the togglebutton's text
    foreground='black',       # The text color of the togglebutton
    borderwidth=5,            # The width of the 3D border around the togglebutton
    relief='solid'             # The style of the 3D border
)
```

