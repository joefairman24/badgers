# Badgers team website

Parent website: https://joefairman24.github.io/badgers/

## Update the team information

Edit **team.json** using GitHub's pencil button, then choose **Commit changes**. GitHub Pages will publish the update, usually within a few minutes. You can also ask Codex to make a change.

- **events**: date (YYYY-MM-DD), kind (game or practice), opponent, start/end (24-hour Eastern time), field, and cancelled (true or false).
- **snacks**: eight family assignments, in week order. Leave an empty string for an open week.
- **updates**: dated announcements. New entries look like this:

```json
{"date":"2026-09-21","title":"Your announcement title","body":"Your message to parents."}
```

Add entries inside the updates array, separated by commas. Keep the surrounding JSON punctuation intact. Do not put parent email addresses, phone numbers or private coaching notes in this public repository.

## Hosting

GitHub Pages: deploy from branch `main`, folder `/ (root)`. No build or third-party services required. All paths are relative so the site works under `/badgers/`.

Schedule source: the supplied YMCA schedule and screenshot dated September 21, 2026, with duplicate practices collapsed. Snack weeks 5 and 8 remain open; snack weeks have not been mapped to game dates.
