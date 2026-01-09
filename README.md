# Project 12 – Building the OS (Sys Library)

**Course:** Build a Modern Computer from First Principles (Nand2Tetris Part II)  
**Institution:** Hebrew University of Jerusalem  
**Author:** Aravind Kumar GS  
**Email:** aravindkumar06062006@gmail.com  
**License:** MIT (Educational purposes only)

---

## Overview

Project 12 implements the **basic operating system (OS) routines** in the **Jack language**. These routines provide essential services to user programs, including memory access, arithmetic, I/O, and string handling. The project introduces the **Sys library**, which serves as the foundation for the Hack OS.

The Sys library consists of the following Jack classes:

- **Array.jack** – Array manipulation routines  
- **Keyboard.jack** – Keyboard input routines  
- **Math.jack** – Mathematical operations (add, multiply, divide, etc.)  
- **Memory.jack** – Memory access and heap management  
- **Output.jack** – Textual output routines  
- **Screen.jack** – Screen display and graphics routines  
- **String.jack** – String handling routines  
- **Sys.jack** – Top-level interface for the OS routines  

These classes are tested using VM Emulator and Hardware Simulator to ensure correct functionality.

---

## Files to Submit

Your submission must include the following **Jack source files**, **all at the top level** (no directories):

```

Array.jack
Keyboard.jack
Math.jack
Memory.jack
Output.jack
Screen.jack
String.jack
Sys.jack

```

> **Important:** Do not include compiled `.vm` files. Only the `.jack` source files are required.

---

## Submission Instructions

1. Place all **Jack source files** in a single folder.  
2. Zip the files at the **top level** (no subfolders) as:  
```

project12.zip

```
3. Upload via the **“My Submissions”** tab on the course platform.

---

## Notes

- Ensure that all routines in the Sys library are **fully functional** and correctly implemented in Jack.  
- The OS routines will be used in **later projects**, so correctness is crucial.  
- Use the **VM Emulator and Hardware Simulator** to test memory, math, screen, keyboard, array, and string functionalities.  

---

## License

MIT License – Educational purposes only. Do **not** distribute or claim as your own work.
