# hsbo-brand

Quarto-Brand der Hochschule Bochum nach dem
[Corporate-Design-Handbuch](https://www.hochschule-bochum.de/meinebo/intranet/corporate-design-handbuch/grundlage/)
(Intranet). Passt zu den Extensions aus [quarto-tinh](https://github.com/matthiasbaitsch/quarto-tinh), die nur
Layout und Stil enthalten.

- **Logo:** `small` ist die Bildmarke BO, `medium` das Logo im Querformat, `large` im Hochformat, jeweils mit
  weißer Fassung für dunkle Hintergründe. Die SVGs in `logos/` sind unverändert aus dem Download der Hochschule
  (Logos_2025, RGB); das Handbuch erlaubt nur die Verwendung in unveränderter Form.
- **Farben:** `primary` ist BO Rot (`#E2001A`), die Bereichsfarben stehen in der Palette, z. B. `bauingenieurwesen`.
- **Schriften:** keine. Die Hausschriften (BO Regular, BO Antiqua, BO Display) gibt es nur auf Anfrage, im Web nimmt
  die Hochschule Arial.

## Einbinden

Im Projektverzeichnis:

```bash
quarto use brand matthiasbaitsch/hsbo-brand
```

Quarto kopiert `_brand.yml` und die Dateien, auf die sie verweist, nach `_brand/` im Projekt. Aktualisieren mit
demselben Befehl.
