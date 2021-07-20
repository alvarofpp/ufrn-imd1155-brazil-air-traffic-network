# Brazil air traffic network
This work has as purpose to analyze the air traffic in Brazil.

Work of undergraduate course about Network Analysis (IMD1155) of Bachelor's degree in Information Technology from the Federal University of Rio Grande do Norte (UFRN), with [Ivanovitch Medeiros Dantas da Silva](https://github.com/ivanovitchm) as professor.

Group:
- [Álvaro Ferreira Pires de Paiva](https://github.com/alvarofpp)
  - Enrolment: 2016039162
  - E-mail: alvarofepipa@gmail.com
- [Marcos Vinícius Rêgo Freire](https://github.com/mvinnicius22)
  - Enrolment: 20210053533
  - E-mail: mvinnicius22@hotmail.com

## Dataset
The dataset used in this work originates from 3 other datasets:

- [Flights in Brazil by ANAC](https://github.com/alvarofpp/dataset-flights-brazil).
- [List of public aerodromes by ANAC](https://www.anac.gov.br/acesso-a-informacao/dados-abertos/areas-de-atuacao/aerodromos/lista-de-aerodromos-publicos-v2).
- [Airport Codes by DataHub.io](https://datahub.io/core/airport-codes) (note: we notice that the latitude and longitude columns have their values swapped).

After merging the datasets, we use [geocoder](https://github.com/DenisCarriere/geocoder) package to fill in the empty values. You can find the final CSV in [`data/airports.csv`](data/airports.csv).
