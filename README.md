# Status auta

GitHub Pages frontend + Google Apps Script backend.

## Przed publikacją

1. W `github-site/index.html` podmień `WKLEJ_TUTAJ_URL_APPS_SCRIPT` na adres wdrożenia Apps Script.
2. W `apps-script/Bridge.html` podmień `GITHUB_PAGES_ORIGIN` na origin GitHub Pages, np. `https://twojlogin.github.io`.
3. Nie publikuj `apps-script/Code.gs` w publicznym repo GitHub.
4. W Apps Script wdrożenie jako Web app musi pozwalać na dostęp zgodny z konfiguracją aplikacji. Backend wykonuje zapis do Sheets/Drive jako właściciel skryptu.
