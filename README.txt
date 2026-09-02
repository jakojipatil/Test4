FINAL TEST SETUP

Required flow:
    index.html
        |
        | Login
        v
    consent.html
        |
        v
    Consent Management Form

Test credentials:
Email: testuser@example.com
Password: Test@123

The consent form is displayed in consent.html after login.
There is NO index2.html in this setup.

Run:
    python -m http.server 8000

Open:
    http://localhost:8000/index.html

Important:
- Keep index.html, consent.html, script.js and styles.css in the same folder.
- Do not open the files using file:// if the consent APIs/scripts require HTTP.
- The login is dummy authentication for testing only.
