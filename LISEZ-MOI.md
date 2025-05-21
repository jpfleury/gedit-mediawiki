**Note: ce fichier de coloration syntaxique est maintenant [inclus dans GtkSourceView](https://github.com/GNOME/gtksourceview/commit/db965e3ac704c574d04023606d4b7afc4ec133ad) à partir de la version 3.9.2.**

## Aperçu

gedit-mediawiki ajoute la coloration syntaxique de la [syntaxe MediaWiki](http://meta.wikimedia.org/wiki/Aide:Syntaxe_wiki) dans gedit, l'éditeur de texte par défaut de GNOME.

Voici une capture d'écran:

<img src="https://raw.githubusercontent.com/jpfleury/gedit-mediawiki/master/doc/exemple1.png" width="685" height="1112" alt="Coloration syntaxique pour la syntaxe MediaWiki dans gedit." />

## Installation

- [Télécharger l'archive de la dernière version.](https://github.com/jpfleury/gedit-mediawiki/archive/master.zip)

- Extraire l'archive.

- Copier le fichier `mediawiki.lang` dans le dossier approprié (créer le dossier s'il n'existe pas):

	- pour gedit 2: `~/.local/share/gtksourceview-2.0/language-specs/`
	- pour gedit 3: `~/.local/share/gtksourceview-3.0/language-specs/`

La coloration syntaxique de la syntaxe MediaWiki sera ajoutée à l'utilisateur courant (l'installation se fait donc sans les droits d'administration). Le dossier créé par l'extraction de l'archive peut être supprimé après l'installation.

## Désinstallation

Supprimer le fichier précédemment installé.

## Utilisation

Avant toute chose, redémarrer gedit s'il est ouvert.

Choisir la coloration en allant dans le menu *Affichage > Mode de coloration > Autres* de gedit et en cochant *MediaWiki*.

Un fichier démo se trouve dans le dossier `doc` de gedit-mediawiki.

## Développement

Le logiciel Git est utilisé pour la gestion de versions. [Le dépôt peut être consulté en ligne ou récupéré en local.](https://github.com/jpfleury/gedit-mediawiki)

## Licence

Auteur: Jean-Philippe Fleury (<https://github.com/jpfleury>)  
Copyright © Jean-Philippe Fleury, 2009.

Ce programme est un logiciel libre; vous pouvez le redistribuer ou
le modifier suivant les termes de la GNU Lesser General Public License telle
que publiée par la Free Software Foundation: soit la version 2.1 de la
License, soit (à votre gré) toute version ultérieure.

Ce programme est distribué dans l'espoir qu'il sera utile, mais
SANS AUCUNE GARANTIE: sans même la garantie implicite de
COMMERCIALISABILITÉ ou d'ADÉQUATION À UN OBJECTIF PARTICULIER. Consultez
la Licence publique générale limitée GNU pour plus de détails.

Vous devriez avoir reçu une copie de la Licence publique générale limitée GNU
avec ce programme; si ce n'est pas le cas, écrivez à la:
Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston,
MA 02110-1301, USA.
