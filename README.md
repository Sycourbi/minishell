# Minishell
![C Language](https://img.shields.io/badge/language-C-blue)
![Shell Implementation](https://img.shields.io/badge/shell-minishell-blue)
![Features](https://img.shields.io/badge/features-Redirection%20%7C%20Pipes%20%7C%20Jobs-yellow)
![42](https://img.shields.io/badge/school-42-green)
![42 Paris](https://img.shields.io/badge/42-Paris-blue)

## Description

Bienvenue sur le dépôt du projet Minishell de l'École 42. Ce projet consiste à recréer un shell minimaliste similaire à Bash, capable d'exécuter des commandes simples comme celles trouvées dans un vrai shell Unix.


## Badge et Note Obtenu

<div align="center">
  <img src="https://github.com/ayogun/42-project-badges/blob/main/badges/minishelle.png?raw=true" alt="Badge du projet minishell">
</div>

### Fonctionnalités

- Interprétation et exécution de commandes Unix standard.
- Commandes internes : `echo`, `cd`, `env`, `export`, `unset`, `pwd`, `exit`.
- Commandes externes via `execve`.
- Gestion des variables d'environnement.
- Gestion des chemins (`PATH`).
- Support des redirections (`>`, `<`, `2>`).
- Support des pipes (`|`).
- Expansion des variables avec `$` et `~`.
- Gestion des signaux Unix : `Ctrl+C` (SIGINT) et `Ctrl+\` (SIGQUIT).

## Installation

Pour installer le projet Minishell, suivez ces étapes :

1. Clonez le dépôt :

   ```bash
   git clone https://github.com/Sycourbi/minishell.git
   cd minishell
   make
   ./minishell

