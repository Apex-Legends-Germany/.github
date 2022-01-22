# **Apex Legends Germany Bot Commands** <img src="https://cdn.discordapp.com/emojis/819317534453006366.gif?size=96" height="30px"> 
<a href="https://discord.gg/apexlegendsgermany"><img src="https://img.shields.io/discord/542304652381782016.svg?style=flat&label=Apex%20Legends%20Germany&color=EB144C" alt="ALG Badge"/></a>

## **Überischt:**
- **Kategorien:**<br>
    - [Was ist Slash?](#slash-commands-)
    <!--- [Automatische Voice-Channel]()  Soon -->
    - [Slash im Voice-Chanel](#befehle-innerhalb-der-temporären-channel-)
    - [Slash außerhalb temp channel](#befehle-außerhalb-der-vocie-channel-)
    - [Moderation mit Slash](#moderation-mit-slash-)
    - [Moderation mit Slash (Verwendung)](#moderation-mit-slash--1)
    - [Unser Ticketsystem](#unser-ticketsystem-)
    - [Verwendung und Beispiele](#anwendung-und-bespiele-)
---
<br>

## **Slash-Commands?**<p> <!-- Einleitung -->
**Was sind Slash Commands eigentlich?**<br>
Slash Commands sind eine direkte Interaktion mit dem Bot.<p>
**Was ist der Unterschied zwischen Slash-Command und `.` oder `vc/` ?**<br>
Es ist im Prinzip ganz einfach: `.` und `vc/` sind Zeichen auf die der Bot immer hört und in *fast* jedem Channel darauf achtet. Mit Slash-Commands sprichst du ein Bot direkt an und er führt dann den entsprechenden Befehl aus. Es gibt somit keine Verzögerung zwischen dem Lesen der Nachricht und der Ausführung des Befehls.<p>

---
<br>


## **Befehle innerhalb der temporären Channel: <img src="https://cdn.discordapp.com/emojis/919240209265225790.png?size=96" height="18">**<br>
<!-- Slashs für Nutzer -->
*Diese Befehle kann jeder User benutzen*<br>
[Mehr Information über diese Befehle.](#slash-befehle-innerhalb-der-temporären-channel)
- /channel bitrate<br>
- /channel info<br>
- /channel kick<br>
- /channel limit<br>
- /channel name<br>
- /channel unlimit<br>
- /channel privte<br>
- /channel public<br>
- /channel transfer<br>
- /lfg<br>

---
[Hier gehts zum Anfang](#apex-legends-germany-bot-commands-)<br><br>

## **Befehle Außerhalb der Voice-Channel:** <img src="https://cdn.discordapp.com/emojis/919244135779688549.png?size=96" height=18><br>
*Befehle welche von jedem genutzt werden können und man in keinem Voice-Channel sein muss.*<br>
[Mehr Information über diese Befehle.](#slash-befehle-außerhalb-der-temporären-channel)
- /all
- /tags
- /timestamp
- /ping

---
<br>


<!-- Slashs für Moderation -->
## **Moderation mit Slash: 🔨**<br>
*Alle Befehle welche hier Aufgelistet sind, stehen nur Moderatoren zur Verfügung. Diese Befehle werden nur im [BOT-Channel](https://canary.discord.com/channels/542304652381782016/787743729275633726) ausgeführt!*<br>
[Mehr Information über diese Befehle.](#moderation-mit-slash--1)
- /ban
- /scamban
- /unban
- /kick
- /modlog
- /note
- /warn
- /mute
- /unmute
- /user
- /role

---
[Hier gehts zum Anfang](#apex-legends-germany-bot-commands-)<br><br>
### **Normale Befehle:**<br>
<!-- Normale Commands für Mods -->
*Diese normalen Befehle geben ein Embed aus und deine Nachricht welche den Befehl auslöst wird direkt gelöscht. Diese Befehle sind hilfreich um in Tickets immer mit der gleichen Nachricht zu antworten.*<br>
[Mehr Information über diese Befehle.](#nomale-befehle)
- %18<br>
- %expert<br>
- %nexttry<br>
- %nickname<br>
- %scam<br>
- %sup<br>
- %supporttime<br>
- %ticktsystem<br>
---
<br>
<br>

## **Unser Ticketsystem** 🎫<br>
<!-- Commands für das Ticketsystem -->
*Befehle für das Ticketsystem. Wir empfehlen die Benutzung der Buttons*
- `$new` - Erstellt ein Ticket mit einem Nutzer zusammen.<br>
- `$close` - Schließt das Ticket.<br>
- `$add @user` - Füge einen Nutzer zu einem Ticket hinzu.<br> 
- `$remove @user` - Entferne einen Nutzer oder Rolle von einem Ticket.<br>
- `$transcript` - Erstellt ein HTML-Script im [ticketsystem-logs-etc](https://discord.com/channels/542304652381782016/917075476135174234) channel.<br>
- `$delete` - Löscht das Ticket (Nur mit Senior oder Head möglich).<br>
- `$rename name` - Ändert den Namen eines Tickets.<p>
---
---
[Hier gehts zum Anfang](#apex-legends-germany-bot-commands-)<br><br>
<br> 


##  **Anwendung und Bespiele: <img src="https://cdn.discordapp.com/emojis/919267633151492099.gif?size=96" height=25>**
<!-- Anwendung der Befehle und entspr. Beispiele -->
### **Slash-Befehle innerhalb der temporären Channel:**
*Hier findest du alle Befehle, deren Anwendung und entspr. Beispiele.*
* `/channel bitrate`
    * Stelle eine Serverweite Bitrate für dich ein. Jedes Mal, wenn du einen Channel eröffnest wird deine persönliche Bitrate auf den Channel angewandt.<br>
    Haben mehrere Nutzer in deinem Channel eine eigne Bitrate wird der Durchschnitt der Bitrates genommen und gesetzt.<br>
    **Verwendung:**<br>
    [`/channel bitrate bitrate:150`](https://i.imgur.com/8hq41Ea.png)<p>
* `/channel info`
    * Bekomme eine Information über deinen Channel in welchem du dich aktuell befindest.<br>
    **Verwendung:**<br>
    [`/channel info`](https://i.imgur.com/QnbCxAU.png)<p>
* `/channel kick`
    * Du möchtest jemanden aus deinem Channel kicken? Dann hiermit!<br>
    Nach [ausführung des Befehls](https://i.imgur.com/a0CGlAF.png) haben die Teilnehmer des Channels 2 Minuten Zeit zu abzustimmen. Sollte innerhalb der 2 Minuten nicht abgestimmt werden wird der Nutzer nicht aus dem Channel gekickt. Zusätzlich **kannst** du einen Grund angeben warum du den Nutzer kicken möchtest.<br>
    **Verwendung:**<br>
    [`/channel kick nutzer:@user grund:grund`](https://i.imgur.com/tanZkfj.png)<p>
* `/channel limit`
    * Hiermit kannst du dein Limit deines Channel erhöhen und beliebig verändern. Achte aber: das maximale Limit eines Channels ist **99**! Gibst du keine Größe des Channels an, so wird die aktuelle Anzahl der Nutzer in deinem Channel genommen.<br>
    **Verwendung:**<br>
    [`/channel limit größe:6`](https://i.imgur.com/W5OSyda.png)<br>
    [`/channel limit`](https://i.imgur.com/W5OSyda.png)<p>
* `/channel name`
    * Hiermit kannst du den Namen des Channels ändern. Es sind allerdings bestimmte Wörter möglich welche du mit [/help channel:name](https://i.imgur.com/cNWGXDT.png) sehen kannst. <br>
    Warum haben wir eine Whitelist drin?<br>
    Bestimmt Wörter sind auf Discord (als Channel-Name) nicht erlaubt.<br>
    **Verwendung:**<br>
    [`/channel name neuer_name:Plat +1`](https://i.imgur.com/dAX5cxA.png)<p>
* `/channel unlimit`
    * Das Prinzip gleicht dem `limit` Befehl.<br>
    Allerdings hebt dieser Befehl das Limit deines Channels komplett auf und setzt diesen auf unbegrenzt.<br>
    **Verwendung:**<br>
    [`/channel unlimit`](https://i.imgur.com/eaNSRAH.png)<p>
* `/channnel private`
    * Dieser Befehl macht deinen Channel privat indem er über deinen Channel einen neuen Channel Namens: ⇩ Join (username) erstellt. Nun können Nutzer dir eine Anfrage zum beitreten schicken indem sie dem ⇩ Join (username) Channel joinen. Es wird eine Automatische Nachricht verfasst und du kannst diese dann annehmen oder ablehnen.<br>
    **Verwendung:**<br>
    [`/channel private`](https://i.imgur.com/p0r6XF6.png)<p>
* `/channel public`
    * Wenn du einen privaten Channel hast kannst du mit diesem Befehl den Channel wieder sichtbar machen.<br>
    **Verwendung:**<br>
    [`/channel public`](https://i.imgur.com/77BraGy.png)<p>
* `/channel transfer`
    * Mit dem transfer Befehl kannst du den Owner deines Voice-Channels abgeben. Du gibt damit deine Berechtigung für den Channel ab.<br>
    **Verwendung:**<br>
    [`/channel transfer nutzer:@user`](https://i.imgur.com/8R00SHu.png)<p>
* `/lfg`
    * Suche! Dieser Befehl schickt einen Channelinvite abhängig deiner Rollen (pc/ ps) in die entsprechende Spielersuche. Wenn du entspr. Rollen hast brauchst du keine Plattform angeben. Hast du keine Rollen welche deine Plattform zeigen so musst du eine angeben. Du kannst optional auch ein Text angeben und somit deine Anfrage etwas spezifizieren. Diesen Befehl kannst du nur in den vc/commands ausführen.<br>
    **Verwendung:**<br>
    [`/lfg plattform:pc text:Suche eine Spieler`](https://i.imgur.com/Fh8HoxB.png)<p>
---
[Hier gehts zum Anfang](#apex-legends-germany-bot-commands-)<br><br>

### **Slash-Befehle außerhalb der temporären Channel:**
*Hier findest du alle Befehle, deren Anwendung und entspr. Beispiele.*
* `/all`
    * Der all Befehl zeigt dir eine Übersicht aller Befehle des ALG-Bots.<br>
    **Verwendung:**<br>
    [`/all`](https://i.imgur.com/FbMlckL.png)<p>
* `/tags`
    * Tags sind feste Embed welche in einem beliebigen Channel gepostet werden können. Es stehen aktuell [ALGinfo](https://i.imgur.com/mOH3SxH.png), [Socials](https://i.imgur.com/9GP1aBA.png), [Suche](https://i.imgur.com/aOvbyIh.png), [Down](https://i.imgur.com/lUEoT1K.png) zur Verfügung.<br>
    **Verwendung:**<br>
    [`/tags type:ALGinfo`](https://i.imgur.com/cDvu5Aq.png)<p>
* `/timestamp`
    * Der Timestamp Befehl gibt dir alle Zeitstempel in den verschiedensten Varianten aus. Diese kannst du einfach kopieren und in den Chat posten.<br>
    Optional kannst du auch eine Zeit angeben.<br>
    **Verwendung:**<br>
    [`/timestamp date:01-01-2022 22:00`](https://i.imgur.com/aULox3H.png)<p>
---
<br>
<br>

###  **Moderation mit Slash: 🔨**
*Hier findest du Beispiele für die Anwendung der Moderations-Befehle. Jeder Befehl kann auch mit der ID des Nutzers genutzt werden. Wichtig ist hierbei dass du den Bot auswählst und den Befehl nicht einfach in den Chat schreibst.*
* `/ban`
    * Bannt einen Nutzer permanent von dem Discord. Der Nutzer bekommt das den Grund per DM mitgeteilt. Es wird ein Grund benötigt, da sonst nicht gebannt werden kann. Optional kann man noch angeben von wie viele Tage zurück man die Nachrichten des Nutzers löschen möchte (Standard ist 1). Bans sind immer nachvollziehbar zu beschreiben. Zusätzlich sollte, wenn es die Situation bietet, man einen Screenshot als Nachweis anhängen.<br>
    **Verwendung:**<br>
    [`/ban nutzer:@Tim-nT grund:Kein guter Modeartor.`](https://i.imgur.com/ADr78po.png)<p>
* `/scamban`
    * Banne einen Nutzer mit der Vorlage. Vorteil: Du erstparrst dir das Copy-Pasten der [Vorlage](https://i.imgur.com/oSPIpuK.png). Zusätzlich wird bei einem 2ten Ban mit `/scamban` dem Nutzer nicht mehr der Entbannungs-Discord mitgeschickt.<br>
    **Verwendung:**<br>
    [`/scamban nutzer:@Tim-nT`](https://i.imgur.com/sH4sZyg.png)
* `/unban`
    * Entbannt einen Nutzer. Ebenfalls wird auch hier **immer** ein Grund benötigt um einen Nutzer zu entbannen.<br>
    **Verwendung:**<br>
    [`/unban nutzer:@Tim-nT grund:Ist doch ein guter Moderator.`](https://i.imgur.com/VtLuUkQ.png)<p>
* `/kick`
    * Kickt einen Nutzer von dem Discord. Ebenfalls wird auch hier **immer** ein Grund benötigt.<br>
    **Verwendung:**<br>
    [`/kick nutzer:@Tim-nT grund:Möchte kein Teil der Community sein.`](https://i.imgur.com/KKOtK7V.png)<p>
* `/modlog user`
    * Frage die Modlogs eines Nutzers ab. Ein Nutzer hat ModLogs wenn dieser verwarnt, gebannt, entbannt ..etc.. wurde. Modslogs können nur Senior-Moderatoren aufwärts gelöscht werden.<br>
    **Verwendung:**<br>
    [`/modlog user nutzer:275258547749650433`](https://i.imgur.com/K9UcWPv.png)<p>
* `/modlog case`
    * Bekomme mehr Information über eine bestimmte Case-ID.<br>
    **Verwendung:**<br>
    [`/modlog case case_id:5`](https://i.imgur.com/1SwUnMh.png)<p>
* `/modlog edit`
    * Ändere den Grund eines ModLogs. Diese Aktion ist ab Senior-Moderator begrenzt.<br>
    **Verwendung:**<br>
    [`/modlog edit case_id:5 grund:~edit case Nummer 5`](https://i.imgur.com/WKTblfm.png)<p>
* `/modlog delete`
    * Entferne einen ModLog von einem Nutzer. Diese Aktion ist ab Senior-Moderator begrenzt.<br>
    **Verwendung:**<br>
    [`/modlog delete case_id:5`](https://i.imgur.com/qT4tzSe.png)<p>
* `/note`
    * Gebe jemanden eine Notiz ohne eine DM zu versenden. *Auch nutzbar nach einem ban.*<br>
    **Verwendung:**<br>
    [`/note nutzer:275258547749650433 note:Könnte Cheaten.`](https://i.imgur.com/1RccWhn.png)<p>
* `/warn`
    * Verwarnt einen Nutzer mit einem Grund welcher ihm dann per DM geschickt wird. Der Grund wird hier ebenfalls benötigt. <br>
    **Verwendung:**<br>
    [`/warn nuzer:275258547749650433 grund:Verhalten im Chat geht nicht klar`](https://i.imgur.com/zRGqkyH.png)<p>
* `/mute`
    * Mute jemanden permanent. (Over Time kommt zu einem späteren Zeitpunkt.)<br>
    **Verwendung:**<br>
    [`/mute nutzer:275258547749650433 grund:Spammen von Emotes`](https://i.imgur.com/9kB3t8R.png)
* `/unmute`
    * Jemanden unmuten der gemuted wurde. Der Nutzer bekommt dann den Grund als DM.<br>
    **Verwendung:**<br>
    [`/unmute nutzer:@Tim-nT grund:Strafzeit abgesessen.`](https://i.imgur.com/czYUyDB.png)
* `/user`
    * Bekomme nützliche Informationen über einen Nurtzer. (gleich wie /info)<br>
    **Verwendung:**<br>
    [`/user nutzer:@Tim`](https://i.imgur.com/61u40dM.png)<p>
* `/role list`
    * Listet alle Rolle des gesamten Servers samt Anzahl der Member und ID auf.<br>
    **Verwendung:**<br>
    [`/role list`](https://i.imgur.com/CP80PbD.png)<p>
* `/role members`
    * Bekomme alle Nutzer samt ID welche eine bestimmte Rolle besitzen. Es kann sowohl eine ID als auch eine Mention der Rolle angegeben werden.<br>
    **Verwendung:**<br>
    [`/role members rolle:@Admin`](https://i.imgur.com/pTVstjo.png)<p>
* `/role count`
    * Zählt alle Nutzer/ Bots mit der Rolle. Es kann sowohl eine ID als auch eine Mention der Rolle angegeben werden.<br>
    **Verwendung:**<br>
    [`/role count rolle:@Admin`](https://i.imgur.com/LAYzIMU.png)<p>
* `/role info`
    * Bekomme nützliche Infomationen über eine Rolle.<br>
    **Verwendung:**<br>
    [`/role info rolle:@Admin`](https://i.imgur.com/kzU6RtW.png)<p>
* `/role give`
    * Gebe jemanden eine Rolle. Es kann sowohl eine ID als auch eine Mention der Rolle/ des Nutzers angegeben werden.<br>
    **Verwendung:**<br>
    [`/role give rolle:@Admin nutzer:@ALG`](https://i.imgur.com/3GScruP.png)<p>
* `/role take`
    * Entferne jemanden eine Rolle. Es kann sowohl eine ID als auch eine Mention der Rolle/ des Nutzers angegeben werden.<br>
    **Verwendung:**<br>
    [`/role take rolle:@Admin nutzer:@ALG`](https://i.imgur.com/1rcZFZ6.png)

---
[Hier gehts zum Anfang](#apex-legends-germany-bot-commands-)<br><br>

### **Nomale Befehle:**
*Diese normalen Befehle geben ein Embed aus und deine Nachricht welche den Befehl auslöst wird direkt gelöscht. Diese Befehle sind hilfreich um in Tickets immer mit der gleichen Nachricht zu antworten.*<br>
*Tipp: Ihr könnt auch Nutzer "silent-pingen" indem ihr einfach an eurem Befehl ein @user schreibt.*
* `%18`
    * Alias: %18+, %ü18<br>
    Fragt ein Nutzer nach Ü18 kann man diesen Befehl nutzen.<br>
    [Embed ansehen](https://i.imgur.com/p5581qT.png)<p>
* `%expert`
    * Alias: %skilled<br>
    Ein Nutzer macht ein Ticket auf oder fragt im Chat wie man die Skilled oder Expert-Rolle bekommen kann.<br>
    [Embed ansehen](https://i.imgur.com/06I5XQw.png)<p>
* `%nexttry`
    * Alias: %try, %next<br>
    Hat ein Nutzer ein Ticket eröffnet aber bisher immer noch nichts geschreiben. Ihr diesen Befehl nutzen um den Nutzer darauf hinzuweisen. Empfehlenswert mit Silent-Ping<br>
    [Embed ansehen](https://i.imgur.com/gUuqKuX.png)<p>
* `%nickname`
    * Der Nickname eines Nutzers verstößt gegen die ToS von Disord bzw. gegen unsere [#server-regeln](https://discord.com/channels/542304652381782016/560975462319390720) so ist diese Embed am besten.<br>
    [Embed ansehen](https://i.imgur.com/cJlAJai.png)<p>
* `%scam`
    * Sollte ein Nutzer einen Scam reporten.<br>
    [Embed ansehen](https://i.imgur.com/e1lz90Q.png)<p>
* `%sup`
    * Falls die Bearbeitung es Ticket etwas dauert oder man investigieren muss ist dieser Befehl hilfreich.<br>
    [Embed ansehen](https://i.imgur.com/7zCX0Ht.png)<p>
* `%time`
    * Ein Nutzer pingt das Team oder fragt nach wann endlich Supportet wird.<br>
    [Embed ansehen](https://i.imgur.com/3l1t9Av.png)<p>
* `%ticktsystem`
    * Alias: %ts<br>
    Dieser Befehl postet ebenfalls ein Embed, ist allerdings nur für den internen Bereich gedacht welches er dir ein Embed mit der Übersicht alles `%` Befehle gibt.<br>
---
[Hier gehts zum Anfang](#apex-legends-germany-bot-commands-)<br>

