# 📥 Gestion des mails

Présentation d'une méthode de gestion des mails, facile et rapide, permettant de garder une boîte de réception (*Inbox*) vide.

Le présent document détaille dans un premier temps la méthodologie à mettre en place, puis dans un second temps, les outils supportant son déploiement.

---

## 🎯 Méthode

Les principaux éléments présentés ci-dessous sont issus de la méthode GTD, décrite dans le best-seller *« Getting Things Done »* de David Allen (publié en 2001, traduit en 2004). L'objectif principal est d'obtenir une boîte vide (*Inbox Zero*) avec un minimum d'effort. En effet, une boîte pleine peut donner le sentiment d'affronter une « montagne » de travail, générant stress et démotivation. Tout message lu (qu'il soit traité ou non) doit donc être immédiatement retiré de l'Inbox.

### 🗂️ Les types de mails

Les mails reçus se répartissent en 2 grandes catégories :
* Les mails d'**information**, que l'on peut qualifier de « jetables » ou « à conserver » sur le long terme.
* Les mails d'**action**, qui se séparent en 2 cas : les actions rapides (moins de 2 minutes) et les actions longues.

On obtient ainsi quatre grands types de mails :
* 🗑️ Mail d'**information jetable**
* 📁 Mail d'**information à conserver**
* ⚡ Mail d'**action rapide (< 2 min)**
* ⏳ Mail d'**action longue (> 2 min)**

Il est indispensable de limiter le nombre de catégories afin de contenir l'effort cognitif et le temps consacré au tri.

> ⏱️ **La règle des 2 minutes (principe GTD)**  
> Tout mail dont le traitement (lecture/décision ou action) prend moins de 2 minutes doit être traité **immédiatement**. Un mail demandant plus de 2 minutes est traité en dehors du temps de tri (il est donc mis de côté pour un traitement ultérieur en [todo](./todo.md)).

### 🚦 Priorité des mails

Avant même d'ouvrir un message, il est possible d'évaluer son niveau de priorité à partir de son expéditeur et de ses destinataires.  
Pour l'expéditeur, la hiérarchie est souvent directe : une annonce du club café sera naturellement moins prioritaire qu'un mail du chef de projet sur lequel vous intervenez.

On peut donc définir, par exemple, les priorités suivantes selon l'**expéditeur** :
* 🔴 Mails de mes responsables
* 🟢 Mails de mon équipe
* ⚪ Autres messages

Concernant les **destinataires**, un message où vous apparaissez en copie carbone (`Cc`) est généralement moins urgent qu'un message dont vous êtes le destinataire direct (`À`).

Exemple de niveaux de priorité selon les destinataires :
* 🎯 Seul destinataire principal (`À`)
* 👥 Destinataire principal parmi d'autres (`À`)
* 📑 En copie (`Cc`)  
  *(À noter : la copie cachée / `Cci` doit être traitée avec le même niveau d'attention qu'un destinataire principal).*

### 🔕 Gérer les interruptions

Pour préserver la concentration, la productivité et limiter le stress, il est fortement conseillé de ne pas subir les interruptions constantes des notifications de sa boite mail.

* Désactiver l'ensemble des alertes visuelles (bannières, pop-ups) et sonores du client mail.
* Définir des plages horaires dédiées au traitement des messages (par exemple 2 sessions par jour : en début de matinée et en début d'après-midi).
* Si possible, garder le client mail fermé en dehors de ces créneaux.

---

## 🛠️ Outils

La configuration du client de messagerie permet d'accélérer le dépilage et le tri tout en offrant des repères visuels clairs (à la manière d'une carte heuristique).

Les configurations décrites ci-dessous s'appuient sur **Microsoft Outlook**, mais restent transposables à d'autres outils (Thunderbird, Apple Mail, etc.).

### 🎨 Coloration des mails par importance (mise en forme conditionnelle)

Le client peut modifier l'affichage des messages dans la liste selon l'expéditeur ou votre position dans les destinataires. Cela permet d'identifier la priorité d'un coup d'œil et, dans certains cas, d'archiver un message sans l'ouvrir.

Exemple de règles de mise en forme :
* Conserver les règles d'affichage par défaut.
* Mettre en évidence les personnes prioritaires : police **rouge** pour la hiérarchie, police **verte** pour l'équipe directe...
* Atténuer les messages où vous êtes en copie (`Cc`) : police **grise** discrète sur fond blanc.
* Distinguer les messages où vous êtes destinataire unique : police **soulignée** ou en gras.

### ⚡ Rangement rapide des mails (actions rapides & raccourcis)

Pour ranger les messages sans glisser-déposer manuel, il est utile de paramétrer des **Actions rapides** configurées pour déplacer directement le mail vers un sous-dossier, combinées à un raccourci clavier :

1. `Ctrl + Maj + 1` ➔ Travail projet 1
2. `Ctrl + Maj + 2` ➔ Travail projet 2
3. `Ctrl + Maj + 3` ➔ Travail projet 3
4. `Ctrl + Maj + 5` ➔ Métier
5. `Ctrl + Maj + 8` ➔ Perso
6. `Ctrl + Maj + 9` ➔ Admin

Le nombre restreint de raccourcis oblige à maintenir une arborescence courte et sobre. Cela évite les dossiers imbriqués à l'infini qui ralentissent le classement. Un moteur de recherche efficace associé à un bon étiquetage rend superflue la multiplication des répertoires.

### 🏷️ Catégories de classement (recherche accélérée)

L'attribution de catégories de couleurs aide à retrouver rapidement des éléments transverses ou récurrents :

* 🔴 **Rouge** : Important / Urgent
* 🟡 **Jaune** : Configuration & accès informatiques
* 🟣 **Violet** : Formation
* 🟠 **Orange** : Personnel

### 📌 Traiter les actions longues (> 2 minutes)

Les tâches de plus de 2 minutes ne pouvant être exécutées sur-le-champ, elles doivent être tracées tout en libérant la boîte de réception.

1. **Poser un indicateur de suivi** (drapeau) via une action rapide dédiée.
2. **Classer immédiatement** le mail dans son dossier de référence (l'Inbox reste ainsi vide).
3. **Consulter la vue dédiée** : créer un *Dossier de recherche personnalisé* (ex. : *« Actions »* ou *« Courrier avec indicateur de suivi »*).
4. Traiter ces actions lors d'un bloc de temps dédié (soit immédiatement après la session de tri, soit sur une plage réservée de l'agenda) avec méthode (voir [todo](./todo.md)).
5. Une fois l'action achevée, marquer l'indicateur comme **terminé** : le mail disparaît de la vue *Actions* sans nécessiter de nouveau rangement puisqu'il est déjà dans son dossier thématique.

---

## 📅 Gestion du calendrier

Cette même approche visuelle peut s'appliquer aux rendez-vous de l'agenda. Outlook permet de colorer automatiquement les événements selon leur organisateur ou leur objet.

Exemple de répartition des couleurs :
* 🔴 **Rouge** : Réunions importantes / hiérarchie
* 🟢 **Vert** : Points d'équipe
* 🟣 **Violet** : Formations
* 🟠 **Orange** : Personnel / privé (marquer comme « Privé » pour masquer le détail)
* 🔵 **Bleu** : Réunions que vous organisez

**Bonnes pratiques collaboratives :**
* ⏱️ Répondre le plus rapidement possible aux invitations reçues.
* 👁️ Partager la visibilité de son calendrier avec ses collègues (le statut privé masquant automatiquement les rendez-vous personnels, le reste facilite les créneaux partagés).
* 🔒 N'hésitez pas à marquer comme privées les réunions confidentielles ou personnelles. 
