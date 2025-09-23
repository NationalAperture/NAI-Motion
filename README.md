# Desktop & Tablet GUI Applications

This repository contains two graphical user interface (GUI) applications designed for use with National Aperture’s motion-control hardware. Both GUIs are built using **Python** and **PySide6/Qt**, with layouts created in **Qt Creator**.  

The repository includes two separate implementations:
- **Desktop** – optimized for full-sized displays with extended features and layout.
- **Tablet** – optimized for touchscreen/tablet use with a simplified interface.

---

## 📂 Repository Structure


Each folder contains the corresponding Python source files and `.ui` files used to generate the interface.

---

## 🚀 Features

- Cross-platform GUI built with Qt (PySide6).  
- Separate desktop and tablet interfaces tailored to different use-cases.  
- Designed for use with motion-control systems.  
- Modular codebase that can be extended and customized.  

---

## 🔧 Requirements

- **Python 3.9+**  
- **PySide6** (Qt for Python)  
- **Other dependencies**: see `requirements.txt`  

Install dependencies with:

```bash
pip install -r requirements.txt
```

---

▶️ Running the Applications
Desktop GUI

```bash
cd Desktop
python main.py
```

Tablet GUI
```bash
cd Tablet
python main.py
```

---

✏️ Editing the GUIs

The .ui files are included in both the Desktop and Tablet folders.
These can be opened and edited directly using Qt Creator:

Open Qt Creator.

Load the desired .ui file from the repo.

Make layout or widget changes.

Save the .ui file.

Run the corresponding main.py to test the updated interface.

This makes it easy to modify button placement, widget properties, and overall layout without editing Python code directly.

---


🛠️ Customization & Development

- The GUIs are structured in a modular way so developers can adapt them for custom use-cases.
- Logic handling is done in the Python scripts, while layouts are defined in .ui files.
- You can regenerate Python code from .ui files using:
```bash
pyside6-uic filename.ui -o filename_ui.py
```
This will create a Python class from the .ui file that can be imported into your main program.

---

🤝 Contributing

Contributions are welcome! If you’d like to improve functionality, fix bugs, or adapt the GUI for new devices:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

---
📜 License

This project is released under the GNU General Public License v3.0 License. 
You’re free to use, modify, and distribute the software with attribution.

