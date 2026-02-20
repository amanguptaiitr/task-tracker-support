# task-tracker-support

# Task Tracker – Support

**Task Tracker** is an iOS app that helps you organise your to-dos using the Eisenhower Matrix. Describe a task in plain English, and AI automatically places it in the right quadrant (Do First, Schedule, Delegate, or Eliminate) based on its importance and urgency.

---

## Contact & Support

**Email:** amandevaccquestion

For bug reports, feature requests, or any questions, please email the address above or [open an issue](https://github.com/amanguptaiitr/task-tracker/issues/new) on this repository. We aim to respond within 2 business days.

---

## Frequently Asked Questions

**How do I add a task?**
Open the Chat tab and describe your task in plain English — for example, "Prepare slides for the Monday board meeting." The AI will classify it automatically.

**Can I add tasks without AI?**
Yes. Use the format: `task title; true/false; true/false`
The first value is importance, the second is urgency.
Example: `Buy groceries; false; true` adds an unimportant but urgent task.

**What is the Eisenhower Matrix?**
It is a 2×2 priority grid:
- **Do First** – Important and Urgent
- **Schedule** – Important, Not Urgent
- **Delegate** – Not Important, Urgent
- **Eliminate** – Not Important, Not Urgent

**Can I move tasks between quadrants?**
Yes. In the Matrix tab, drag any task card to a different quadrant to reclassify it.

**How do I delete my account?**
Go to the **Account tab** (last tab) → tap **Delete Account**. This permanently removes your account and all your tasks from our servers.

**How do I turn off AI classification?**
Go to the **Account tab** → **Privacy** section → toggle off **AI Classification**. Your tasks will no longer be sent to Google Gemini.

**The app is stuck or crashing — what should I do?**
Try force-quitting and relaunching the app. If the issue persists, email us with your iOS version and a description of what happened.

---

## Privacy Policy

**Last updated: February 2026**

### Data we collect
- **Account information**: your name and email address from Google or Apple Sign-In.
- **Task data**: the text you enter when creating tasks, and any corrections you make to AI suggestions.

### How we use your data
- Task text and correction history are sent to **Google Gemini** (Google's AI service) via a secure Firebase Cloud Function solely to classify tasks by importance and urgency.
- Account and task data are stored in **Firebase Firestore** (Google Cloud) and are only accessible to your account.
- We do not sell, rent, or share your data with any third party beyond what is described here.

### Third-party services
| Service | Provider | Purpose | Privacy Policy |
|---|---|---|---|
| Firebase Auth | Google | Account sign-in | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Firebase Firestore | Google | Task storage | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Google Gemini | Google | AI task classification | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Google Sign-In | Google | Authentication | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Apple Sign-In | Apple | Authentication | [apple.com/legal/privacy](https://www.apple.com/legal/privacy/) |

### Your rights and controls
- **Disable AI**: Account tab → Privacy → toggle off AI Classification.
- **Delete your data**: Account tab → Delete Account. All data is permanently removed from Firebase.
- **Export/access**: Email us and we will provide a copy of your stored data within 30 days.

### Data retention
Your data is retained until you delete your account. Deleting your account removes all personal data from our servers immediately.

### Contact
For privacy-related questions: support@tasktracker.app *(replace with your real email address)*

---

## App Version History

See [Releases](https://github.com/amanguptaiitr/task-tracker/releases) for version history and changelogs.
