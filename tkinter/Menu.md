A widget that contains a list of commands.
# Inicialize the variable
```python
menu = Menu(root) 
root.config(menu=menu)
file_menu = Menu(menu, tearoff=0)
menu.add_cascade(label="File", menu=file_menu) file_menu.add_command(label="Exit", command=root.quit)
```

# Arguments
```python
menu = Menu(root,
    background='white',       # The background color of the menu
    font=('Arial', 20),       # The font to use for the menu's text
    foreground='black',       # The text color of the menu
    borderwidth=5,            # The width of the 3D border around the menu
    relief='solid'             # The style of the 3D border
)
```

	