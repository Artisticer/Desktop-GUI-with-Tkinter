# Desktop-GUI-with-Tkinter
Create a simple desktop graphical user interface (GUI) using Tkinter.
import tkinter as tk

def on_button_click():
    label.config(text="Button Clicked!")

# Create the main window
window = tk.Tk()
window.title("Tkinter GUI")

# Create a button and label
button = tk.Button(window, text="Click Me!", command=on_button_click)
label = tk.Label(window, text="Hello, Tkinter!")

# Pack widgets and start the main loop
button.pack(pady=10)
label.pack(pady=10)
window.mainloop()
