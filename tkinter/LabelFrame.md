A widget that acts as a container for other widgets and has a label.
# Inicialize the variable
```python
label_frame = LabelFrame(root, text="Label Frame") 
label_frame.pack()
```

# Arguments
```python
label_frame = LabelFrame(root, text="Label Frame",
    background='white',       # The background color of the labelframe
    font=('Arial', 20),       # The font to use for the labelframe's text
    foreground='black',       # The text color of the labelframe
    borderwidth=5,            # The width of the 3D border around the labelframe
    relief='solid'             # The style of the 3D border
)
```

