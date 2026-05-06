# Gabarit-MyST-PolyMTL
Gabarit pour la template MyST book-theme aux couleurs de Polytechnique Montréal

Pour utiliser le gabarit, il faut copier les fichiers et le dossier "images" à la racine du livre MyST.
Ensuite, il faut le déclarer comme suit dans myst.yml existant :

```{code} yaml
:filename: myst.yml
site:
  template: book-theme
  options:
     favicon: favicon.ico
     logo: ./images/site_logo.png
     logo_dark: ./images/site_logo_dark.png
     style: poly.css
```

