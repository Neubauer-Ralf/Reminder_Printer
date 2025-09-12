### I want to print tasks that I completed so my brain thinks I did something good.

#### I want it to be automated.

## Ingredients:
- RaspberryPI
- Thermal Printer

## "Architecture"
<img width="1086" height="500" alt="Pasted image 20250905130724" src="https://github.com/user-attachments/assets/ff6e4798-7249-435f-af6a-b7628c0d59a3" />

## How To
1. Setup PI, SSH into it.
2. Install CUPS.
3. Setup printer in CUPS.
4. Run python flask with code included.
5. Import Apple shortcut in shortcut app.
6. Edit IP.

## Info
- There is a **/health** endpoint and a **/print** endpoint. Default port is **5000**.
- Print endpoint accepts a .json file with
    - list
    - time
    - date
    - note
