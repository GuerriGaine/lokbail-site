# lokbail.fr

Site statique de Lokbail (fiche coloc + tirage au sort de 3 cartes cadeaux de 50 €, 15/10 → 14/11/2026, tirage le 15/11/2026).

- `index.html` : page principale et formulaire (envoie les fiches à la fonction Supabase `formulaire`)
- `reglement.html` : règlement du tirage au sort
- `mentions-legales.html` : mentions légales
- `.htaccess` : HTTPS, domaine sans www, adresses courtes `/reglement` et `/mentions-legales`

Déployé sur l'hébergement web OVH de lokbail.fr via « Associer Git » (branche `main`).
