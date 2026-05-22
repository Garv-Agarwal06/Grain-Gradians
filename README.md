# Crops Portal — Python Final Project

Simple GUI app for farmers and consumers backed by MySQL. The primary entrypoint is `main.py`.

**Prerequisites**
- Python 3.8 or newer
- A working MySQL server (or compatible) reachable from this machine
- Optional: virtual environment (recommended)

**Install (recommended)**
1. Create and activate a virtual environment:

```powershell
python -m venv venv
# Windows
venv\Scripts\activate
```

2. Install Python dependencies:

```powershell
pip install -r requirements.txt
```

**About tkinter**
- `tkinter` is part of the Python standard library on most official installers (Windows and many macOS/Linux builds).
- If you get an import error for `tkinter`, install the OS package:
  - Debian/Ubuntu: `sudo apt install python3-tk`
  - Fedora: `sudo dnf install python3-tkinter`
  - macOS (Homebrew): `brew install tcl-tk` and ensure Python is built/linked against it, or use the official python.org installer which bundles Tcl/Tk.

**Database (MySQL)**
- `main.py` contains a `DB_CONFIG` block near the top — edit host/user/password/port as needed.
- The application will attempt to create the database and necessary tables automatically on first run.

**Run**
Start the GUI app:

```powershell
python main.py
```

**Files**
- `main.py` — application entrypoint and GUI
- `requirements.txt` — Python pip dependencies

If you'd like, I can add example `.env` support or a sample SQL dump for easier local setup.
