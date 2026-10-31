# Rješavač inverznih funkcija

> Dio kolekcije **Aplikacije za fakultet**: https://djuk400.github.io/

**Sajt:** https://djuk400.github.io/Rje-ava-a-inverznih-funkcija/

Rješavač za 1. zadatak kolokvijuma iz matematike: *"Skicirati datu funkciju, te odrediti i skicirati inverznu funkciju."* Radi za funkcije oblika **f(x) = A·g(Bx + C) + D**, gdje je g arcsin, arccos, arctg, arcctg, sin, cos, tg ili ctg.

## Šta radi

- **Rješavač:** upišeš funkciju, npr. `2arcsin(3x − 1) + π/4` ili `2sin(2x − π/3) + 1`. Dobiješ redom domen, kodomen, monotonost, karakteristične tačke, skicu f kroz 5 koraka transformacije, izvođenje inverza, skicu f⁻¹ kroz 5 koraka transformacije i zajednički grafik f i f⁻¹ sa pravom y = x.
- **sin, cos, tg i ctg:** pošto nisu injektivne na cijelom domenu, uzima se standardni luk (argument u [−π/2, π/2] za sin, [0, π] za cos, (−π/2, π/2) za tg, (0, π) za ctg) i to se jasno naglašava.
- **Objašnjenja:** svako uprošćavanje je napisano eksplicitno (polazni izraz → pravilo → rezultat), a dugme "Zašto?" objašnjava razlog za svaki korak.
- **Vježba:** nasumični zadaci sa gotovim graficima (sve, samo arcus ili samo sin/cos/tg/ctg). Postupak se otvara na klik.
- **Osnovna pravila:** grafici arcus funkcija i lukova sin, cos, tg, ctg, postupak za crtanje inverza, transformacije grafika, identiteti, nejednakosti i česte greške.

## Pouzdanost

- Sve se računa tačno, sa razlomcima i višekratnicima π.
- Svaki inverz se automatski provjerava na 800 tačaka. Ako provjera ne prođe, rezultat se ne prikazuje.
- Za nepodržan unos (ln, x van funkcije, x², zbir dvije funkcije, zadat interval, A = 0, B = 0…) sajt prikazuje obavještenje sa razlogom i ne izmišlja rješenje.
- Pretpostavke: uglovi su u radijanima, kodomen arcctg je (0, π), a za sin, cos, tg i ctg koristi se standardni luk.

Sajt je jedan fajl (`index.html`), bez servera, i radi i na telefonu. Služi da provjeriš i razumiješ svoj postupak, a ne da ga zamijeni.
