# Real-Antivirus- 
Detecting Real Antivirus is a Python-based desktop application designed to verify the authenticity of antivirus software installed on a computer.
Using the **Tkinter** library for the graphical user interface, the program allows users to easily check whether a detected antivirus application is genuine or potentially fake.

---------

**🧩Key Features :** 

**🖥️ User-Friendly GUI** — Built with Tkinter for easy interaction.

**🔍 Automatic Antivirus Detection** — Scans the system for installed antivirus applications.

**🔐 Hash Verification** — Uses hashlib to generate SHA256 hashes and compare them with known genuine antivirus signatures.

**📂 System File Access** — Employs the os module to navigate directories and locate antivirus executables.

**⚠️ Fake Antivirus Alert** — Notifies the user if an unverified or suspicious antivirus file is found.

-------

**⚙️ Technologies Used :**

    Python 3.x

    Tkinter            — GUI framework

    hashlib            — File hashing

    os                 — System file handling

    tkinter.filedialog — File selection

    tkinter.messagebox — Alerts and information dialogs

-----

**🚀 How It Works :**

  1.Launch the application via the Tkinter GUI.

  2.The program scans common installation paths for antivirus software using the os module.

  3.For each detected antivirus executable, it computes a SHA256 hash using hashlib.

  4.The hash is compared to a list/database of known genuine antivirus hashes.

  5.Results are displayed in the interface, indicating whether the antivirus is real or fake.

------

**🎯 Purpose:**

This project aims to enhance **cybersecurity awareness** by helping users verify the legitimacy of antivirus software installed on their computers. It’s especially useful for educational demonstrations, cybersecurity training, and personal computer security audits.
