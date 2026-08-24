# EXP6 – File Transfer Between Virtual Machines

## Aim

To find a procedure to transfer files from one virtual machine to another virtual machine.

## Procedure

There are three methods to transfer files between virtual machines:

1. Copy and paste / Drag and Drop
2. USB drive
3. Network share

### Method 1 – Copy and Paste / Drag and Drop

1. Start the virtual machine.
2. Open **Devices → Drag and Drop** in VirtualBox.
3. Select **Host to Guest**, **Guest to Host**, or **Bidirectional**.
4. Transfer the required files using drag and drop.

### Method 2 – USB Drive

1. Install the VirtualBox Extension Pack.
2. Insert the USB device.
3. Open VirtualBox settings and enable USB support.
4. Attach the USB device to the required virtual machine.
5. Copy the required files using the USB drive.

### Method 3 – Network Share

1. Install VirtualBox Guest Additions.
2. Open **Devices → Shared Folders → Shared Folders Settings**.
3. Add the folder to be shared.
4. Enable **Auto-mount** and **Make permanent**.
5. Open the shared folder from the guest operating system.
6. Transfer the required files.

## Result

Thus, the procedure to transfer files from one virtual machine to another virtual machine was executed successfully.
