# AmeriStudy AI — Privacy Policy

This repository hosts the official **Privacy Policy** for **AmeriStudy AI**, an AI-powered mobile application that helps people prepare for the U.S. naturalization civics test.

## Live Page

The privacy policy is publicly available at:

**[https://uria0868-byte.github.io/ameristudy-privacy/](https://uria0868-byte.github.io/ameristudy-privacy/)**

This URL is used in the Apple App Store and Google Play Store listings for AmeriStudy AI.

---

## About AmeriStudy AI

AmeriStudy AI is an independent educational app that helps immigrants prepare for the civics portion of the U.S. naturalization interview. It is **not affiliated with, endorsed by, or connected to** the U.S. Citizenship and Immigration Services (USCIS) or any U.S. government agency.

### Key Features

| Feature | Description |
|---|---|
| **Car Mode** | Hands-free audio learning with text-to-speech and voice answer evaluation |
| **Test Mode** | Simulated USCIS civics interview with 10 or 20 questions |
| **Learning Mode** | Flashcard-based study with 3-stage hints and mnemonics |
| **AI Mock Interview** | Conversational interview with an AI USCIS officer persona |
| **Rewards System** | XP, tokens, and achievements for study milestones |
| **3 Difficulty Levels** | Beginning, Intermediate, and Advanced |

---

## Privacy Summary

| Data Type | Stored Where | Retained |
|---|---|---|
| Study progress, scores, streaks | Device only (AsyncStorage) | Until app is uninstalled |
| Voice audio (Car Mode) | Server — transient only | Deleted immediately after transcription |
| AI interview session data | Server memory only | Discarded when session ends |
| Personal identity data | Not collected | N/A |

> **We do not sell your data. No account or login is required to use the app.**

For full details, read the [Privacy Policy](https://uria0868-byte.github.io/ameristudy-privacy/).

---

## Repository Structure

```
ameristudy-privacy/
├── index.html      ← Privacy policy page (served by GitHub Pages)
└── README.md       ← This file
```

---

## Updating the Policy

To update the privacy policy:

1. Edit `index.html` — update the content and the **Effective Date** near the top of the file.
2. Commit and push to the `main` branch.
3. GitHub Pages will automatically redeploy within 1–2 minutes.

```bash
git add index.html
git commit -m "Update privacy policy — <brief description of change>"
git push
```

---

## Contact

**Developer:** AmeriStudy AI Team  
**GitHub:** [github.com/uria0868-byte](https://github.com/uria0868-byte)

For privacy-related questions or data deletion requests, please open an issue in this repository.

---

## License

The privacy policy text in this repository is specific to AmeriStudy AI and its data practices. It is not a template and should not be reused for other applications without modification.
