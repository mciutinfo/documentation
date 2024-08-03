# Website

Cette documentation a été créée à l'aide de [Docusaurus](https://docusaurus.io/).

### Téléchargement

```bash
git clone https://github.com/mciutinfo/documentation
```

### Build

```bash
cd documentation
npm run build
```

Le site est généré dans le dossier `build`. Le site est statique et ne nécessite pas de serveur pour être consulté.

### Deployment

Pour le déployer à l'aider d'un server serve (NPM) :

```bash
npm run serve -- --build --port 80 --host 0.0.0.0
```


### Tout d'un coup ?

```bash
git clone https://github.com/mciutinfo/documentation
cd documentation
rm -rf build # Supprime le dossier build s'il existe
npm run build
cd build
npm run serve -- --build --port 80 --host
```