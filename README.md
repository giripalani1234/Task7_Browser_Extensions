# Task 7: Identify and Remove Suspicious Browser Extensions

## Objective
Understand how to identify and manage suspicious or malicious browser extensions to improve browser security.

## Environment
- OS: Kali Linux
- Browser: Firefox

## Steps Performed
1. Opened Firefox and accessed the Extensions Manager (`Ctrl + Shift + A`).
2. Reviewed all installed extensions.
3. Compared installed extensions against a known list of malicious extensions.
4. Found only one extension installed: **uBlock Origin**.
5. Researched recent security issues related to unmaintained ad blockers Nano Adblocker and Nano Defender.
6. Confirmed uBlock Origin is a trusted, actively maintained alternative.
7. Documented findings and took screenshots of the extensions page and permissions.
8. No suspicious extensions found; no removals needed.

## Installed Extensions
- **uBlock Origin**  
  - Purpose: Blocks ads and trackers to improve privacy and speed.  
  - Status: Kept installed due to trustworthiness.

## Malicious Extension Warning: Nano Adblocker / Nano Defender
- Chromium versions of these extensions became malicious in 2020, collecting user data and performing ad fraud.  
- Firefox versions were safe but are now unmaintained and pose security risks.  
- Users are advised to **remove Nano Adblocker and Nano Defender immediately** and switch to **uBlock Origin**.

## Screenshots
- `extensions_list.png`: List of installed extensions (only uBlock Origin).  
- `ublock_permissions.png`: Permissions requested by uBlock Origin.

## Conclusion
The Firefox browser was free from malicious extensions. With only uBlock Origin installed, it remains secure and efficient. Awareness of malicious extension risks is crucial to maintaining browser security.

---

## Interview Questions and Answers

1. **How can browser extensions pose security risks?**  
   They can read and modify browsing data, steal credentials, or inject malicious content if compromised or malicious.

2. **What permissions should raise suspicion?**  
   Permissions to "read and change all your data on all websites" without clear purpose.

3. **How to safely install browser extensions?**  
   From official stores, verify developers, review permissions and user feedback.

4. **What is extension sandboxing?**  
   Isolating extension processes to restrict access, limiting damage if compromised.

5. **Can extensions steal passwords?**  
   Yes, if given permission to read page content or form data.

6. **How to update extensions securely?**  
   Allow automatic updates from official stores only.

7. **Difference between extensions and plugins?**  
   Extensions add browser features; plugins handle specific content types (mostly deprecated).

8. **How to report malicious extensions?**  
   Use the “Report” option on the extension page in the browser store or contact browser support.

