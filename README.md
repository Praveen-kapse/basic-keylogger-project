**BASIC-KEYLOGGER**

This code implements a **consent-based Typing Session Recorder using HTML, CSS, and JavaScript**

**Purpose:**
It records keystrokes only after explicit user consent and keeps all data locally in the browser. Nothing is uploaded or stored automatically.

**User Interface:**
A clean, centered UI with:

Start (I Consent) button to begin recording

Stop button to end recording

Download Log button to save the recorded keystrokes

A live preview area showing recorded keystrokes with timestamps

**JavaScript Functionality:**

Uses keydown event listeners to capture keys while recording is active

Logs each keystroke with an ISO timestamp

Stores data in memory (array) during the session

Allows downloading the log as a .txt file using a Blob

**Ethical Design:**
Includes a consent confirmation dialog and clear messaging to ensure transparent and responsible use.
