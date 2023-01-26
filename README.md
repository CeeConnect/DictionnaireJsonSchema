# @CeeConnect - Dictionnaire JSON Schema

⚠️ Développement en cours

## Spécification

### Utilisation

```
{
    "$id": "https://example.com/schema",
    "$schema": "https://raw.githubusercontent.com/CeeConnect/json-schema-draft/main/meta-schema.json"
}
```

## Répertoire

### Arborescence

- **type**: Schémas incrustables
    - **common**: Propriétés communes
    - **\[secteur]**: Subdivision par secteur d'application des fiches d'opération standardisée
        - **\[scope]**: Subdivision par périmètre de la donnée
- **bundle**: Schémas composés
    - **controle**: Schémas applicables aux contrôles des opérations standardisées
        - **\[secteur]**: Subdivision par secteur d'application des fiches d'opération standardisée
    - **dossier**: Schémas applicables aux attestations sur l'honneur et pièces justificatives
        - **partie-a**: Schémas applicables aux parties A des attestations sur l'honneur
            - **\[secteur]**: Subdivision par secteur d'application des fiches d'opération standardisée
    - **fiche**: Schémas applicables aux calcules des volumes de CEE délivrables par opération standardisée
        - **\[secteur]**: Subdivision par secteur d'application des fiches d'opération standardisée

### Référence

- [Draft 2020-12](https://json-schema.org/draft/2020-12/schema)
