A widget that allows the user to select one or more options from a list.
# Inicialize the variable
```python
check_var = IntVar() 
check_button = Checkbutton(root, text="Option", variable=check_var)
check_button.pack()
```

# Arguments
```python
check_var = IntVar()
check_button = Checkbutton(root, text="Option", variable=check_var,
    background='white',       # The background color of the checkbutton
    font=('Arial', 20),       # The font to use for the checkbutton's text
    foreground='black',       # The text color of the checkbutton
    borderwidth=5,            # The width of the 3D border around the checkbutton
    relief='solid'             # The style of the 3D border
)
```

