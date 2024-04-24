A widget that displays a list of options when clicked.
# Inicialize the variable
```python
menu_button = Menubutton(root, text="Options", relief="raised") 
menu = Menu(menu_button, tearoff=0)
menu_button["menu"] = menu 
menu.add_command(label="Option 1", command=callback_function) menu.add_command(label="Option 2", command=callback_function) 
menu_button.pack()
```

# Arguments
```python
menu_button = Menubutton(root, text="Options", relief="raised",
    background='white',       # The background color of the menubutton
    font=('Arial', 20),       # The font to use for the menubutton's text
    foreground='black',       # The text color of the menubutton
    borderwidth=5,            # The width of the 3D border around the menubutton
    relief='solid'             # The style of the 3D border
)
```

