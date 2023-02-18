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
    - [Moderation mit Slash (Apex-Befehle)](#moderation-mit-slash-apex-befehle-und-funktion)
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

---
[Hier gehts zum Anfang][go_to_start]<br><br>

## **Befehle Außerhalb der Voice-Channel:** <img src="https://cdn.discordapp.com/emojis/919244135779688549.png?size=96" height=18><br>
*Befehle welche von jedem genutzt werden können und man in keinem Voice-Channel sein muss.*<br>
[Mehr Information über diese Befehle.](#slash-befehle-außerhalb-der-temporären-channel)
- /activities
- /all
- /avatar
- /tags
- /timestamp
- /ping
- /geburstag
- /patreon
- /share

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
- /prole

<br>

*Befehle welche außerhalb der BOT-Channels verwendet werden können.*
- /clear

---
[Hier gehts zum Anfang][go_to_start]<br><br>
### **Normale Befehle:**<br>
<!-- Normale Commands für Mods -->
*Diese normalen Befehle funktionieren nicht mit Slash, die unten sind Embed welche bei dem posten permanent bestehen bleiben.*<br>
[Mehr Information über diese Befehle.](#nomale-befehle)


---
<br>
<br>

## **Unser Ticketsystem** 🎫<br>
<!-- Commands für das Ticketsystem -->
*Befehle für das Ticketsystem. Die Nutzung der Buttons ist vorausgesetzt.*
- `/ticket new user:@Tim-nT` - Erstellt ein Ticket mit einem Nutzer zusammen. Der Grund ist optional und muss nicht mit angegeben werden.<br>
- `/ticket rename name:Neuer Name` - Ändert den Namen eines Tickets.<br>
- `/ticket add user:@Tim-nT` - Fügt einen Nutzer/ Rolle vom Server zu einem Ticket hinzu.<br>
- `/ticket remove user:@Tim-nT` - Entfernt einen Nutzer/ Rolle von einem Ticket.
---
---
[Hier gehts zum Anfang][go_to_start]<br><br>
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
[Hier gehts zum Anfang][go_to_start]<br><br>

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
* `/color`
    * Bekomme eine Preview von einer Hex Color. *mehr Farb-Codes SoonTM*<br>
    **Verwendung:**<br>
    [`/color color_hex:EB144D`]()<p>
* `/giveaway create`
    * Erstelle ein Giveaway <br>
    **Verwendung:**<br>
    [`/color create`](https://i.imgur.com/wMp0Pvf.png)<p><br>
*Die `/share` Befehle sind erst ab Patreon Tier 3 ausführbar!*
* `/share list`
    * Zeigt dir eine Liste von deiner geteilten Custom Patreon Rolle an.<br>
    **Verwendung:**<br>
    `/share list`<p>
* `/share add`
    * Fügt einem User deine Custom Patreon Rolle hinzu.<br>
    **Verwendung:**<br>
    `/share add user: @user | ID`<p>
* `/share remove`
    * Entfernt einem User deine Custom Patreon Rolle.<br>
    **Verwendung:**<br>
    `/share remove: @user | ID`<p>
 
---
<br>
<br>

###  **Moderation mit Slash: 🔨**
*Hier findest du Beispiele für die Anwendung der Moderations-Befehle. Jeder Befehl kann auch mit der ID des Nutzers genutzt werden. Wichtig ist hierbei, dass du den Bot auswählst und den Befehl nicht einfach in den Chat schreibst. Nicht jeder Befehl ist für Moderatoren auf Probe, aber alle sind ab Moderator möglich.*
* `/channel move`
    * Verschiebt alle Nutzer eines Talk-Channels in einen neuen.<br>
* `/ban`
    * Bannt einen Nutzer permanent von dem Discord. Der Nutzer bekommt das den Grund per DM mitgeteilt. Es wird ein Grund benötigt, da sonst nicht gebannt werden kann. Optional kann man noch angeben von wie viele Tage zurück man die Nachrichten des Nutzers löschen möchte (Standard ist 1). Bans sind immer nachvollziehbar zu beschreiben. Zusätzlich sollte, wenn es die Situation bietet, man einen Screenshot als Nachweis anhängen.<br>
    Gebe nur */ban nutzer:@Tim-nT* um einen Ban-Antrag zu stellen. Der Ban-Antrag ist ebenfalls für Probe-Moderatoren nutzbar.<br>
    **Verwendung:**<br>
    [`/ban nutzer:@Tim-nT grund:Kein guter Modeartor.`](https://i.imgur.com/ADr78po.png)<p>
* `/scamban`
    * Banne einen Nutzer mit der Vorlage. Vorteil: Du erstparrst dir das Copy-Pasten der [Vorlage](https://i.imgur.com/oSPIpuK.png). Zusätzlich wird bei einem 2ten Ban mit `/scamban` dem Nutzer nicht mehr der Entbannungs-Discord mitgeschickt.<br>
    **Verwendung:**<br>
    [`/scamban nutzer:@Tim-nT`](https://i.imgur.com/sH4sZyg.png)
* `/unban`
    * Entbannt einen Nutzer. Ebenfalls wird auch hier **immer** ein Grund benötigt um einen Nutzer zu entbannen. Eine Einladung wird ebenfalls zusätzlich verschickt.<br>
    **Verwendung:**<br>
    [`/unban nutzer:@Tim-nT grund:Ist doch ein guter Moderator.`](https://i.imgur.com/VtLuUkQ.png)<p>
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
* `/kick`
    * Kickt einen Nutzer vom Server.<br>
    **Verwendung:**<br>
    [/kick nutzer:275258547749650433 grund:Mag Katzen](https://i.imgur.com/f8taZsp.png)<p>
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
    [`/role take rolle:@Admin nutzer:@ALG`](https://i.imgur.com/1rcZFZ6.png)<p>
* `/prole info`
    * Erhalte Informationen über die Custom Rolle eines Users.<br>
    **Verwendung:**<br>
    [`/prole info user: @user | ID`](https://i.imgur.com/WMGMXoS.png)<p>
* `/prole add`
    * Übertrage die Custom Rolle auf einen User.<br>
    **Verwendung:**<br>
    [`/prole add user: @user | ID role: @role`](https://i.imgur.com/bJO1moP.png)<p>
* `/prole remove`
    * Entferne die Custom Rolle eines Users.<br>
    **Verwendung:**<br>
        [`/prole remove user: @user | ID`](https://i.imgur.com/ZGNr5Je.png)
  
        

---
[Hier gehts zum Anfang][go_to_start]<br><br>

### **Moderation mit Slash (Apex-Befehle und Funktion):**
<!-- Alles rund um die "Apex" Commands-->
* `/apex user user:@Tim-nT`<br>
    * Finde heraus mit welchem Apex-Account ein Nutzer verknüpft ist.<br>
    Optional Nutzbar mit der Origin-ID um einen Discord-Nutzer zu finden.<p>
* `/apex api origin_id:12345678 plattform:PC`<br>
    * Eine direkte abfrage um etwaige Informationen über einen Account zu bekommen.<p>
* `/apex autorank state:Aktivieren user:@Tim-nT`<br>
    * Enabled oder Disabled das automatische updates eines Ranges von einem Nutzer.<p>
* `/apex count`<br>
    * Zeigt die wie viele Nutzer aktuell verifiziert sind<br><br>

### **Vorgehensweise bei Unlinkungen**:
#### #1 Aktuellen Apex-Account mit `/apex user` abfragen und die Apex-ID kopieren 
#### #2 Eine Notiz mit `/note` mit der Apex-ID zu dem jeweiligen Benutzer hinzufügen. (`/note user:@Tim-nT reason:Hat seinen Account unlinken lassen weil Smurf. Apex-ID: 2423448648`)
#### #3 Die Apex-ID mit `/blacklist` zu unserer internen Blacklist hinzufügen!
#### #4 Der Account ist nach danach mit `/unlink` zu unliken!<br>
*Notiz: Es ist dem Nutzer nicht gestattet zu wissen das wir die Accounts auf eine blacklist packen!*<br><br>

* `/apex unlink user:@Tim-nT`<br>
    * Entfernt die verlinkung zu einem Nutzer.<br>
    Richtlinie: Sollte ein Nutzer gebannt o.ä. werden so die Origin Account-ID zu blacklisten!<p>
* `/blacklist add origin_id:12345678 reason:Cheater in Apex Discord-ID:275258547749650433 siehe ban oder case-ID 1234`<br>
    * Setzt einen Apex-Account auf die Blacklist sodass ein Nutzer sich nicht mehr mit diesem Account verlinken kann!<br>
    **Wichtig:** Hierbei ist die Discord-ID des ehemaligen Nutzers **oder** die Case-ID notwendig, da sonst eine eindeutige identifizierzung nicht möglich ist!!
    <p>
* `/blacklist show account_id:12345678`<br>
    * Lasse dir einen Eintrag aus der Blacklist anzeigen.<p>
* `/blacklist remove origin_id:12345678`<br>
    * Entferne einen Account von der Blacklist sodass ein Nutzer sich wieder mit dem Account verknüpfen kann.<br>
    Im besten Fall wird hierbei nochmal Rücksprache mit den älteren Mods gehälten.
        
        
### **Vorgehensweise bei Last-Split-Rollen**:
#### #1 Alle User von sämtlichen Last-Split-Rollen entfernen (Am Besten schon am Vortag erledigen!)
#### #2 Umbennenung der Rollen
#### #3 Automatische-Rangrollenvergabe deaktivieren **(Erst kurz vor Split-Ende)**
#### #4 Last-Split-Rollen vergeben<br><br>

1. `/role all role:@role remove:true`<br>
    * Entfernt alle User der angegebenen Rolle **(Dyno-Bot auswählen!)**<br>
    Dieser Befehl muss also mindestens **4 Mal** ausgeführt werden<br>
2. Nenne die Last Split Rollen um: S14.2-BR-Master -> S15.1-BR-Master
3. `/apex vtoggle`<br>
    * Deaktiviert für User die Verifizierung.
4. Die folgenden Befehle weisen User mit der aktuellen Rang-Rolle die entsprechende Last-Split-Rolle zu.<br>
    * `/role in in_role:628715049392799755 role:991407728075485235` (Predator-BR)<br>
    * `/role in in_role:673539726027915275 role:991407745037254826` (Master-BR)<br>
    * `/role in in_role:628714695242678313 role:991407754050814014` (Diamond-BR)<br>
    * `/role in in_role:628715389144137732 role:1006564768838078565` (Platinum-BR)<br>


---
[Hier gehts zum Anfang][go_to_start]<br><br>

### **Nomale Befehle:**
*Diese normalen Befehle geben ein Embed aus und deine Nachricht welche den Befehl auslöst wird direkt gelöscht. Diese Befehle sind hilfreich um in Tickets immer mit der gleichen Nachricht zu antworten.*<br>
*Tipp: Ihr könnt auch Nutzer "silent-pingen" indem ihr einfach an eurem Befehl ein @user schreibt.*<p>
Alle folgenden Commands werden mit einer @ Mention an den Bot ausgeführt!<br>
Beispiel: `@ALG 18`<br>

* `18`
    * Alias: `ü18`, `18+`<br>
    Fragt ein Nutzer nach Ü18 kann man diesen Befehl nutzen.<br>
    [Embed ansehen](https://i.imgur.com/p5581qT.png)<p>
* `expert`
    * Alias: `skilled`<br>
    Ein Nutzer macht ein Ticket auf oder fragt im Chat wie man die Skilled oder Expert-Rolle bekommen kann.<br>
    [Embed ansehen](https://i.imgur.com/06I5XQw.png)<p>
* `master`
    * Alias: `mas`, `pred`, `predator`, `dia`, `diamond` <br>
    Ein Hinweis darauf, dass sich Nutzer die Diamond+ Rolle nur über das Verifizierungssystem abholen können.<br>
    [Embed ansehen](https://i.imgur.com/mAtW9Mq.png)<p>
* `nexttry`
    * Alias: `try`, `next`<br>
    Hat ein Nutzer ein Ticket eröffnet aber bisher immer noch nichts geschreiben, könnt ihr diesen Befehl nutzen um den Nutzer darauf hinzuweisen. Empfehlenswert mit @silent-Ping<br>
    [Embed ansehen](https://i.imgur.com/gUuqKuX.png)<p>
* `nickname`
    * Alias: `hsnick`<br>
    Der Nickname eines Nutzers verstößt gegen die ToS von Disord bzw. gegen unsere [#server-regeln](https://discord.com/channels/542304652381782016/560975462319390720) so ist diese Embed am besten.<br>
    [Embed ansehen](https://i.imgur.com/OTn5bhS.png)<p>
* `beleidigung`
    * Alias: `flame` <br>
    Für Tickets bei dem ein Nutzer reportet wurde.<br>
    [Embed ansehen](https://i.imgur.com/Y4mluJL.png)<p>
* `rank`
    * Alias: `ranked` <br>
    Postet ein permanentes Embed mit dem Hinweis darauf, wo die Ranked-Rollen zu finden sind.<br>
    [Embed ansehen](https://i.imgur.com/iPf0CBI.png)<p>
* `scam`
    * Sollte ein Nutzer einen Scam reporten.<br>
    [Embed ansehen](https://i.imgur.com/e1lz90Q.png)<p>
* `sup`
    * Alias: `support`<br>
    Falls die Bearbeitung es Ticket etwas dauert oder man investigieren muss ist dieser Befehl hilfreich.<br>
    [Embed ansehen](https://i.imgur.com/7zCX0Ht.png)<p>
* `time`
    * Ein Nutzer pingt das Team oder fragt nach wann endlich Supportet wird.<br>
    [Embed ansehen](https://i.imgur.com/3l1t9Av.png)<p>
* `ticktsystem`
    * Alias: ts<br>
    Probier einfach auch was das ist.<br>
---
[Hier gehts zum Anfang][go_to_start]<br>


[go_to_start]: #apex-legends-germany-bot-commands-