# Merise

L'objectif de ce document est de permettre une compréhension plus facile de Merise. C'est surtout une prise de note en suivant l'odre des dailies.

## Niveaux dans Merise

<table><thead>
  <tr>
    <th width=5000></th>
    <th width=5000>Données</th>
    <th width=5000>Traitements</th>
    <th width=5000>Communication</th>
  </tr></thead>
<tbody>
  <tr>
    <th align=right>Conceptuel</th>
    <td align=center>MCD</td>
    <td align=center>MCT</td>
    <td align=center>MCC</td>
  </tr>
  <tr>
    <th align=right>Organisationel</th>
    <td align=center>MLD</td>
    <td align=center>MOT</td>
    <td align=center></td>
  </tr>
  <tr>
    <th align=right>Technique</th>
    <td align=center>MPD</td>
    <td align=center>MOpT</td>
    <td align=center></td>
  </tr>
</tbody>
</table>

## Dépendaces fonctionnelles

- dépendance multi-valuée : information prenant plus d'une valeur dans la table
- dépendance élémentaire : information dépendant uniquement de la clé primaire d'une table
- dépendance transitive : information dépendant d'une information non clé d'une table

## Formes normales

- Première forme normale (1FN) : élimination des dépendaces multi-valuées
- Deuxième forme normale (2FN) : élimination des dépendances non élémentaires
- Troisième forme normale (3FN) : élimination des dépendances transitives
