# Frequently Asked Questions

**Q: Which version of Python should I install?**
A: Install the latest stable release of Python 3 from [python.org](https://www.python.org/downloads/), unless a specific project requires an older version.

**Q: Do I need to install pip separately?**
A: No. Since Python 3.4, `pip` is included by default with the standard installer. If it's missing, reinstall Python and make sure the pip option is selected.

**Q: What's the difference between `python` and `python3` commands?**
A: On Windows, `python` typically points to Python 3 after installation. On macOS and Linux, `python3` is often required because `python` may be unmapped or reserved for legacy Python 2 in older systems.

**Q: Can I install multiple versions of Python on the same machine?**
A: Yes. Tools like `pyenv` (macOS/Linux) or the Python Launcher (`py`, on Windows) let you manage and switch between multiple installed versions.

**Q: Do I need administrator/root privileges to install Python?**
A: On Windows and macOS, the standard installer may prompt for administrator access. On Linux, installing via a package manager (e.g., `apt`, `dnf`) typically requires `sudo`. You can also install Python without elevated privileges using tools like `pyenv`.

**Q: What is a virtual environment, and do I need one?**
A: A virtual environment is an isolated Python setup for a specific project, keeping its dependencies separate from other projects. It's not required to install Python, but it's strongly recommended once you start installing packages. Create one with:
```
python -m venv myenv
```

**Q: How do I uninstall Python?**
A:
- **Windows:** Use "Add or Remove Programs" and select the Python version to uninstall.
- **macOS:** Remove the Python framework from `/Library/Frameworks/Python.framework` and related symlinks, or use Homebrew's `brew uninstall python` if installed that way.
- **Linux:** Use your package manager, e.g., `sudo apt remove python3`.

**Q: How do I update Python to a newer version?**
A: Download and run the newer installer from python.org, or use your package manager/Homebrew. Existing virtual environments won't automatically upgrade and may need to be recreated.

**Q: I installed Python, but my code editor doesn't detect it. What do I do?**
A: Restart the editor after installation, and manually select the Python interpreter path in the editor's settings if it isn't detected automatically.

**Q: Where can I get more help?**
A: See the [Troubleshooting section](Installation.md#troubleshooting) in this module, or consult the official [Python documentation](https://docs.python.org/3/).
