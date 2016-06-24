---
name: API Prélèvements sociaux
tagline: Estimer le coût d'embauche en France
doc_tech: https://embauche.beta.gouv.fr/api-prelevements-sociaux.html
domain: https://embauche.beta.gouv.fr
contract: OUVERT
experimentale: true
clients:
  - Entreprises
  - Administrations
  - Associations
owner: DINSIC
category: simulation
keywords:
  - coût d'embauche
  - fiches de paie
  - cotisations sociales
  - contributions sociales
  - aides à l'emploi
  - salaire net
  - salaire brut
---

Permet l'estimation rapide et précise du coût d'une embauche en fonction du contexte de l'entreprise et du salarié : salaire, type de contrat de travail (CDD, CDI, interim, indépendant ...), temps partiel, activité, géographie, taille... Vous obtiendrez précisément le décompte des cotisations salariales et patronales dans ce contexte. Par exemple, deux requêtes identiques mais avec des codes postaux différents pourra produire deux résultats distincs car le taux du versement transport n'y est pas forcément le même.
