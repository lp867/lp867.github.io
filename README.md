# lp867.github.io

Leitet auf [Meridian](https://lp867.github.io/Meridian/) weiter und enthält
`.well-known/assetlinks.json`: Damit darf die Android-App von Meridian die Website
im Vollbild (ohne Adressleiste) anzeigen. Der Eintrag ist der SHA-256-Fingerabdruck
des Signaturschlüssels der App. Kommt die App in den Play Store, gehört dort
zusätzlich der Fingerabdruck von Google Play dazu.

`.nojekyll` sorgt dafür, dass GitHub Pages den Ordner `.well-known` ausliefert.
