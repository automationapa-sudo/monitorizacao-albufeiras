# Monitorização de Albufeiras — ARH Alentejo

Mapa e painel com os níveis de armazenamento das albufeiras das regiões hidrográficas
RH6 (Sado e Mira) e RH7 (Guadiana). Os dados são lidos em tempo real de uma API
(Google Apps Script) e atualizados automaticamente a cada 30 minutos.

## Ficheiros

- `index.html` — a página (HTML, CSS e JavaScript num só ficheiro)
- `geo/rh6_rh7.js` — limites das regiões hidrográficas RH6 e RH7

## Fontes de dados

- Limites das regiões hidrográficas: SNIAmb / Agência Portuguesa do Ambiente —
  [Regiões hidrográficas de Portugal continental](https://dados.gov.pt/en/datasets/regioes-hidrograficas-de-portugal-continental-conjunto-de-dados-geografico-sniamb-2),
  licença CC BY 4.0 (dados de 17/10/2026, sem simplificação).
- Mapas base: Esri, © OpenStreetMap.
