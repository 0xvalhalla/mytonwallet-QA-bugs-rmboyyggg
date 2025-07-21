🐞 Bug Report — MyTonWallet (iOS)

## 1. 🔐 PIN Input Visible on Screen Recording (No Protection)
	•	During PIN setup after wallet import, the app allows full screen recording.
	•	The keyboard input and button presses are clearly visible in the recorded video.
	•	Expected behavior: The screen should be protected (blurred or blocked) during sensitive input to prevent screen recording.
	•	Actual behavior: Full visibility of PIN input during screen recording.
	•	Risk: Sensitive data (PIN) could be leaked or stolen if the device is being recorded.

## 2. 🔄 Biometric Setup Option Not Working Properly
	•	After setting a PIN, the app shows two options: “Use Face ID” and “No”.
	•	Regardless of which option is selected, the user is directly logged into the wallet without additional authentication.
	•	Face ID is activated even if the user selects “No”.
	•	Expected behavior: “No” should disable biometric login and require manual PIN entry next time.
	•	Actual behavior: Face ID is active and used by default, even when declined.

## 3. ⚙ Touch ID Icon Appears on Non-Touch ID Device
	•	After closing and reopening the app, a Touch ID fingerprint icon appears, even though iPhone 11 does not support Touch ID.
	•	Pressing the fingerprint icon immediately switches to Face ID authentication.
	•	Expected behavior: The app should detect the available biometric method and only show the appropriate icon (Face ID only).
	•	Actual behavior: Incorrect biometric icon (Touch ID) appears, then auto-switches.

## 4. 💱 Currency Switching Is Slow and Unresponsive
	•	In the currency settings (USD, EUR, BTC, TON, etc.), switching between currencies is delayed and sluggish.
	•	User input is not immediately reflected on the interface — requires multiple taps or force click.
	•	Expected behavior: UI should instantly switch and update selected currency.
	•	Actual behavior: Delayed response and unresponsive buttons.

## 5. 🔁 No Reset PIN Option via Seed Phrase
	•	There is no available option to reset PIN using the seed phrase.
	•	If the user forgets the PIN and does not use Face ID, the wallet becomes inaccessible.
	•	Expected behavior: A secure “Reset PIN using seed phrase” option should be provided.
	•	Actual behavior: Missing critical recovery option.

📎 Supporting Evidence : 
[Watch bug record via Google Drive]( https://drive.google.com/file/d/1AXAjNIqA_co5Is3ztoOTVyJJlRSt2yGM/view?usp=drivesdk )

Screen recordings and proof of bugs are available upon request.

📱 Device: iPhone 11
📲 iOS Version: 18.5 (latest)

🔢 App Version: MyTonWallet v3.8.3

🪪 Github : Valhalla Team
🪪 Tweet : valhallafop_

🪪 Tweet : 0xrvmakarov404_
🪪 Telegram ID : @Rmboyyggg
📛 Nick Telegram: RVMakarov
