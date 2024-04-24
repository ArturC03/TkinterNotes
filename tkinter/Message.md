A widget that displays multiple lines of text.
# Inicialize the variable
```python
message = Message(root, text="Hello, World!") 
message.pack()
```

# Arguments
```python
message = Message(root, text="Hello, World!",
    background='white',       # The background color of the message
    font=('Arial', 20),       # The font to use for the message's text
    foreground='black',       # The text color of the message
    borderwidth=5,            # The width of the 3D border around the message
    relief='solid'             # The style of the 3D border
)
```

