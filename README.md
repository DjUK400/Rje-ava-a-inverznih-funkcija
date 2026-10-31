# Rješavač inverznih funkcija

**Sajt:** https://djuk400.github.io/Rje-ava-a-inverznih-funkcija/

Rješavač za 1. zadatak kolokvijuma iz matematike: *"Skicirati datu funkciju, te odrediti i skicirati inverznu funkciju."* Radi za arcus funkcije oblika **f(x) = A·g(Bx + C) + D**, gdje je g arcsin, arccos, arctg ili arcctg.

## Šta radi

- **Rješavač:** upišeš funkciju, npr. `2arcsin(3x − 1) + π/4`. Dobiješ redom domen, kodomen, monotonost, karakteristične tačke, skicu kroz 5 koraka transformacije, izvođenje inverza, skicu f⁻¹ i zajednički grafik f i f⁻¹ sa pravom y = x.
- **Objašnjenja:** svako uprošćavanje je napisano eksplicitno (polazni izraz → pravilo → rezultat), a dugme "Zašto?" objašnjava razlog za svaki korak.
- **Vježba:** nasumični zadaci sa gotovim graficima. Postupak se otvara na klik.
- **Osnovna pravila:** grafici četiri arcus funkcije, transformacije grafika, identiteti, nejednakosti i česte greške.

## Pouzdanost

- Sve se računa tačno, sa razlomcima i višekratnicima π.
- Svaki inverz se automatski provjerava na 800 tačaka. Ako provjera ne prođe, rezultat se ne prikazuje.
- Za nepodržan unos (sin, ln, x van arcusa, x², zbir dvije arcus funkcije, A = 0, B = 0…) sajt prikazuje obavještenje sa razlogom i ne izmišlja rješenje.
- Pretpostavke: uglovi su u radijanima, a kodomen arcctg je (0, π).

Sajt je jedan fajl (`index.html`), bez servera, i radi i na telefonu. Služi da provjeriš i razumiješ svoj postupak, a ne da ga zamijeni.
