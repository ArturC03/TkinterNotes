A widget that displays data in a tree-like structure.
# Inicialize the variable
```python
tree = ttk.Treeview(root) tree["columns"] = ("one", "two") 
tree.column("one", width=100) 
tree.column("two", width=100) 
tree.heading("one", text="Column One") 
tree.heading("two", text="Column Two") 
tree.insert("", "end", values=("Value One", "Value Two")) 
tree.pack()
```

# Arguments
```python
tree = ttk.Treeview(root)
tree["columns"] = ("one", "two")
tree.column("one", width=100)
tree.column("two", width=100)
tree.heading("one", text="Column One")
tree.heading("two", text="Column Two")
tree.insert("", "end", values=("Value One", "Value Two"))
tree.tag_configure('oddrow', background='white')
tree.tag_configure('evenrow', background='lightgray')
tree.bind('<Configure>',
    lambda e: tree.itemconfigure(tree.get_children()[0], tags=('evenrow',)))
tree.bind('<Configure>',
    lambda e: tree.itemconfigure(tree.get_children()[1], tags=('oddrow',)))
```

