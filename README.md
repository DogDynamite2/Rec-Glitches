# Rec-Glitches

This guide explains a method I found that can bypass certain restrictions (including Steam). Use it **at your own risk**. I am not responsible for any issues that may occur.

## Requirements

Before you begin, you'll need:

* The Steam installer (`Steam.exe`)
* A Windows PC

## Steam Instructions

### Step 1: Download Steam

Download the Steam installer (`Steam.exe`) and save it to your desktop.

### Step 2: Create the Batch File

1. On your desktop, create a new **Text Document**.
2. Open it and paste the following exactly as shown:

```bat
cmd /min /C "set __COMPAT_LAYER=RUNASINVOKER && start "" "%1""
```

3. Save the file as:

```
RunMe.bat
```

> Make sure the file extension is `.bat` and not `.txt`.

### Step 3: Create a Folder

Create a new folder on your desktop. Since this example uses Steam, name the folder:

```
Steam
```

### Step 4: Run the Installer

1. Drag `Steam.exe` onto `RunMe.bat`.
2. Wait for the installer to launch.
3. Select your preferred language.
4. Install Steam into the **Steam** folder you created on your desktop.

### Step 5: Finish the Process

After the installation finishes, the folder should contain around **18 or more files and folders**.

If everything worked correctly:

1. Steam should open and display an **"Ignore or Repair"** prompt. Click **Ignore**.
2. A second prompt will appear asking **"Install Service"** or **"Cancel"**. Click **Cancel**.
3. Steam should then open normally.
