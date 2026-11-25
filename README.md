# heartbreaking beauty — website

Statische Seite ohne Build-Schritt.

```
index.html   Seite (HTML, CSS, JS inline)
assets/      Bilder (Graustufen; die C/M/Y/K-Schichten erzeugt der Browser)
fonts/       Suisse Intl Bold, Regular und Mono als .woff2 (Lizenz: nur eigene Domain)
assets/heartbreaking.svg  Wortmarke aus der Markerskizze (im HTML inline eingebettet)
.nojekyll    GitHub Pages liefert die Dateien unverändert aus
```

Suisse Intl lädt nur auf den Domains, die oben in `index.html` unter `DOMAINS` stehen (Lizenz: nur eigene Domain). Überall sonst erscheint Helvetica.
