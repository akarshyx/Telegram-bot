---
name: Casino VPS testing
description: User tests downloaded casino bot source in Replit before moving changes to their VPS.
---

The live casino bot runs on the user's VPS. Replit is for editing and testing downloaded `main.py` before they transfer it back; do not launch against production bot credentials or real casino data.

**Why:** The user explicitly said the casino is running on a VPS and asked not to break it.

**How to apply:** Make targeted changes to uploaded source. Use a separate test bot token and isolated data for runtime checks. If required companion modules are missing, ask for the complete project bundle rather than inventing replacements.
