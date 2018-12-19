# Rust-Cookbook
CookBook de l'élec soft du Club Robot

# Contribution

Ce répertoire est ouvert à ***TOUTES*** les contributions, alors si tu vois des erreurs, des fautes ou des choses à corriger n'hésite surtout pas et fais un commit.

Si jamais tu ne sais pas utiliser `git` ce n'est pas grave, tu peut toujours utiliser l'interface en ligne de github ! :smile:

Un robot s'occupera de mettre à jour le cookbook à chaque commit sur la branche master.

Pour prévisualiser ses changements il faut commencer par installer `mdbook`.

Il faut commencer par installer Rust si tu ne l'as pas déjà. Je te laisse suivre les instructions sur la page de [rustup](https://rustup.rs/).

Ensuite, on peut installer `mdbook`. La compilation va prendre du temps, pas d'inquiétude, c'est normal.

```bash
cargo install mdbook
```

On peut maintenant clone le repo :

```bash
git clone https://jesaispasoutemettre
```

Une fois cloné, il faut lancer mdbook :

```bash
cd doc
mdbook serve
```

## [Guide pour se servir de mdbook](https://rust-lang-nursery.github.io/mdBook/)

Il est recommandé de lire le [guide de l'utilisateur](https://rust-lang-nursery.github.io/mdBook/) de mdbook avant de faire des changements pour bien comprendre ce que l'on fait.
