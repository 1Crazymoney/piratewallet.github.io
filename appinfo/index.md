---
layout: post
# title: App Info
# author: Satoshi Nakamoto
# tags:   changelog
---

# Supported Devices

| iOS 14.1+ |
| --------- |
| iPhone 12 (iOS 14.1+) |
| iPhone 12 Pro (iOS 14.1+) |
| iPhone 12 Pro Max(iOS 14.1+) |
| iPhone 12 mini (iOS 14.1+) |
| iPhone 11 (iOS 14.1+) |
| iPhone 11 Pro (iOS 14.1+) |
| iPhone 11 Pro Max (iOS 14.1+) |
| iPhone XR (iOS 14.1+) |
| iPhone Xs (iOS 14.1+) |
| iPhone Xs Max (iOS 14.1+) |
| iPhone X (iOS 14.1+) |
| iPhone 8 (iOS 14.1+) |
| iPhone 8 Plus (iOS 14.1+) |
| iPhone 7 (iOS 14.1+) |
| iPhone 7 Plus (iOS 14.1+) |
| iPhone 6s (iOS 14.1+) |
| iPhone 6s Plus (iOS 14.1+) |
| iPhone SE (iOS 14.1+) |
| iPhone SE gen 2 (iOS 14.1+) |
| iPod Touch (7th gen) (iOS 14.1+) |
| iPad 2019 (7th gen) (iOS 14.1+) |
| iPad Pro 12” (2nd Gen) (iOS 14.1+) |
| iPad Pro 10.5” (2nd Gen) (iOS 14.1+) |
| iPad Pro 12” (iOS 14.1+) |
| iPad Pro 9” (iOS 14.1+) |
| iPad 9.7” (2017)(iOS 14.1+) |
| iPad Mini 5 (iOS 14.1+) |
| iPad Mini 4 (iOS 14.1+) |
| iPad Air (3rd gen) (iOS 14.1+) |
| iPad Air 2 (iOS 14.1+) |


# Changelog

#### Version 1.0.0 (6) (2021-12-03)

- Grey screen bug after sending transaction-see detail issue - Git #48
- Fixed - Changed everywhere from Face ID to Biometric ID  - Git #49
- Default server changes, and auto updation of port in settings/private server config
- Fixed - Default fee bug

#### Version 1.0.0 (5) (2021-11-24)

- Fixed - FaceID bug glitching out. Git #35
- Fixed - When you click on "Send Max" it puts a dot instead of a comma and until you replace it with a comma you can't send a transaction: Git #47
- Fixed - 3) When you're inputting or changing the amount you want to send, the keyboard disappears after every number/character you input or delete: 
- Changes related to opening up transaction within the app
- Added tap gesture to dismiss keyboard on recovery phrase (login)
- Fixed - header space pushed down post recovery phrase based login. Git #30 

#### Version 1.0.0 (4) (2021-11-18)

- Fixed address, text size and layout issues on Sending transaction screen
- Changed Lottie animation on the send transaction screen
- Removed metal validation, speed up opening up “Send money” screen.
- Change the button to “Restore Wallet”, remove restore from on login screen
- Fixed Header space issue for returning user
    - Subsequent launches
- Created flow to pick a server in private server config settings
- Fixed Layout issues on private server config screen
- Fixed autocapitalisation on confirm recovery screen
- Fixed cross button shape and sizes across multiple screens
- Fixed back button shape, alignment/placement and sizes across multiple screens.
- Fixed navigation stack issues on recover phrase (settings) screen
- Textual changes on recovery phrase option (login)
- Fixed a use case leading to header being pushed down on all tabs. (On subsequent app Relaunch)
- Updated black screen blocker layout and flow. - Git #26
- Introduced new checkpoints in the code.
- Fixed Request/Send opening/closing speed/layout lag. - - Git #44
- Fixed Recovery Screen Popup, whenever resume an APP - Git #41
- Fixed - New User - Confirm Recovery Phrase - (Back button isn't working) - Git #39
- Minor changes in keyboard first responder
- Added new checkpoints on both recovery phrase and rescan wallet option
- Fixed wallet unlink issue - leading to Oh My Screen! - Git #34
- Fixed google/grammarly keyboard related crashes - Git #33
- Fixed - new User - Set PIN - Wrong pin use case - Git #38
- Fixed - Custom Server config - trimming chars
- Font size changes on Congratulations and authenticate face Id screen
- Fixed autocapitalization on confirm recovery phrase screen
- Fixed - “X” is cut off on send money layout
- Fixed - "ECC Wallet v1.0.0" and/or text with ECC Wallet on it.

#### Version 1.0.0 (2) (2021-11-03)


- Background syncing process - with audio and multiple changes during the week.
- Created flow to send max amount. - I believe we need to build the flow to “double” check / confirm if transaction amount Is huge?
- Adjust sending transaction amount based on wallet balance. Eg: someone has 1.000 ARRR and tries to send 1.000, then amount/balance will be auto adjusted
- Created confirmation screen to confirm before sending the ARRR
- Layout changes on Receive address UI to have text+copy flow
- Removed custom keypads from send and receive ARRR layouts, instead started using native one’s.
- Wrong tx fee - Though its fixed on UI - as its being read from ZCash SDK, but the actual transaction still shows 0.00001 fee - that’s something we need help from rust or probably dig deep in identifying this out.
- Fixed an issue related to memo not being passed when a transaction was made from the wallet
- Allowed transactions to be viewed from wallet tab 
- Editable/Cursor related changes, auto opening up of keyboard on landing upon a screen.
- Moved flow from keychain to local secured cache.
- Allowed app to start afresh on a new installation. Please everyone to install it a fresh by removing existing one.
- Textual changes related to “sent via” to “Sent to”, “From to To:” if it’s sent.
- Home tab shifted up - Still there is one use case in which it shifts down a bit - I have that bug opened up on layouts repo. But, the one you have been pointing (empty space) in comparison to history/settings tab at the top.
- Increased the font size of about - build version a bit
-  Increased the “ARRR” text font size on transaction detail.
- T&C, Support - removed, Privacy updated, and License introduced.
- Birthday selection flow, and rescan from settings.
- Introduced copy icon to copy an address on transaction detail
- In app safari - URL handling
- Send max - touch gesture fixes.
- Unlink back action wasn’t working.
- Introduced about pirate wallet section.

#### Version 1.0.0 (1) (2021-10-17)

- Initial test release