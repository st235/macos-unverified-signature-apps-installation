# A few words on how to install and run unverified macOS apps

`macOS` includes built-in security features that prevent apps from unknown developers or unverified signatures from running immediately (shame on 🍎 as this basically introduces a paywall for indie devs).

If you're installing a `.dmg` or `.app` file and encounter warnings, follow the steps below to run the app safely.

>![NOTE]
> The steps in this guide use `BlackJack Math` — a game available on [itch.io](https://st235.itch.io/blackjack-math) — as an example.

## Step 1: Download the app image

Download the `.dmg` file from the trusted source.

## Step 2: Attempt to open the image

Double-click the `.dmg` file. You’ll likely see a message like:

![Warning](./assets/step%202.%20attempt%20to%20open%20the%20image.png)

>![INFO]
>The message means that the app was signed with a local (aka ad-hoc) or free developer's license.

Click **"Done"** when this message appears.

## Step 3: allow the disk image via system settings

1. Open **System Settings**.
2. Go to **Privacy & Security**.
3. Scroll to find the message about the disk image being blocked.
4. Click **"Open Anyway."**

![Step 3: allow the disk image via system settings](./assets/step%203.%20allow%20the%20image%20via%20privacy%20settings.png)

## Step 4: confirm the disk image launch

A new dialog will appear asking if you’re sure you want to open the disk image.

Click **"Open Anyway"** to proceed.

![Step 4: confirm the disk image launch](./assets/step%204.%20confirm%20the%20disk%20image%20launch.png)

## Step 5: Move the App to Applications

If the app is inside a `.dmg` disk image, you’ll see a window like the one below (with your disk image content).

![Step 5: disk image](./assets/step%205.%20disk%20image.png)

Drag and drop the app into your **Applications** folder.

## Step 6: Open the app from applications

Go to **Finder** → **Applications** (alternatively, open **Launchpad**), and double-click the app to launch it.

>![INFO]
>You most likely will encounter the unverified developer warning again.

![Step 6: app warning](./assets/step%206.%20app%20warning.png)

Click **"Done"**, and repeat the [System Settings](#step-3-allow-the-disk-image-via-system-settings) step one last time:

![Step 6: app system settings](./assets/step%206.%20app%20system%20settings.png)

Click **"Open Anyway"**, then confirm the prompt that appears. The app should now launch without issues.

![Step 6: dialog](./assets/step%206.%20dialog.png)

>![IMPORTANT]
>Only bypass these security warnings if you're confident the app is from a trusted source. macOS uses these checks to protect against potentially harmful software.