# LUC BRICO-TECH — V3

Application web de gestion et supervision.

## Modules
- Tableau de bord
- Membres et rôles
- Ventes
- Achats
- Dépenses
- Stock et matériel
- Activités / interventions
- Projets
- Innovations
- Rapports
- Journal d'activité
- Paramètres
- Connexion Supabase
- Mode démo local

## Lancer
Ouvrir `login.html` avec Live Server dans VS Code.

## Production
Configurer Supabase avec `supabase/schema.sql`, puis renseigner `config.js`.
Déployer ensuite le dossier sur Vercel.

## Important
La version fournie contient le socle complet de l'interface et de la sécurité Supabase. Les opérations cloud sont activées progressivement par le module de synchronisation de `script.js`. Ne jamais exposer une clé `service_role`.


## Identité visuelle
La page d’accueil utilise le logo LUC BRICO-TECH et une identité bleu nuit / bleu technique / doré pour éviter l’aspect blanc et neutre.
