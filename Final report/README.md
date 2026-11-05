# PtX – Final report (DTU kursus 47211)

Kode og data til vores Power-to-X (PtX) slutrapport.

## Indhold
| Fil | Beskrivelse |
|---|---|
| `Data_analyse.ipynb` | Hovednotebook: indlæser timedata for el-produktion/-forbrug (DK1 + DK2), skalerer vind og sol op til fremtidigt scenarie og beregner overskudsstrøm til PtX |
| `ProductionConsumptionSettlement.csv` | Rådata fra Energinet (Energi Data Service), timeopløsning |
| `Figure1_production_consumption_prosumption.png` | Figur 1 til rapporten |

## Kom i gang
```bash
pip install -r requirements.txt
jupyter notebook Data_analyse.ipynb
```

## Sådan arbejder vi sammen
1. **Pull** altid før du starter (hent de andres ændringer).
2. Lav en **branch** til din opgave, fx `elektrolyse-beregning`.
3. **Commit** ofte med en kort besked om hvad du har lavet.
4. **Push** og lav en **Pull Request** på GitHub, så en anden kan kigge på det før det merges ind i `main`.
5. Undgå at to personer redigerer samme notebook samtidig – notebooks er svære at flette. Del hellere op i flere notebooks.
