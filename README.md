**PYTHON Tkinter.simpledialog-GUI-Input-Output**

import tkinter as tk 
from tkinter import messagebox
from tkinter import simpledialog

user_input= simpledialog.askstring("input", "name")
print("hello ", user_input) 
messagebox.showinfo("output",user_input)
