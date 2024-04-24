A widget that displays the progress of a task.
# Inicialize the variable
```python
progressbar = Progressbar(root, length=200) 
progressbar.pack()
```

# Arguments
```python
progressbar = Progressbar(root, length=200,
    background='white',       # The background color of the progressbar
    font=('Arial', 20),       # The font to use for the progressbar's text
    foreground='black',       # The text color of the progressbar
    borderwidth=5,            # The width of the 3D border around the progressbar
    relief='solid'             # The style of the 3D border
)
```

