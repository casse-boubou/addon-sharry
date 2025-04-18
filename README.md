# Home Assistant Add-on: Sharry

[![GitHub Release][releases-shield]][releases]
[![License][license-shield]](LICENSE)

![Supports aarch64 Architecture][aarch64-shield]

[Sharry][sharry] permet de partager des fichiers avec d'autres de manière
simple. C'est une application web auto-hébergé. Le concept de base est le
suivant : téléchargez des fichiers et récupérez une URL qui peut ensuite
être partagé.

[![Open your Home Assistant instance and show the add add-on repository dialog
with a specific repository URL pre-filled.][add-repo-shield]][add-repo]
[![Open your Home Assistant instance and show the dashboard of a Supervisor add-on.][add-addon-shield]][add-addon]

## About

Ce projet est un fork du projet original de [Mike Degatano][mike-degatano] auquel
j'ai rajouter la possibilitée de stocker les fichier directement dans un dossier
local ainsi que de copier la base de donnée de Mariadb à un stockage local ou inversement.

Cet add-on permet un partage de fichiers rapidement et facilement.
Vous glisser et déposez des fichiers et obtenez un lien que vous pouvez partager
avec n'importe qui.
Vous pouvez également créer et partager des liens avec d'autres personnes
qu'elles utiliseront pour partager des fichiers avec vous.
Toute personne disposant d'un lien de partage peut y accéder, mais seulement les
utilisateurs authentifiée peuvent créer de nouveaux liens de partage.
Les URL sont difficiles à deviner afin que les utilisateurs puissent en contrôler
qui y a accès.
Il a également quelques fonctionnalités intéressantes comme les téléchargements
de fichiers avec reprise et l'affichage de la galerie pour les photos et les
vidéos.

## Support

Je ne suis pas dévellopeur, n'ai aucune formation de code, je suis simplement
autodidact.
Si vous avez une question concernant HA et ses add-ons vous pouvez consulter:

- [Le Forum communautaire francophone][hacf] de HomeAssistant
- [Le Forum communautaire anglophone][forum] de HomeAssistant.
- [Le serveur Discord][discord-ha] de HomeAssistant.

## Authors & contributors

Ce projet est un fork du projet original de [Mike Degatano][mike-degatano].

Pour une liste complète des auteurs et contributeurs merci de consulter
la [page des contributeurs][contributors].

## License

MIT License

Copyright (c) 2022-2025 [Frosh][Frosh]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[add-addon]: https://my.home-assistant.io/redirect/supervisor_addon/?addon=c751e21a_sharry
[add-addon-shield]: https://my.home-assistant.io/badges/supervisor_addon.svg
[add-repo]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A//github.com/casse-boubou/hassio-addons
[add-repo-shield]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
[releases]: https://github.com/casse-boubou/addon-sharry/releases
[releases-shield]: https://img.shields.io/github/v/release/casse-boubou/addon-sharry
[license-shield]: https://img.shields.io/github/license/casse-boubou/addon-sharry
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[mike-degatano]: https://github.com/mdegat01/addon-sharry
[contributors]: https://github.com/mdegat01/addon-sharry/graphs/contributors
[sharry]: https://eikek.github.io/sharry/
[discord-ha]: https://discord.gg/c5DvZ4e
[forum]: https://community.home-assistant.io
[hacf]: https://forum.hacf.fr/
[Frosh]: https://github.com/casse-boubou
