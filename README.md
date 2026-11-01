# Neteja i anàlisi de dades d’una llibreria


## Fitxers

- **`05_llibreria.csv`**
  Dades originals proporcionades per a la pràctica.
  Es conserven sense modificar.

- **`AC4_Llibreria.ipynb`**
  Notebook amb l’exploració, la neteja, la validació i l’anàlisi.
  Inclou el codi executat, les comprovacions i les conclusions.

- **`registres_nets.csv`**
  Els 90 registres acceptats, amb els camps normalitzats.
  És el conjunt utilitzat per calcular els indicadors.

- **`incidencies.csv`**
  Detall de les 58 incidències: 49 motius de rebuig i 9 correccions.
  Inclou la fila d’origen, el camp, el valor original i l’acció.

- **`registres_rebutjats.csv`**
  Les 30 files rebutjades, amb els valors originals.
  El camp `fila_csv` permet consultar-ne els motius a `incidencies.csv`.

- **Presentació PowerPoint (`.pptx`)**
  Resum visual del procés, les decisions i els resultats,
  preparat per a l’exposició oral.

- **Dossier de preparació (`.pdf`)**
  Guió amb les respostes als vuit apartats de l’exposició,
  exemples i referències al notebook.

## Execució

1. Tenir Python 3 i un entorn per executar notebooks, com Jupyter
   o VS Code amb les extensions Python i Jupyter.
2. Mantenir `05_llibreria.csv` a la mateixa carpeta que el notebook.
3. Obrir `AC4_Llibreria.ipynb` i executar les cel·les de dalt a baix.

El codi utilitza només la biblioteca estàndard de Python.
L’exportació genera els tres CSV de resultats i substitueix
les versions anteriors, sense modificar el CSV original.

## Abast

Les conclusions descriuen els registres acceptats segons les
regles aplicades. El fitxer no especifica si els exemplars són
vendes, estoc o altres operacions.

## Autores

Zoya Ahmed i Sana Sabir .