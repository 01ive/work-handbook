# 📋 Gestion des actions

Cette méthode permet de capturer, prioriser et suivre les actions professionnelles et personnelles. Elle complète la [gestion des mails](./mails.md) : toute action qui ne peut pas être traitée immédiatement est transférée dans la liste des actions, afin de libérer la boîte de réception.

---

## 🎯 Méthode

L'organisation s'appuie sur une liste d'actions structurée, inspirée de la méthode Kanban. Chaque action est décrite en identifiant, si possible, les éléments suivants :
* ✏️ sa description par une phrase synthétique
* *@* la personne chargée de l'action
* 📅 la date d'échéance de l'action
* *#* une catégorie libre
* ⏱️ la charge de travail estimée
* ⏳ la charge de travail réalisée
* ✅ son état : ouvert, en cours, bloqué ou clos
* 🔴 sa priorité

Lors de la création d'une action, il est possible de ne pas disposer de toutes ces informations. Nous pouvons les compléter au fur et à mesure, au moment où l'on traite l'action.

### 📥 Capturer les actions

Les actions peuvent provenir de différentes sources :
* Réunions : comptes rendus, décisions et suivis.
* Mails : demandes et suivis qui nécessitent plus de 2 minutes (voir [traitement des mails](./mails.md)).
* Idées spontanées : elles peuvent être identifiées à l'aide de l'émoji `💡`.
* Demandes diverses et variées.

### Classer les actions

Je classe les actions selon cinq catégories :

* 📦 **Backlog** : pour noter toutes les actions et idées. Elles ne comportent bien souvent qu'une description et une date lointaine.
* 📝 **Todo** : pour regrouper au maximum une dizaine d'actions à traiter dans les semaines à venir (à échéance proche). Lors du passage du backlog à Todo, j'en profite souvent pour affiner la date de réalisation et ajouter une charge ainsi qu'une priorité.
* 🎯 **Today** : regroupe les tâches que je dois réaliser aujourd'hui. Je note le temps passé en fin de journée et les clos si besoin.
* ⏳ **Standby** : pour les tâches bloquées, qui nécessitent que j'y revienne plus tard, lorsque j'aurai les informations attendues.
* ✅ **Done** : pour les tâches achevées.

### ✅ Clore les actions

Il est important de clore les actions une fois celles-ci réalisées et d'en garder une trace. Cela procure un sentiment de satisfaction indispensable au moment de la clôture et vous fait prendre conscience que vous avancez dans vos activités lorsque vous observez l'ensemble du travail effectué.

### 🧘‍♂️ Préparer votre journée la veille

À la fin de votre journée de travail, il est important de compléter votre liste d'actions avec toutes les nouvelles actions de la journée et de planifier celles que vous traiterez le lendemain. Cela vous libérera l'esprit et vous évitera toute angoisse d'oublier des actions pendant la nuit.

---

## 🛠️ Outils

Comme décrit dans la méthode de [gestion des mails](./mails.md), les tâches prenant plus de 2 minutes peuvent être marquées, classées et regroupées dans une vue d'Outlook. La gestion des tâches sous Outlook ne me convient pas et j'ai essayé des outils alternatifs comme le très bon [Task Coach](https://taskcoach.org/), mais j'ai développé ma propre solution afin de répondre parfaitement à mes besoins.

En tant que développeur, j'ai toujours **VS Code** ouvert. J'ai donc développé une solution [My todo](https://github.com/01ive/my-todo-md) s'appuyant sur cet IDE, qui me permet :
* d'utiliser du texte brut au format **Markdown**, afin que les données restent exploitables avec un simple éditeur ;
* de gérer la configuration sous **Git** ;
* de connecter un **agent IA** comme Copilot avec [My todo MCP](https://github.com/01ive/my-todo-mcp-server) ;
* de proposer une vue **Kanban** simple et interactive ;
* de visualiser les tâches dans un planning de type **Gantt** ;
* d'ajouter et de modifier **rapidement** les tâches ;
* de mettre en avant certaines **catégories** d'actions.

### My todo

Extension VS Code permettant d'afficher le markdown en **Kanban** et **Gantt**.

https://github.com/01ive/my-todo-md


### My todo MCP server pour agent IA

Serveur MCP permettant à un **agent IA** d'interagir avec une liste de tâches au format My todo.

https://github.com/01ive/my-todo-mcp-server
