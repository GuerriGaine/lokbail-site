# lokbail.fr

Site statique de Lokbail (fiche coloc + tirage au sort de 3 cartes cadeaux de 50 €, 15/10 → 14/11/2026, tirage le 15/11/2026).

- `index.html` : page principale et formulaire (envoie les fiches à la fonction Supabase `formulaire`)
- `reglement.html` : règlement du tirage au sort
- `mentions-legales.html` : mentions légales
- `.htaccess` : HTTPS, domaine sans www, adresses courtes `/reglement` et `/mentions-legales`

Publié avec GitHub Pages (branche `main`, dossier racine) sur le domaine lokbail.fr (fichier `CNAME`). `404.html` = copie de `index.html` pour que les liens cassés mènent à la fiche. Le `.htaccess` ne sert que si le site est remis sur un hébergement Apache (OVH).
