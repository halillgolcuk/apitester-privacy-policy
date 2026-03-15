# ApiTester — Privacy Policy

**Last updated:** 2026

---

## Overview

ApiTester is a developer tool that allows users to capture, inspect, replay, and fuzz test API requests directly from the browser.

ApiTester does **not collect personal information** such as names, emails, or user accounts. The extension processes network request data only to provide its core functionality.

ApiTester does **not sell, rent, or share user data for advertising or marketing purposes.**

---

## Data Processing

### Local processing

When network monitoring is enabled, ApiTester captures network requests from the active browser tab in order to display them to the user.

Captured data may include:

* Request method (GET, POST, etc.)
* Request URL
* Request body (payload)
* Response body
* HTTP status code

This data is:

* Processed locally in the browser
* Kept temporarily while the extension UI is open
* Not stored on any developer-controlled server

Captured requests are cleared when the extension session ends.

---

## AI Analysis (Optional Feature)

ApiTester provides an optional AI-powered analysis feature. This feature is **disabled by default** and only runs when the user explicitly enables it.

When AI Analysis is enabled, limited request data may be sent to a third-party AI service to generate security suggestions.

The following information may be sent:

* Request method
* Request URL
* HTTP status code
* Request body (truncated to a maximum of 2000 characters)
* Response body (truncated to a maximum of 2000 characters)

The data is used only to generate analysis suggestions such as:

* potential security issues
* payload improvements
* testing ideas

The extension does **not execute any code returned by the AI service**.

---

## Data That Is NOT Sent to AI Services

The following sensitive information is **never sent to the AI service**:

* Request headers (including Authorization, Cookie, X-Auth-Token, etc.)
* Response headers
* Authentication credentials
* Browser cookies
* Session tokens

---

## Domain Context (Optional)

If the user sets a testing goal, the extension may send the **tested domain name** (for example `example.com`) to a search API to retrieve publicly available information about the site. This helps provide better AI analysis context.

No personal data or browsing history is transmitted.

---

## Third-Party Services

ApiTester may use the following services when optional features are enabled:

**Groq** – used to generate AI-based analysis suggestions.
**Serper** – used to retrieve public search results for contextual analysis.

These services process only the limited data described above.

---

## Data Storage

ApiTester does not operate any backend server that stores captured request data.

The only data stored persistently is:

* user-defined fuzz testing payload settings

These settings are stored locally using the browser's storage system and are never transmitted to the developer.

---

## User Control

Users have full control over the extension features:

* Network monitoring is activated only when the user enables it.
* AI Analysis is optional and can be disabled.
* The extension can be used entirely without sending any data to external services.

Users should only test websites or APIs that they are authorized to analyze.

---

## Changes to This Policy

This privacy policy may be updated when the extension functionality changes. The "Last updated" date will reflect the latest revision.

---

## Contact

For privacy-related questions, please contact the developer using the contact email listed on the Chrome Web Store listing.
