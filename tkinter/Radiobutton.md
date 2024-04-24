A widget that allows the user to select one option from a list.
# Inicialize the variable
```python
radio_var = StringVar() 
radio_button1 = Radiobutton(root, text="Option 1", variable=radio_var, value="opt1") 
radio_button2 = Radiobutton(root, text="Option 2", variable=radio_var, value="opt2")
radio_button1.pack()
radio_button2.pack()
```

# Arguments
```python
radio_var = StringVar()
radio_button1 = Radiobutton(root,
	text="Option 1",
	variable=radio_var, value="opt1",
	background='white',       # The background color of the radiobutton
	font=('Arial', 20),       # The font to use for the radiobutton's text
	foreground='black',       # The text color of the radiobutton
	borderwidth=5,            # The width of the 3D border around the radiobutton
	relief='solid'             # The style of the 3D border
)
```

