# Notfall-Tresor – Downloads

Hier stehen die veröffentlichten Fassungen des Notfall-Tresors. Die neueste Fassung steht rechts unter «Releases».

Jedes Release enthält die Programmdatei `notfall-tresor.html`, das Lese-Skript `ntresor_lesen.py`, die Formatbeschreibung `FORMAT.md`, den Lizenztext `LICENSE`, die Hinweise `NOTICE.md` sowie die Prüfsummen `SHA256SUMS` mit der Signatur `SHA256SUMS.minisig`.

## Echtheit prüfen

Den öffentlichen Schlüssel nie aus der Programmdatei oder von dieser Seite übernehmen – und auch die Kontaktangaben, um danach zu fragen, nicht von dort. Zurzeit geht das nur persönlich beim Herausgeber oder über eine Vertrauensperson, die den Schlüssel schon geprüft hat. Bewahren Sie den Schlüssel auf und verwenden Sie ihn für jede neue Version. Passt die Signatur einer neuen Version nicht zu diesem Schlüssel: die Datei nicht verwenden und auf dem Weg nachfragen, auf dem Sie den Schlüssel erhalten haben.

```
minisign -Vm SHA256SUMS -P <öffentlicher Schlüssel>
shasum -a 256 -c SHA256SUMS --ignore-missing   # macOS / Linux
certutil -hashfile notfall-tresor.html SHA256   # Windows, dann mit SHA256SUMS vergleichen
```

## Herausgeber

Marcus Hug\
Frostweg 4\
4124 Schönenbuch BL\
Schweiz\
E-Mail: marcus.hug@digital-base.net

Der Notfall-Tresor ist kostenlos. Der Herausgeber ist eine Privatperson.

## Datenschutz

Diese Seite wird von GitHub betrieben. Für Besuch und Herunterladen gilt die Datenschutzerklärung von GitHub: https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement

Das Programm verarbeitet Ihre Eingaben nur auf Ihrem Gerät.

Wenn Sie dem Herausgeber schreiben, verarbeitet er Ihre E-Mail-Adresse und Ihre Nachricht, um sie zu beantworten und das Programm zu verbessern. Er löscht sie nach höchstens 12 Monaten.

Die vollständige Datenschutzerklärung, auch zu freiwilligen Beiträgen und zu Ihren Rechten, steht im Programm unter «Datenschutz & Impressum».
