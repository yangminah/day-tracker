# day-tracker
iphone app
safari -> share to homescreen

Do not clear Safari's cache or website data. That's where every tick and every hour lives — there's no server copy to restore from. Specifically avoid Settings → Safari → Clear History and Website Data, and Settings → Safari → Advanced → Website Data → remove. Deleting the Home Screen icon has the same effect, which is why step 2 belongs at the start rather than after you've built up history.

Safe: force-quitting, restarting your phone, updating iOS, uploading a new index.html.

That last one is the useful part going forward. Storage is tied to the URL, not the file, so when we change something you just upload the new index.html — no reinstalling, no data loss. Only new icons need the delete-and-re-add dance, and you're doing that now.

## Backups

Scroll to the bottom, under **Backup**:

- **Save a copy** opens the share sheet. Pick **Save to Files**, then a folder in iCloud Drive. The file is named `day-tracker-YYYY-MM-DD.json`. The line under the buttons shows when you last did this.
- **Restore** opens Files. Pick a backup and the app shows its date and what's in it, then asks before replacing everything on the phone.

A backup is the one way back from cleared website data, a deleted icon, or a new phone.
