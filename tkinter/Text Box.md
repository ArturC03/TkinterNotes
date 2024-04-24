A widget that allows the user to enter and edit text.
# Inicialize the variable
```python
text_box = Text(root) 
text_box.pack()
```

# Arguments
```python
text_box = Text(root,
    background='white',       # The background color of the text box
    font=('Arial', 20),       # The font to use for the text box's text
    foreground='black',       # The text color of the text box
    borderwidth=5,            # The width of the 3D border around the text box
    relief='solid'             # The style of the 3D border
)
```

