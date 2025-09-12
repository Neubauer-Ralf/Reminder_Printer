I want to print tasks that I completed so my brain thinks I did something good.
I want it to be automated.

Ingredients:
- RaspberryPI
- Thermal Printer

"Architecture"
<img width="1086" height="500" alt="Pasted image 20250905130724" src="https://github.com/user-attachments/assets/ff6e4798-7249-435f-af6a-b7628c0d59a3" />

Setup PI, SSH into it.
Install CUPS. 
Setup printer in CUPS.
Run python flask with code included.
Import Apple shortcut in shortcut app.
Edit IP.

There is a health endpoint and a print endpoint.
Print endpoint accepts a .json file with list, time, date, note.
