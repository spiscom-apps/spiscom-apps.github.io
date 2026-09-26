# spiscom-apps.github.io

Strona dewelopera **Spiscom** i jego aplikacji na Androida, publikowana przez GitHub Pages:
https://spiscom-apps.github.io/

Czysty HTML i jeden plik CSS (`assets/style.css`), bez frameworka i budowania. Linki są względne.

| Adres | EN | PL |
|---|---|---|
| Spiscom – lista aplikacji, kontakt | `/` | `/pl/` |
| Orbiroad – opis aplikacji | `/orbiroad/` | `/orbiroad/pl/` |
| Orbiroad – polityka prywatności | `/orbiroad/privacy/` | `/orbiroad/pl/privacy/` |
| Orbiroad – zasady korzystania | `/orbiroad/terms/` | `/orbiroad/pl/terms/` |
| Orbiroad – pomoc | `/orbiroad/support/` | `/orbiroad/pl/support/` |

Nowa aplikacja dostaje własny katalog (`/<aplikacja>/`) z własną polityką prywatności i kartę na stronie głównej.

Miejsca do uzupełnienia są oznaczone klasą `todo` (podświetlone na czerwono):

```bash
grep -rn 'class="todo"' --include=*.html .
```

Zmiana działania aplikacji (nowe uprawnienie, serwer, analityka) wymaga aktualizacji polityki: numeru wersji i daty.
