A widget that allows the user to select an option from a drop-down list.
# Inicialize the variable
```python
options = ["Option 1", "Option 2", "Option 3"] 
variable = StringVar(root)
variable.set(options[0])
option_menu = OptionMenu(root, variable, *options)
option_menu.pack()
```

# Arguments
```python
options = ["Option 1", "Option 2", "Option 3"]
variable = StringVar(root)
variable.set(options[0])
option_menu = OptionMenu(root, variable, *options,
    background='white',       # The background color of the optionmenu
    font=('Arial', 20),       # The font to use for the optionmenu's text
    foreground='black',       # The text color of the optionmenu
    borderwidth=5,            # The width of the 3D border around the optionmenu
    relief='solid'             # The style of the 3D border
)
```

