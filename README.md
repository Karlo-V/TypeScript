README.md
User Management Project
Beschreibung
Dieses Projekt ist eine einfache TypeScript-Anwendung, die Benutzerdaten und Medien verwaltet. Es enthält Funktionen, um Benutzer zu erstellen, Medien hinzuzufügen und Benutzer basierend auf ihrem Standort zu filtern.

Projektstruktur
src/user/user-models.ts: Enthält die Interfaces User, Profile, Account, und Media.
src/user/user-utils.ts: Implementiert Funktionen wie addMediaToUser und filterUsersByLocation.
src/main.ts: Führt die Funktionen aus und zeigt ihre Funktionalität.
test/user-utils.test.ts: Enthält Unit-Tests für die Funktionen in user-utils.ts.
Verwendete Tools
TypeScript: Ermöglicht statische Typisierung.
ESBuild: Schnelles Bündeln und Kompilieren des TypeScript-Codes.
Jest: Test-Framework zur Sicherstellung der Funktionalität durch Unit-Tests.
ESLint: Linter zur Verbesserung der Codequalität.
Prettier: Automatische Codeformatierung.
Setup und Installation
Repository klonen:

bash
Copy code
git clone <repository-url>
cd user-management-project
Abhängigkeiten installieren:

bash
Copy code
npm install
Projekt bauen:

bash
Copy code
npm run build
Tests ausführen:

bash
Copy code
npm test
Wie man das Projekt ausführt
Bundle erstellen:

bash
Copy code
npm run build
Ausführen:

Öffnen Sie die Datei dist/index.html im Browser, um die Konsolenausgabe zu sehen.
Alternativ kann src/main.ts direkt mit NodeJS ausgeführt werden:
bash
Copy code
node dist/bundle.js
Tests
Unit-Tests sind mit Jest implementiert. Sie prüfen die wichtigsten Funktionen des Projekts:

Medien zu einem Benutzer hinzufügen
Benutzer nach Standort filtern
Berechnung des Gesamtalters der Benutzer
Tests können mit folgendem Befehl ausgeführt werden:

bash
Copy code
npm test
Linter und Formatierung
ESLint kann mit folgendem Befehl ausgeführt werden:

bash
Copy code
npm run lint
Prettier zur Formatierung:

bash
Copy code
npm run format
Lizenz
