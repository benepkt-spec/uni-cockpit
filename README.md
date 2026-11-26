# Uni-Cockpit

Persönliches Lern-Cockpit (WI, 1. Semester, WS 26/27).

Die Seite ist verschlüsselt: `index.html` enthält nur eine Anmeldeseite und einen verschlüsselten Block. Ohne Passwort ist der Inhalt nicht lesbar (RSA-OAEP + AES-GCM, Schlüssel per PBKDF2 aus dem Passwort).
Der Quellcode liegt im privaten Repo `uni-cockpit-src`.
