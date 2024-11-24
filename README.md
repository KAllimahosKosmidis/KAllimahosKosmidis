- 👋 Hi, I’m @KAllimahosKosmidis
- Copy this Orfea Malaka
 import tkinter as tk
import random

def show_error():
    # Δημιουργία νέου παραθύρου
    error_window = tk.Toplevel()
    error_window.geometry(f"200x100+{random.randint(0, 1920)}+{random.randint(0, 1080)}")  # Τυχαίες θέσεις
    tk.Label(error_window, text="Error Alkis!", fg="red").pack()

# Ξεκινάει το πρόγραμμα
root = tk.Tk()
root.withdraw()  # Κρύβει το κύριο παράθυρο
while True:
    show_error()
    root.update()  # Ενημερώνει την οθόνη
