## 1. Project Title & Description

Start with a clear heading and a 2-3 sentence summary of what the app does.

> **SyncEML**
> A desktop application designed to synchronize and archive Gmail messages locally in `.eml` format for offline analysis and secure storage.

## 2. Key Features

List the functions you mentioned in your OAuth justification. This helps reviewers confirm the app's "Limited Use."

* **Gmail Integration:** Connects securely to your Google account using `gmail.readonly`.
* **Local Archiving:** Downloads raw email content directly to your machine.
* **Header Analysis:** Views subject lines, dates, and senders without needing an active internet connection.

## 3. Privacy & Data Handling (Crucial for Verification)

Because you are using a Restricted Scope, you should explicitly state your data flow here.

* **No Server-Side Storage:** This app is a client-side tool. Your email data is never uploaded to our servers.
* **Encryption:** Mention if you encrypt the local `.eml` files or the local database.
* **Limited Use:** Include a small note: *"This app's use of information received from Google APIs adheres to the Google API Service User Data Policy."*

## 4. Installation & Setup

Since it's a desktop app, tell the user how to run it.

* **Prerequisites:** (e.g., Python 3.10+, Node.js, or a specific OS).
* **Setup:**
1. Clone the repo.
2. Install dependencies (e.g., `npm install` or `pip install -r requirements.txt`).
3. Run the executable or script.



## 5. OAuth Verification Status

This is a helpful "pro-tip" for reviewers.

> **Note to Reviewers:** This application is currently in the verification process. The Privacy Policy can be found at [https://imocrafty.github.io/synceml/privacy.html](https://www.google.com/search?q=https://imocrafty.github.io/synceml/privacy.html).

