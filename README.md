# PHP & XAMPP-cursus

Een aparte SD Learn-cursuswebsite voor studenten over het veilig bijwerken van PHP binnen XAMPP op Windows.

## Website publiceren

Activeer GitHub Pages via **Settings → Pages → Deploy from a branch → main → /(root)**.

De website staat daarna op:

https://yildiz2505.github.io/php-xampp-cursus/

## Lokaal bekijken

Start in de projectmap een lokale webserver:

```powershell
php -S localhost:8000
```

Open vervolgens http://localhost:8000. Via een lokaal `file://`-adres kan de browser het Markdown-bestand blokkeren.

## Inhoud

- `index.html` – de cursuspagina;
- `css/` – scherm- en printopmaak;
- `js/app.js` – cursusmenu en Markdown-loader;
- `courses/php/les-01.md` – de les PHP veilig bijwerken in XAMPP.

De vormgeving is gebaseerd op de aparte repository `sd-course-template`. Die template blijft ongewijzigd.
