# Reminders dashboard (template)

A single-file, dependency-free reminders dashboard. Type a reminder in plain English
("Call parents tomorrow 3pm", "Team meeting every Monday 8:30am !") and it works out the date,
time, repeat, category and importance. Timed items pop up when due.

- Your reminders are stored only in your own browser (localStorage). Nothing is sent anywhere.
- Open `index.html` directly, or use the GitHub Pages link.
- Edit the category keyword lists (`CATWORDS`) near the top of the script to suit your own work.
- Do not store confidential or identifying information in a shared or government device.

## Google Calendar (optional)

Click "Connect Google Calendar" to sign in with your Google account. Timed reminders for a category that has a
calendar are created as real calendar events, and events from those calendars are shown in the lists.
Edit categories, keywords and each category's calendar under **Settings** (the `cal` field holds a calendar name).
Settings and reminders are stored only in your own browser.
