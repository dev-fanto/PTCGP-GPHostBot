# PTCGP-GPHostBot Auto Host GP

This repository contains a backup scenario created with **Klick'r - Smart AutoClicker version 3.2.0**. The scenario is designed to automate specific actions within the 'Social HUB' section of PTCGP. Below, you will find instructions for setup and a brief description of the scenario's functionality.

## Requirements

- **Android platform (device/emu)**.
- **Klick'r - Smart AutoClicker version 3.2.0** is required to import and run this backup scenario.

## How to Use

#### Install Klick'r
- Download and install the Klick'r .apk from [this link](https://f-droid.org/repo/com.buzbuz.smartautoclicker_59.apk).
(For MuMu: Drag and drop the .apk into the instance that will be hosting)

#### Configure Klick'r Permissions
- Go to the Settings app -> Apps -> Klick'r and enable "Display over other apps."

#### Import the Backup
- Download the provided `PTCGP-GPHostBot.zip` file from [this repository](https://github.com/dev-fanto/PTCGP-GPHostBot).
- Move the smart macro into the Mumu shared folder using the "File Transfer" option in Mumu (default folder: C:\Users\YOUR_USER\Documents\MuMuSharedFolder).
- Open Klick'r, click the folder icon in the top right to "Import backup," and select the `PTCGP-GPHostBot.zip` file from the `$Mumu12Shared` folder.

#### Enable Accessibility Permissions
- The first time you run the scenario, Klick'r will request permissions. Enable "Display over other apps" again, then go to Accessibility settings and grant Klick'r the required permissions for full control.

#### Start the Scenario
- Press the "Start Now" button in Klick'r and navigate to the Social HUB page within Pokemon Pocket.
- Press the "Play" button to activate the automation.

## Scenario Description

The scenario automates the following workflow:

#### Processing Friend Requests
- Navigates from Social HUB to the friend request screen.
- Accepts or rejects requests based on badge checks (only accepting requests from players with emblems equipped).

#### Return to 'Social HUB'
- After processing all friend requests, the scenario returns to the 'Social HUB' view.

#### Cleanup of Friend List
- When friend list is full removes all friends.

   `If you need to clean up the friend list before it gets full, simply start the scenario on the Friends tab. `

## Notes

- Ensure that your Klick'r environment is properly configured before running the automation.
- **Important:** Only friend requests from players with emblems equipped will be accepted. Be sure to specify this in your post to guard against trolls or griefers using throwaway accounts.

