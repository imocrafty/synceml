The **SyncEML** is a desktop-based email archiving tool designed to help users create local, searchable backups of their personal Gmail data.

We are requesting the gmail.readonly scope specifically to:

**List Messages**: Identify the available emails and labels in the user's account to allow for selective archiving.

**Download Headers**: Extract metadata (Subject, Date, Sender) to build a local index for fast searching.

**Download Raw Content**: Retrieve the full email body and attachments to store them in a local JSON/HTML format on the user's hardware.

A narrower scope (such as metadata only) would not work because the primary function of the app is to archive the full content of the emails for offline access. 
The app does not require 'Write' or 'Modify' access, hence we have selected the most restrictive scope that allows for full content reading. 
All data retrieved is stored locally on the user's device and is not transmitted to any external servers."
