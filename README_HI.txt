HisabBuddy PWA Test Starter

इस ZIP में mobile-first web app/PWA source है।
शामिल: income, expense, lent/borrowed entries, monthly report, CSV, print/PDF, local backup/restore, PWA manifest/service worker, Firebase Google/phone login और Firestore sync का starter code.

महत्वपूर्ण:
1) यह ZIP सीधे installable APK नहीं है।
2) PWA को Home Screen पर install करने के लिए HTTPS website पर host करना जरूरी है। file:// से install prompt/service worker नहीं चलता।
3) Cloud sync अभी live नहीं है। Firebase project बनाना, Web App config firebase-config.js में डालना, Authentication में Google और Phone providers enable करना, authorized domain set करना, Firestore database बनाना और firestore.rules deploy करना जरूरी है।
4) Phone OTP में reCAPTCHA और SMS billing/limits लागू हो सकते हैं।
5) Cloud sync code शुरुआती merge demo है; production से पहले duplicate/conflict handling, deletion sync, encrypted backup, privacy review और extensive testing जरूरी है।
6) इस prototype में data localStorage में है; इसे highly sensitive financial records के लिए production-secure न मानें।
7) GitHub Pages जैसे HTTPS hosting पर files upload कर सकते हैं। पहले किसी भरोसेमंद adult की मदद से Firebase और hosting setup करें।
