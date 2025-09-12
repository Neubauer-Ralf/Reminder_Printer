### I want to print tasks that I completed so my brain thinks I did something good.

#### I want it to be automated.

## Ingredients:
- RaspberryPI
- Thermal Printer

## "Architecture"
<img width="1086" height="500" alt="Pasted image 20250905130724" src="https://github.com/user-attachments/assets/ff6e4798-7249-435f-af6a-b7628c0d59a3" />

## How To
2. Setup PI, SSH into it
3. Connect Printer to PI via USB
4. Install CUPS on PI
5. Setup printer in CUPS Interface
6. Run python flask with code included in repo
7. Import Apple shortcut in shortcut app
8. Edit IP
9. ...
10. Profit

## Info
- There is a **/health** endpoint and a **/print** endpoint. Default port is **5000**.
- Print endpoint accepts a .json file with
    - list
    - time
    - date
    - note
