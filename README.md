# Sinterklaas lootjes

Lootjes trekken voor het gezin. Eén statische pagina (`index.html`), geen server, geen accounts.

## Zo werkt het

1. De organisator vult de namen in, plus eventueel wie elkaar niet mag trekken, een budget en de datum.
2. "Trek de lootjes" maakt voor iedereen een persoonlijke link.
3. Stuur elke link door (kopiëren of WhatsApp). Wie de link opent ziet alleen zijn eigen lootje.

## Goed om te weten

- Het lootje zit verhuld in de link zelf. Dat houdt nieuwsgierige ogen tegen, maar het is geen echte versleuteling.
- De organisator ziet de uitslag niet, zolang die de links van anderen niet opent.
- Namen en links worden alleen in de browser van de organisator bewaard (localStorage).

## Lokaal draaien

Open `index.html` in een browser, of:

```bash
python3 -m http.server 8000
```

## Online zetten

GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root.
