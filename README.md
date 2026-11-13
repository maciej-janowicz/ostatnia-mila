# Ostatnia mila komisarza Głąba

Gra na telefon do **wykładu 6 „Sieci dostępowe”** z przedmiotu *Architektura systemów telekomunikacyjnych*. Trwa ok. **20 minut**.

Z zamku barona de Thunder-ten-Tronkh skradziono dokumenty rodowodowe owczarka Volt-R-a. Emerytowany komisarz Stanisław Głąb ściga dwóch legendarnych włamywaczy, Wieńczysława Nieszczególnego i Bogumiła Kadrylla, przez sześć kontynentów. Na każdym etapie trafia na inną sieć dostępową.

## Dla studentów

1. Proszę otworzyć grę w przeglądarce telefonu (adres lub kod QR na rzutniku).
2. Proszę wpisać imię lub pseudonim (pojawi się na certyfikacie) i kliknąć **Wsiadam do pociągu**.
3. Za poprawną odpowiedź za pierwszym razem dostaje się **10 smaczków dla Volt-R-a** 🦴, za drugim 5, za trzecim 2. Po trzech pudłach Volt-R sam wskazuje odpowiedź.
4. Kolejny etap otwiera się po rozwiązaniu wszystkich zadań poprzedniego. Wolno naradzać się z sąsiadem.
5. Na końcu proszę zrobić **zrzut ekranu całego certyfikatu**, razem z kodem weryfikacyjnym.

## Trasa pościgu

| Minuty | Etap | Temat |
|:---:|:---|:---|
| 0–2 | Prolog · Westfalia: Zamek Thunder-ten-Tronkh | anatomia sieci dostępowej, BNG, wskaźnik wykorzystania, koszty |
| 2–5 | Etap I · Buenos Aires: Kamienica pełna kotów | xDSL: DMT, przesłuch, wektoryzacja, PPPoE i MTU 1492 |
| 5–8 | Etap II · Nowy Jork: Hotel z kablówką | HFC i DOCSIS: szyfrowanie, żądanie–przydział, dzielenie węzłów |
| 8–12 | Etap III · Tokio: Światło w kociej kawiarni | PON: rozgałęźniki, długości fali, nieposłuszny terminal, pomiar odległości |
| 12–14 | Etap IV · Syberia: Budżet na mrozie | budżet mocy optycznej, klasy B+ i C+ |
| 14–17 | Etap V · Australia: Anteny na pustkowiu | FWA, satelity GEO i LEO |
| 17–20 | Finał · Pekin: Zakazane Miasto | porównanie technologii, wyłączanie miedzi |

Razem **26 zadań**, najwyżej **260 smaczków**.

## Dla prowadzącego

**Tryb rzutnika:** ten sam adres z końcówką `#rzutnik`, np. `https://maciej-janowicz.github.io/ostatnia-mila/#rzutnik`. Pokazuje duży zegar odliczający 20 minut i plan etapów z podświetleniem bieżącego. Zegar rusza po kliknięciu **Start pościgu**.

**Sprawdzanie certyfikatu:**

1. W trybie rzutnika, w ramce **Sprawdzenie kodu z certyfikatu**, wpisać **imię** i **liczbę smaczków** dokładnie tak, jak widnieją na zrzucie (wielkość liter i spacje na początku i końcu nie mają znaczenia).
2. Porównać wyświetlony kod z kodem na zrzucie.
   - Kody **zgodne**: wynik prawdziwy.
   - Kody **różne**: imię lub liczba smaczków zostały zmienione albo przepisane z błędem.

Kod chroni przed poprawieniem liczby na obrazku. Nie jest zabezpieczeniem kryptograficznym: ktoś, kto przeczyta kod źródłowy strony, mógłby go wyliczyć sam.

### Rangi na certyfikacie

| Wynik | Ranga |
|:---:|:---|
| ≥ 90% | Komisarz światłowodowy z odznaką Volt-R-a |
| ≥ 75% | Inspektor ostatniej mili |
| ≥ 50% | Aspirant pętli abonenckiej |
| < 50% | Posterunkowy na stażu u Volt-R-a |

## Publikacja na GitHub Pages

1. Utworzyć publiczne repozytorium, np. `ostatnia-mila`.
2. Wgrać do niego plik `index.html` (i ten `README.md`).
3. **Settings → Pages → Build and deployment:** *Source: Deploy from a branch*, *Branch: main*, folder */ (root)* → **Save**.
4. Po 1–2 minutach gra jest dostępna pod adresem `https://<nazwa-użytkownika>.github.io/ostatnia-mila/`.

Gra to jeden samodzielny plik HTML. Nie wymaga serwera ani instalacji; z zewnątrz pobiera tylko kroje pisma z Google Fonts (bez nich użyje czcionek systemowych).

## Prywatność

Gra niczego nie wysyła. Imię i postęp są zapisywane wyłącznie w pamięci przeglądarki na urządzeniu gracza (`localStorage`). Prowadzący poznaje wynik tylko wtedy, gdy student sam przekaże zrzut ekranu.

## Autorstwo

Fabuła na motywach opowiadania Macieja Janowicza o komisarzu Stanisławie Głąbie, baronie de Thunder-ten-Tronkh i owczarku Volt-R. Nazwisko barona nawiązuje do *Kandyda* Woltera. Treści dydaktyczne odpowiadają wykładowi 6 przedmiotu *Architektura systemów telekomunikacyjnych*.
