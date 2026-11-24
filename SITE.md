# Capose : site web (capose.net)

`index.html` présente l’application Capose, avec des captures réelles de l’app dans `assets/`. `support.html`, `privacy.html` et `terms.html` sont les pages légales liées depuis l’App Store. Le domaine est capose.net ; cap200.net redirige vers lui (règle de redirection Cloudflare).

Un projet Sites privé a été enregistré : `appgprj_6ab19ac159008191a2565d83b7ce617a`. Aucune version n’a été déployée, l’outil Sites ayant été retiré de l’environnement pendant la tâche. Si Sites est reconnecté, réutiliser cet identifiant, sans créer un autre projet.

La source de travail initiale et le manifeste sont dans le dossier local `landing/`, ignoré par Git. La copie livrée dans ce dossier `website/` est enregistrée dans GitHub.

Aperçu local :

```sh
python3 -m http.server 4173 --directory website
```
