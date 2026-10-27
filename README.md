# Valdemars LEGO-samling

Hjemmesiden på https://lego.mbiegel.dk bygges automatisk ud fra `Legosamling.xlsx` i OneDrive.

- `index.html` – siden (genereres, ret ikke i hånden)
- `img/` – produktbilleder (genereres)
- `_vaerktoej/skabelon.html` – designet; `__SETS__` og `__DATO__` udfyldes
- `_vaerktoej/byg_side.py` – bygger siden: `python3 _vaerktoej/byg_side.py <Legosamling.xlsx> <Produktbilleder-mappe> .`
