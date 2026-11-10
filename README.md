# WoW Forever: Fundstücke

**Ein Rundgang durch Addons, Webseiten und Werkzeuge rund um World of Warcraft: Forever, für alle, die mehr suchen als die üblichen zehn Empfehlungen.**

Stand: 2026-11-10 · Client 1.60.1 · 53 Einträge hier, 87 auf der [vollständigen Übersicht mit Suche und Filter](https://kirchlive.github.io/wow-forever-fundstuecke/)

Jeder Eintrag wurde an seiner Originalquelle geprüft: Das Repo wurde geklont und gelesen, die Addon-Seite oder Webseite geöffnet. Was sich nicht bestätigen ließ, steht nicht hier. Wie genau geprüft wurde, steht [weiter unten](#so-wurde-geprüft).

## Inhalt

- [Warum Forever eigene Addons braucht](#warum-forever-eigene-addons-braucht)
- [Wo fange ich an?](#wo-fange-ich-an)
- [Leveling und Routen](#leveling-und-routen)
- [Datenbanken, Rechner und Karten](#datenbanken-rechner-und-karten)
- [Interface und Komfort](#interface-und-komfort)
- [Entdecken und Sammeln](#entdecken-und-sammeln)
- [Berufe, Camping und Handel](#berufe-camping-und-handel)
- [Klassen-Helfer und Ausrüstung](#klassen-helfer-und-ausrüstung)
- [Gilde und Gruppe](#gilde-und-gruppe)
- [Rollenspiel, Sprache und Atmosphäre](#rollenspiel-sprache-und-atmosphäre)
- [Entwickler-Tooling und KI](#entwickler-tooling-und-ki)
- [Plattform-Exoten](#plattform-exoten)
- [Grauzone: nicht empfohlen](#grauzone-nicht-empfohlen)
- [Was diese Liste nicht ist](#was-diese-liste-nicht-ist)
- [So wurde geprüft](#so-wurde-geprüft)
- [Etwas beitragen](#etwas-beitragen)

## Warum Forever eigene Addons braucht

World of Warcraft: Forever ist seit dem 4. November 2026 live. Es ist die ursprüngliche Welt von Stufe 1 bis 60, erweitert um neue Zonen wie Zephras Isle und die Riverglades, das neue Volk der Skyborne und Systeme wie Camping und Vermächtnis (accountweite Punkte für Herausforderungen). Technisch läuft es auf dem modernen Client, nicht auf dem von Classic. Das hat drei Folgen. Alte Classic-Addons funktionieren nicht einfach weiter. Vieles ist schon eingebaut, etwa der Bearbeitungsmodus für die Oberfläche, ein Schadensmesser und ein Cooldown-Manager. Und im Kampf hält der Client bestimmte Werte vor Addons geheim, zum Beispiel Lebenspunkte von Gegnern. Addons, die daraus etwas berechnen wollen, gehen deshalb nicht mehr oder müssen Umwege finden. WeakAuras und TradeSkillMaster gibt es für Forever bislang nicht. Genau in diesen Lücken ist in wenigen Wochen eine eigene kleine Landschaft entstanden.

## Wo fange ich an?

Die Grundausstattung (Questie, Leatrix Plus, Baganator, Auctionator) steht in jeder Top-10-Liste und fehlt hier absichtlich. Wenn du darüber hinaus nur sechs Dinge ausprobierst, dann diese:

- **[Polestar](#polestar)**: kostenloser Leveling-Guide mit Pfeil, auch auf Deutsch
- **[OpenMap](#openmap)**: eine Weltkarte, auf der du einfach herauszoomst
- **[ForeverChanges](#foreverchanges)**: nachschlagen, was Forever gegenüber Classic geändert hat
- **[Keep or Toss: Forever](#keep-or-toss-forever)**: sagt dir, was aus der Tasche weg kann
- **[ForeverArtisan](#foreverartisan)**: nimmt Berufen das Rechnen ab
- **[WoW Forever Diary](#wow-forever-diary)**: schreibt nebenbei die Geschichte deines Charakters auf

## Leveling und Routen

Der Weg von 1 bis 60 ist lang, und Forever hat neue Zonen, neue Quests und ein neues Volk dazubekommen. Diese Projekte sagen dir, wohin du als Nächstes läufst, oder zeichnen auf, wie deine Reise verlaufen ist.

### Polestar

[polestar.guide](https://polestar.guide) · Addon + Webseite · Kostenlos, Open Source (GPL-3.0)

<img src="https://polestar.guide/shots/shot-guide.webp" width="640" alt="Polestar: Schritte eines Guides im Spiel">

Polestar führt dich Schritt für Schritt von 1 bis 60, mit einer eigenen Startroute für jedes Volk. Ein Pfeil zeigt im Spiel den Weg, und dieselben Guides lassen sich auf der Webseite mitlesen. Neben dem Leveln gibt es Guides für Klassenquests, Berufe, Ruf, Reittiere und Begleiter.

**Gut zu wissen:** Trägt noch das Etikett Beta.

**Alternativen:** [Sage Guide](https://www.sageguide.net) (Ausführlicher Text-Guide im Browser, nur für die Allianz), [FlowUp](https://flowup-wow.com) (Routen, die aus dem berechnet werden, was Spieler tatsächlich tun).

### LevelForge

[levelforge.dev](https://levelforge.dev) · Addon + Webseite · Kostenlos

<img src="https://levelforge.dev/levelforge.png" width="640" alt="LevelForge-Logo">

LevelForge besteht aus einem Addon, einem Katalog von Community-Guides und einem Editor, in dem du Routen selbst schreibst oder per Ziehen auf der Karte anpasst. Das Addon nimmt dir Routine ab, etwa Quests annehmen und abgeben, und zeigt Wegpunkte samt Pfeil. Hältst du Shift gedrückt, machst du alles von Hand.

**Gut zu wissen:** Unterstützt Classic Era und Forever.

### Factoruide

[github.com/brouznouf/factoruide](https://github.com/brouznouf/factoruide) · Repo (App + Addon) · Kostenlos, Open Source · **Neu**

<img src="https://raw.githubusercontent.com/brouznouf/factoruide/main/docs/guide.png" width="640" alt="Factoruide: Route auf der Karte mit Level je Etappe">

Die meisten Guides sind eine Route für alle. Factoruide simuliert stattdessen deinen Durchlauf mit deinen Berufen, Wunschzonen und Dungeons und sucht den schnellsten Weg zum Ziellevel. Ein Addon führt dich danach im Spiel durch das Ergebnis.

**Gut zu wissen:** Der Autor nennt es selbst ein Experiment: Die Simulation kann Unsinn liefern, etwa eine Quest, die du nicht bekommst. Ein guter handgeschriebener Guide ist vermutlich schneller.

**Alternativen:** [Road to 60](https://roadto60.com) (Planer, der dir einen Tagesplan bis Stufe 60 ausrechnet).

### Joana's World

[www.joanasworld.com](https://www.joanasworld.com) · Addon + Webseite · 1 bis 30 gratis, danach Abo oder Einmalkauf

<img src="https://www.joanasworld.com/newhome/assets/img/HomeAddonMap.png" width="640" alt="Joana-Addon mit Kartenansicht">

Joana schreibt seit 2006 Leveling-Guides und liefert sie heute über ein eigenes kostenloses Addon aus. Für Forever sind die Stufen 1 bis 20 dabei, 20 bis 30 gibt es mit einem Gratis-Konto, der Rest kostet. Wo es noch keine eigene Forever-Route gibt, greift das Addon auf die Classic-Era-Route zurück.

**Gut zu wissen:** Preise laut Webseite am Prüftag, die Einführungspreise sind befristet. Forever-Guides enthalten keinen Hardcore-Modus.

**Alternativen:** [RestedXP](https://www.restedxp.com) (Der kommerzielle Platzhirsch unter den Guide-Addons), [Zygor Guides](https://zygorguides.com) (Premium-Guides mit eigenem Viewer im Spiel).

### Campfire

[campfire.7donuts.dev](https://campfire.7donuts.dev) · Addon + Webseite · Kostenlos (kein Preis genannt)

Das Addon Campfire Journeys schreibt mit, während du spielst. Den Export lädst du auf die Webseite und siehst deinen Weg durch Azeroth, Quests, Kills, knappe Situationen und die Zeit, die du gebraucht hast. Wer mag, vergleicht sich mit anderen am selben Meilenstein.

**Gut zu wissen:** Anmeldung über Discord oder Battle.net nötig.

**Alternativen:** [Road to Sixty](https://roadtosixty.online) (Spielt deine Reise auf der Weltkarte noch einmal ab).

### WoW Forever Tracker

[www.curseforge.com/wow/addons/wow-forever-tracker](https://www.curseforge.com/wow/addons/wow-forever-tracker) · Addon + Webseite · Kostenlos

<img src="https://media.forgecdn.net/attachments/2031/235/wft2-png.png" width="640" alt="WoW Forever Tracker im Spiel">

Das Addon merkt sich Level, Quests, Berufe, Ausrüstung, Talente und Auktionspreise. Die dazugehörige Webseite baut daraus eine Route, einen Berufsplan und Upgrade-Vorschläge, die du wieder ins Spiel holst. Eine Besonderheit: Auf der Webseite beschreibst du ein Makro in normalen Worten, und /wft macro legt es im Spiel an.

**Gut zu wissen:** Die Webseite läuft unter einer Railway-Adresse, wirkt also wie ein Ein-Personen-Projekt.

## Datenbanken, Rechner und Karten

Forever ändert Talente, Zauber und Gegenstände gegenüber Classic. Diese Seiten und Addons beantworten die Frage „Was hat sich geändert, und was heißt das für meinen Charakter?“

### ForeverChanges

[foreverchanges.pro](https://foreverchanges.pro) · Webseite · Kostenlos, mit Werbung

<img src="https://foreverchanges.pro/home/talent-calculator.webp" width="640" alt="Talentrechner von ForeverChanges">

Wer wissen will, was Blizzard geändert hat, fängt hier an: Änderungen je Klasse, Blue Posts, Talentrechner und ein Zauberbuch Rang für Rang. Dazu kommen Beute für 35 Dungeons, eine Karte in 2D und 3D und eine Seite mit Gegenständen, deren Werte der Client noch verbirgt.

**Gut zu wissen:** Mehrere Addons nutzen die BiS-Listen dieser Seite als Datenquelle.

**Alternativen:** [The Forever Era](https://theforeverera.com/de/) (Datenbank mit Talentrechner, BiS-Listen und Karte, auch auf Deutsch), [AzerPUG Forever](https://forever.azerpug.com/) (Interaktive Karte mit NPCs, Quests, Dungeons und Begleitern).

### WoW Forever Builds

[wowforeverbuilds.com](https://wowforeverbuilds.com) · Webseite · Kostenlos, Konto nur zum Veröffentlichen

<img src="https://wowforeverbuilds.com/og/default.jpg" width="640" alt="WoW Forever Builds">

Der Rechner deckt alle neun Klassen mit 51 Punkten ab und erzeugt teilbare Links. Praktisch beim Leveln: Zu jedem Build gibt es die Reihenfolge, in der du die Punkte setzt. Der Vermächtnis-Planer verteilt die 16 accountweiten Punkte auf drei Bäume.

**Gut zu wissen:** Kopfzeile und Fußzeile der Seite nennen unterschiedliche Client-Builds, die Daten sind also nicht überall gleich frisch.

**Alternativen:** [WoW Forever Talent](https://wowforevertalent.com) (Schlanker Talentrechner, der Änderungen gegenüber Classic markiert).

### WoWForever.gg

[wowforever.gg/de](https://wowforever.gg/de/) · Webseite · Kostenlos (kein Preis genannt)

Eine Fan-Seite, die von Grund auf deutsch gedacht ist. Sie hilft bei der Klassenwahl, hat einen Talentplaner, einen Herstellungsrechner, einen Ausrüstungsberater und eine interaktive Karte. Dazu kommen News, Guides und eine eigene Geschichtenserie.

**Gut zu wissen:** Community-Funktionen wie Gildenhäuser sind noch als „Demnächst“ markiert.

**Alternativen:** [WoW Forever Community](https://wowforever-community.de/) (Deutsche Fan-Seite mit übersetzten Blizzard-News und Guides).

### WoWSims Forever

[wowsims.com/forever](https://wowsims.com/forever) · Webseite + Repo · Kostenlos, Open Source (MIT) · **Neu**

WoWSims rechnet aus, wie viel Schaden ein Charakter mit bestimmter Ausrüstung und Rotation macht. Das Team hinter den Classic-Simulatoren pflegt inzwischen ein eigenes Forever-Repository. Die Simulation läuft im Browser oder als Download für Windows, macOS und Linux.

**Gut zu wissen:** Welche Klassen schon fertig sind, verrät die Startseite nicht. Simulationsergebnisse sind Modellrechnungen, keine Messungen aus dem Spiel.

**Alternativen:** [WoW: Forever sim (gunba)](https://github.com/gunba/wow-forever-sim) (Simulator-Fork mit einer DPS-Matrix über 34 Builds).

### OpenMap

[www.curseforge.com/wow/addons/openmap](https://www.curseforge.com/wow/addons/openmap) · Addon · Kostenlos, Open Source · **Neu**

<img src="https://media.forgecdn.net/attachments/2038/249/wowscrnshot_101126_015048-jpg.jpg" width="640" alt="OpenMap: nahtlose Weltkarte">

OpenMap fügt alle Zonenkarten zu einer durchgehenden Karte zusammen. Du zoomst von der ganzen Welt bis auf Straßenhöhe, ohne dich durch Zonen zu klicken. Dungeon-Eingänge zeigen ihre Levelspanne, und ein Klick öffnet Blizzards Karte des Dungeons.

**Gut zu wissen:** Das mit Abstand meistgeladene Addon in dieser Liste (rund 137.000 Downloads am Prüftag), also kein Geheimtipp mehr.

### Addon Radar

[addon-radar.com/forever](https://addon-radar.com/forever) · Webseite · Kostenlos · **Neu**

<img src="https://addon-radar.com/og-default.png" width="640" alt="Addon Radar">

Die großen Listen nennen immer dieselben zehn Addons. Addon Radar wertet stündlich die CurseForge-Downloads aus und zeigt bewusst die weniger bekannten: „Hot“ für die meistgeladenen, „Rising“ für das schnellste Wachstum. Für diese Übersicht war die Seite eine der ergiebigsten Quellen.

## Interface und Komfort

Forever läuft auf dem modernen Client, sieht also erst einmal aus wie das aktuelle WoW. Hier findest du Addons, die den alten Look zurückholen, die Oberfläche beruhigen oder dir lästige Klicks abnehmen.

### ClassicUI Forever

[github.com/fallenguards/classicuiforever](https://github.com/fallenguards/classicuiforever) · Addon · Kostenlos, Open Source

Greifenleiste, runde Minikarte, altes Zauberbuch, altes Questlog: ClassicUI Forever legt die Original-Optik über die moderne Oberfläche. Jedes Teil hat einen eigenen Schalter, du behältst also, was dir am Neuen gefällt. Für Forevers Vermächtnis-System gibt es ein eigenes Fenster im alten Stil.

**Gut zu wissen:** Das Repo lag früher unter wowaddonmaker/classicuiforever, die alte Adresse leitet weiter.

**Alternativen:** [ForeverSuite](https://github.com/Bovahkiin/ForeverSuite) (Modulare Oberfläche mit zehn Farbthemen und Profilen).

### QuietUI

[github.com/rdurica/quiet-ui](https://github.com/rdurica/quiet-ui) · Addon · Kostenlos, Open Source

<img src="https://media.forgecdn.net/attachments/2152/157/01-exploring-jpg.jpg" width="640" alt="QuietUI beim Erkunden: die Welt bekommt den ganzen Bildschirm">

Beim Erkunden verschwinden Leisten, XP-Balken und alles andere. Sobald etwas passiert, ist es wieder da: ein Pull, die Maus über der Leiste, ein Dungeon. Mit der Taste ` blitzt die ganze Oberfläche kurz auf.

**Alternativen:** [BlizzHUDTweaks](https://github.com/PhenomDevel/BlizzHUDTweaks) (Blendet Blizzards Standardrahmen je nach Situation aus).

### Goblin Things

[github.com/CoffeeAndLoot/goblinthings](https://github.com/CoffeeAndLoot/goblinthings) · Addon · Kostenlos, Open Source (MIT)

<img src="https://raw.githubusercontent.com/CoffeeAndLoot/goblinthings/master/images/banner.png" width="640" alt="Goblin Things">

Quests automatisch annehmen und abgeben, Graues verkaufen, reparieren, schneller looten, Duelle ablehnen. Der Quest-Tracker lässt sich filtern, etwa auf die aktuelle Zone oder ohne Quests, die zu hoch für dich sind. Hältst du Shift beim Ansprechen eines NPCs, bleibt für diesen Besuch alles aus.

**Alternativen:** [Forever++](https://github.com/xIGBClutchIx/ForeverPlusPlus) (Kleine Module, die aussehen sollen, als hätte Blizzard sie eingebaut), [EQ - Objective Tracker](https://www.curseforge.com/wow/addons/eq-objective-tracker) (Ersetzt den Quest-Tracker durch ein verschiebbares, sortierbares Fenster).

### Haste's Super Tweaks

[github.com/hastecraft/super-tweaks](https://github.com/hastecraft/super-tweaks) · Addon · Kostenlos, Open Source · **Neu**

<img src="https://raw.githubusercontent.com/hastecraft/super-tweaks/master/.github/highlights/xp-tracker.png" width="640" alt="XP Tracker aus Haste's Super Tweaks">

Eine Sammlung von laut Autor über 50 Kleinigkeiten in einem Einstellungsfenster. Zwei stechen heraus: Der Campfire Helper zeigt, wann du nah an einem Feuer bist und wie lange deine Camp-Buffs noch halten. Der XP Tracker rechnet aus, wie viele Kills eines Gegners dir noch zum Levelaufstieg fehlen.

**Gut zu wissen:** Was für dich handelt oder Teile der Oberfläche ersetzt, ist anfangs ausgeschaltet.

### Keep or Toss: Forever

[www.curseforge.com/wow/addons/keep-or-toss-forever](https://www.curseforge.com/wow/addons/keep-or-toss-forever) · Addon · Kostenlos · **Neu**

<img src="https://media.forgecdn.net/attachments/2036/775/tooltips-png.png" width="640" alt="Keep or Toss: Begründung im Tooltip">

Die ewige Taschenfrage: behalten oder weg? Keep or Toss schreibt die Antwort mit Begründung in den Tooltip, etwa weil ein Beruf oder eine Quest den Gegenstand verlangt. Eine eigene Seite sortiert Taschen und Bank nach diesen Gründen.

### forever-icons

[github.com/hastecraft/forever-icons](https://github.com/hastecraft/forever-icons) · Repo (Icon-Paket) · Kostenlos · **Neu**

<img src="https://raw.githubusercontent.com/hastecraft/forever-icons/master/docs/comparison.png" width="640" alt="Zwölf Icons vorher und nachher">

Auf großen Monitoren sehen die alten Icons schnell matschig aus. Dieses Fan-Projekt hat sie alle hochskaliert. Es gibt zwei Pakete: eines mit dem gewohnten grauen Rand, eines mit dünnem schwarzem Rahmen.

**Gut zu wissen:** Die Grafiken selbst gehören Blizzard, das Projekt ist reine Aufbereitung. Wer ein UI-Addon nutzt, das Buttons umrandet, nimmt das Hauptpaket.

### Improved Forever

[github.com/markgravity/ImprovedForever](https://github.com/markgravity/ImprovedForever) · Addon · Kostenlos · **Neu**

<img src="https://raw.githubusercontent.com/markgravity/ImprovedForever/main/media/wheel.webp" width="640" alt="Radialmenü von Improved Forever">

Forever unterstützt Gamepads von Haus aus, lässt aber Wünsche offen. Improved Forever ergänzt Radialmenüs, Vibration und eine Auktionshaus-Bedienung per Pad. Alles lässt sich vom Controller aus einrichten, ohne Tastatur.

**Alternativen:** [TriggerBar](https://github.com/cjwhiskers/TriggerBar) (Ordnet die Gamepad-Leisten zu einer flachen Leiste um).

### ForeverAuras

[github.com/neroxrw/foreverauras](https://github.com/neroxrw/foreverauras) · Addon · Kostenlos, Open Source · **Neu**

WeakAuras selbst gibt es für Forever nicht. ForeverAuras ist eine Portierung, die mit den neuen Regeln arbeitet: Was der Client geheim hält, kann das Addon nicht berechnen, aber es kann Blizzards Cooldown Manager sagen, wie er es anzeigen soll. Viele fertige Auren dafür liegen auf wago.io.

**Gut zu wissen:** Alte WeakAuras-Importe laufen nicht automatisch. Achtung: ForeverArtisan nutzt ebenfalls /fa.

**Alternativen:** [Musca Auras](https://www.curseforge.com/wow/addons/musca-auras) (Zweiter WeakAuras-Fork, mit fertigem HUD für jede Klasse).

## Entdecken und Sammeln

Vermächtnis-Herausforderungen, Bibliotheksbücher, Erzadern, Fische: Forever belohnt Neugier. Diese Addons helfen beim Finden, ohne dir das Finden ganz abzunehmen.

### Legacy Forever

[github.com/cjber/legacy-forever](https://github.com/cjber/legacy-forever) · Addon · Kostenlos, Open Source · **Neu**

<img src="https://raw.githubusercontent.com/cjber/legacy-forever/main/docs/screenshots/map.png" width="640" alt="Legacy Forever auf der Weltkarte">

Das Vermächtnis-System vergibt accountweite Punkte für Herausforderungen, etwa das Erkunden einer Zone. Legacy Forever setzt ein Schild mit einer Zahl an die Weltkarte: so viele Ziele sind auf dieser Karte noch offen. Was du anhakst, erscheint mit Fortschritt im Quest-Tracker.

### ForeverSecrets

[www.curseforge.com/wow/addons/foreversecrets](https://www.curseforge.com/wow/addons/foreversecrets) · Addon · Kostenlos · **Neu**

<img src="https://media.forgecdn.net/attachments/1992/564/screenshot-2026-09-30-120940-png.png" width="640" alt="ForeverSecrets">

Der Cozy Sleeping Bag ist eine der versteckten Belohnungen in Forever. ForeverSecrets führt in sieben Schritten dorthin, getrennt für Allianz und Horde. Der zweite Teil ist ein Bücher-Tracker mit Fundorten, Koordinaten und Kartenmarkierungen, pro Charakter mitgezählt.

### Node Sight

[www.curseforge.com/wow/addons/node-sight](https://www.curseforge.com/wow/addons/node-sight) · Addon · Kostenlos · **Neu**

<img src="https://media.forgecdn.net/attachments/2040/448/bestestest-before-after-png.png" width="640" alt="Node Sight: Minikarte vorher und nachher">

Statt jeden gelben Punkt abzufahren, siehst du direkt das Icon. Vorkommen, für die dein Skill nicht reicht, sind rot. Auf Wunsch funkeln nahe Vorkommen in der Welt, und ein Pfeil zeigt zum nächsten.

**Gut zu wissen:** Mit rund 33.000 Downloads am Prüftag schon recht bekannt.

### Pagle

[github.com/timemir/pagle-addon](https://github.com/timemir/pagle-addon) · Addon · Kostenlos, Open Source · **Neu**

<img src="https://raw.githubusercontent.com/timemir/pagle-addon/main/docs/readme/01-hero.jpg" width="640" alt="Pagle, ein Angel-Addon">

Benannt nach Nat Pagle. Jeder Wurf landet in einem Logbuch, das alle Charaktere deines Accounts teilen. Daraus entstehen ein Fisch-Journal, Statistiken und, wenn du magst, tägliche Aufgaben am „Tackle Board“. Münzen gibt es für Erreichtes, nicht für Masse.

**Gut zu wissen:** Ausdrücklich kein Bot: Das Addon beobachtet und belohnt, es wirft die Angel nicht aus.

### wow_forever_addons (tobarisu1)

[github.com/tobarisu1/wow_forever_addons](https://github.com/tobarisu1/wow_forever_addons) · Repo (Addon-Sammlung) · Kostenlos, Open Source

Eine persönliche Sammlung mit klarer Haltung: keine Datenbanken aus dem Netz, keine Optionsfenster. GatherMemory merkt sich nur die Vorkommen, die du selbst abgebaut hast. PhatLewtDb führt Buch über deine eigenen Drops. Bedient wird alles über kurze Befehle wie /gm oder /bm.

**Gut zu wissen:** Der Autor baut die Addons für sich selbst, ein Rundum-Support ist nicht zu erwarten. Zwei Namen stimmen in älteren Übersichten nicht: Es heißt PhatLewtDb und OldManQuester.

## Berufe, Camping und Handel

Camping ist neu in Forever: Lagerfeuer geben Buffs, und Berufe stellen Objekte fürs Lager her. Dazu kommt das Auktionshaus, für das es noch kein TradeSkillMaster gibt. Diese Projekte füllen die Lücken.

### ForeverArtisan

[foreverartisan.app](https://foreverartisan.app) · Addon + Webseite · Kostenlos, keine Bezahlstufe

<img src="https://foreverartisan.app/img/shots/04-plan-shopping-list.jpg" width="640" alt="ForeverArtisan: Plan mit Einkaufsliste">

Du nennst einen Zielwert für deinen Beruf, und ForeverArtisan plant die Herstellungen und rechnet die Materialien samt Bezugsquelle und Auktionspreis zusammen. Eine Rangliste zeigt, welche Rezepte nach Auktionshausgebühr Gewinn bringen. Jeder Beruf ist ein eigenes Modul, du lädst nur, was du nutzt.

**Gut zu wissen:** Daten bleiben lokal auf deinem Rechner. Bedienung über /fa, denselben Befehl nutzt auch ForeverAuras.

### Camping Kit

[www.curseforge.com/wow/addons/camping-kit](https://www.curseforge.com/wow/addons/camping-kit) · Addon · Kostenlos

<img src="https://media.forgecdn.net/attachments/2031/325/1_overview-png.png" width="640" alt="Camping Kit im Überblick">

Ein Klick aufs Zelt fächert deine Camping-Sachen auf: Feuer-Set, die Camp-Objekte deiner Berufe, den Cozy Sleeping Bag und vier frei belegbare Plätze für Essen oder Waffenbuffs. Timer zeigen, wie lange Camp Benefits und Well Fed noch laufen. Im Kampf versteckt sich das Ganze.

**Gut zu wissen:** Vom selben Autor (Shuklock) gibt es Warlock Kit, Fishing Kit und First Aid Kit nach demselben Muster.

### Happy Camper

[www.curseforge.com/wow/addons/happy-camper](https://www.curseforge.com/wow/addons/happy-camper) · Addon · Kostenlos · **Neu**

<img src="https://media.forgecdn.net/attachments/1985/764/maphc-png.PNG" width="640" alt="Happy Camper auf der Karte">

Spieler mit dem Addon teilen ihre Feuer untereinander. Du siehst sie auf Welt- und Minikarte, filterst nach den Buffs, die du suchst, und kannst Camp-Anfragen stellen oder ein Gruppenlager planen.

**Gut zu wissen:** Noch Beta. Wie bei allen Addons dieser Art siehst du nur Feuer von Spielern, die dasselbe Addon nutzen.

**Alternativen:** [CampFirePin](https://www.curseforge.com/wow/addons/campfirepin) (Pinnt gefundene Lagerfeuer auf die Minikarte), [S'more Skills](https://github.com/Henrik8210/smore-skills) (Bringt Gastgeber und Suchende am Lagerfeuer zusammen), [Campfire Assistant](https://www.curseforge.com/wow/addons/campfire-assistant-forever) (Zählt Camp-Plätze und warnt vor Buff-Konflikten).

### AHledger

[ahledger.com](https://ahledger.com/) · Webseite + Addon · Kostenlos · **Neu**

Forever hat kein TradeSkillMaster. AHledger schließt die Lücke von der anderen Seite: Du scannst das Auktionshaus mit dem Addon, eine kleine Sync-App lädt den Scan hoch und schreibt etwa halbstündlich frische Preise zurück ins Spiel. Die Webseite zeigt Preisverlauf, Margen und Angebote deutlich unter dem üblichen Preis.

**Gut zu wissen:** Die Preise sind so gut wie die Scans für deinen Markt. Der Quellcode von Sync und Addon ist einsehbar.

**Alternativen:** [Market](https://marketforever.dev) (Auktionshaus- und Berufe-Addon, das AHledger-Preise nutzt), [auxForever](https://github.com/TylerHampton/aux-forever) (Das Auktionshaus-Addon aux, von einem Fan auf Forever gebracht).

## Klassen-Helfer und Ausrüstung

Im Kampf dürfen Addons in Forever vieles nicht mehr auslesen (dazu unten mehr). Diese Addons zeigen, was trotzdem geht, und helfen bei der Frage, welches Teil du anziehen sollst.

### Warlock Kit

[www.curseforge.com/wow/addons/warlock-kit](https://www.curseforge.com/wow/addons/warlock-kit) · Addon · Kostenlos

<img src="https://media.forgecdn.net/attachments/2056/437/warlock-kit-png.png" width="640" alt="Warlock Kit">

Ein Klick auf den Seelensplitter öffnet alles, was ein Hexer braucht: Flüche, Dämonen, Gesundheits- und Seelenstein, Rüstung. Das Addon zählt deine Splitter und löscht auf Wunsch überzählige. Im Raid hört es auf Beschwörungswünsche im Chat und listet, wer gerufen werden will.

**Gut zu wissen:** Das meistgeladene Addon von Shuklock (rund 3.200 Downloads am Prüftag).

### Soul Codex

[www.curseforge.com/wow/addons/soul-codex](https://www.curseforge.com/wow/addons/soul-codex) · Addon · Kostenlos

<img src="https://media.forgecdn.net/attachments/2139/969/every-creature-is-graded-common-to-legendary-png.png" width="640" alt="Soul Codex: jede Kreatur hat eine Seltenheit">

Zieht Drain Soul einen Splitter aus einer Kreatur, bekommt sie eine Seite im Buch, sortiert nach Zone, Familie und Seltenheit von gewöhnlich bis legendär. Bei seltenen Gegnern, die dir noch fehlen, schlägt das Addon Alarm. Deine Splitter in der Tasche wissen, von wem sie stammen.

**Gut zu wissen:** Nur Seelen von Gegnern, die du selbst markiert hast, zählen. Shadowburn zählt nicht.

### Seal Timers Forever

[github.com/Pirson-s-Addons/SealTimersForever](https://github.com/Pirson-s-Addons/SealTimersForever) · Addon · Kostenlos, Open Source

<img src="https://media.forgecdn.net/attachments/1975/669/screenshot_1-png.png" width="640" alt="Siegel-Timer">

Ein kleines Addon für genau eine Aufgabe: das laufende Siegel als Icon mit Countdown. In den letzten Sekunden leuchtet es auf, damit du rechtzeitig nachzauberst. Es erkennt jedes Siegel im Zauberbuch, auch die neuen wie Seal of Fury.

**Gut zu wissen:** Lädt nur auf Forever und nur für Paladine.

### nanShield - Forever

[wago.io/dOv0uSdrf](https://wago.io/dOv0uSdrf) · ForeverAuras-Import · Kostenlos

<img src="https://media.wago.io/screenshots/dOv0uSdrf/6acfe22224aebf4d7dc8b7ec.jpg" width="640" alt="nanShield: Schildbogen um den Charakter">

20 Segmente und eine Zahl darunter: So siehst du auf einen Blick, wie viel Absorption übrig ist, und der Bogen schrumpft live, während der Schild verbraucht wird. Priester bekommen links einen zweiten Bogen für die 20 Aufladungen von Inner Fire.

**Gut zu wissen:** Kein eigenes Addon, sondern ein Import für ForeverAuras. Ältere Übersichten behaupten, der Schild werde aus gelernten Trefferhöhen geschätzt. Laut Beschreibung meldet das Spiel den Wert selbst.

### Naowh Forever

[github.com/naowh-gaming/NaowhForever](https://github.com/naowh-gaming/NaowhForever) · Addon · Kostenlos, Open Source

Ein großes Fenster für vieles, wofür man sonst fünf Addons bräuchte. Die BiS-Liste zeigt je Platz die besten Teile und wo sie fallen, das Dungeon-Journal deckt auch die neuen Dungeons ab, und der Lehrer-Planer sagt, was dich das nächste Level kostet. Dazu kommen Berufe, Makros und ein eigenes Auktionsfenster.

**Gut zu wissen:** Viel Umfang heißt auch viel Oberfläche. Wer nur eine Funktion sucht, ist mit einem Einzel-Addon oft besser bedient.

**Alternativen:** [Pro Item Forever](https://www.curseforge.com/wow/addons/pro-item-forever) (Markiert Upgrades in der Tasche und berät beim Würfeln), [OneForAll](https://github.com/smoergi/OneForAll_Forever) (Zweiter Alles-in-einem-Begleiter mit Ausrüstungsplaner).

## Gilde und Gruppe

Gildenverwaltung, Raidplanung und Welt-PvP: Werkzeuge für alles, was man nicht allein macht.

### GuildOS

[guildos.me](https://guildos.me) · Addon + Discord-Bot + Webseite · Kostenlos, Spenden möglich

Das Addon liest Kader, Ausrüstung, Zugangsquests und Raidteilnahme. Der Bot postet Raidankündigungen in Discord und sammelt Anmeldungen. Die Webseite legt beides übereinander und zeigt, wer zugesagt hat und wer wirklich da war.

**Gut zu wissen:** Die Webseite ist teils portugiesisch. Ein Gründerabzeichen und ein Gildentagebuch, die ältere Übersichten nennen, waren nicht zu finden.

### Innkeeper

[github.com/fmplaw/innkeeper](https://github.com/fmplaw/innkeeper) · Repo (Webportal) · Kostenlos, Open Source (AGPL v3) · **Neu**

<img src="https://raw.githubusercontent.com/fmplaw/innkeeper/main/docs/images/accueil.png" width="640" alt="Innkeeper: Startseite einer Beispielgilde">

Eine Instanz, eine Gilde: Charakterbögen mit Main und Twinks, ein filterbarer Kader, Raidtermine über Raid-Helper und Herstellungsaufträge, die der Bot in Discord ankündigt. Für Gilden, die ihre Daten nicht bei einem fremden Dienst haben wollen.

**Gut zu wissen:** Oberfläche und Dokumentation sind französisch. Du brauchst einen eigenen Server.

### DOINK

[github.com/ryan-flan/DOINK](https://github.com/ryan-flan/DOINK) · Addon · Kostenlos, Open Source · **Neu**

Levelaufstieg, Beute, Tod, Bosskill, neues Reittier, gewonnenes Duell: DOINK kennt neun Arten von Ereignissen und sagt die an, die du auswählst, mit echten Gegenstandslinks. Eine Begleit-App reicht die Meldungen an Discord weiter.

### Overlord Forever

[github.com/leliondoc/overlord-forever-addon](https://github.com/leliondoc/overlord-forever-addon) · Addon · Kostenlos, Open Source · **Neu**

Ein Spiel im Spiel: Gebiete einnehmen, um Gildenfestungen und Außenposten kämpfen, die Wochenkampagne der eigenen Fraktion verfolgen. Kartenziele und Ranglisten kommen vom Addon.

**Gut zu wissen:** Funktioniert nur zwischen Spielern, die das Addon ebenfalls nutzen.

## Rollenspiel, Sprache und Atmosphäre

Nicht alles muss effizienter werden. Diese Projekte machen die Welt hörbar, lesbar oder einfach ein Stück persönlicher.

### WoW Forever Diary

[www.curseforge.com/wow/addons/wow-travel-diary](https://www.curseforge.com/wow/addons/wow-travel-diary) · Addon · Kostenlos

<img src="https://media.forgecdn.net/attachments/2142/468/02_today-png.png" width="640" alt="WoW Forever Diary: die Seite von heute">

Du spielst, das Addon schreibt mit: Quests, Kills, Tode, Beute, Reisewege. Daraus wird ein Buch mit einer Doppelseite pro Tag, einer Weltkarte mit Zeitschieber und einem Bestiarium. Schön sind die Zeitkapseln: Briefe an dich selbst, die bis zu einem bestimmten Tag oder Level versiegelt bleiben.

**Gut zu wissen:** Noch in Arbeit, laut Autor überlebt das Tagebuch aber Updates.

**Alternativen:** [Social Diary](https://www.curseforge.com/wow/addons/social-diary) (Führt Buch über die Spieler, denen du begegnest).

### Spoken

[github.com/rusty-key/spoken-wow](https://github.com/rusty-key/spoken-wow) · Addon · Kostenlos, Open Source · **Neu**

Spoken liest vor, was sonst nur als Text erscheint. Es besteht aus drei Modulen: Quests und NPC-Gespräche, Geschichte zu Zonen und Orten, und alles Lesbare wie Bücher und Briefe. Ein Erzählerfenster oder Untertitel zeigen, wer gerade spricht.

**Alternativen:** [Forever Voiceover](https://github.com/quinn-dougherty/forever-vo) (Vertonung, deren Audio du mit einem lokalen Sprachmodell selbst erzeugst).

### Campfire Tales Forever

[www.curseforge.com/wow/addons/campfire-tales-forever](https://www.curseforge.com/wow/addons/campfire-tales-forever) · Addon · Kostenlos

Setz dich an ein Lagerfeuer, und nach etwa zehn Sekunden macht dein Charakter ein passendes Emote. Sitzen bringt Gespräche und Geschichten, Knien ruhigere Momente, Schlafen Träume. Wer aufsteht, bricht ab. Keine Oberfläche, kein Eingriff in den Kampf.

**Gut zu wissen:** Klein (95 Downloads am Prüftag). In älteren Übersichten als „Campfire Stories“ mit 20 Volksmärchen beschrieben: Der Name stimmt nicht, und Quellen oder eine Zahl nennt die Addon-Seite nicht.

### WoW Forever Japanese

[foreverjapanese.com](https://foreverjapanese.com) · Addon · Kostenlos, Open Source

<img src="https://raw.githubusercontent.com/zyaga/wow-forever-japanese/main/docs/images/hero.jpg" width="640" alt="Questfenster auf Japanisch">

Quests, NPC-Gespräche, Bücher, Tooltips und Fenster erscheinen auf Japanisch. Hältst du Alt, steht wieder das englische Original da. Für Lernende gibt es ein Wörterbuch als Popup und ein Vokabeldeck im Spiel, das sich nach Anki exportieren lässt.

**Gut zu wissen:** Auch ohne Japanisch sehenswert: Das Repo dokumentiert seine Architekturentscheidungen sauber in docs/adr.

**Alternativen:** [Czech Forever](https://czechforever.cz) (Komplette tschechische Übersetzung mit Vertonung), [WordHunter Learning](https://github.com/Ironship/WordHunter-Learning-Forever) (Deutsch lernen beim Questen).

## Entwickler-Tooling und KI

Wer selbst Addons schreibt, steht vor einem Client, der sich wie Retail verhält, aber wie Classic aussieht. Diese Repos dokumentieren die Fallen und liefern Werkzeug.

### forever-addon-kit

[github.com/Thunderz96/forever-addon-kit](https://github.com/Thunderz96/forever-addon-kit) · Repo · Kostenlos, Open Source

Ein Repo voller gemessener Befunde. Der wichtigste: Forever ist technisch der Retail-Client. Viele Retail-Addons prüfen aber, ob die Interface-Nummer mindestens 100000 ist, und Forever meldet 16001. Sie landen deshalb im falschen Codepfad. Das Kit dokumentiert diese und weitere Fallen und bringt Werkzeug zum Portieren mit.

**Gut zu wissen:** Ein Schnappschuss aus der ersten Beta-Woche, zuletzt Ende September aktualisiert. Einiges hat Blizzard seitdem behoben, das Repo vermerkt das zum Teil selbst.

**Alternativen:** [WoW-Addons (Atraeau)](https://github.com/Atraeau/WoW-Addons) (Durchsuchbare API-Referenz, erzeugt aus der Dokumentation des Clients).

### Hated WoW MCP

[github.com/RdyGaming/hated-wow-mcp](https://github.com/RdyGaming/hated-wow-mcp) · Repo (MCP-Server) · Kostenlos, Open Source

Wer Addons mit Claude Code, Cursor oder einem anderen MCP-Client schreibt, kennt das Problem: Das Modell rät API-Namen. Dieser Server liefert die Lua-API des jeweiligen Clients, Blizzards mitgelieferten UI-Code und die Grafikdaten zum Nachschlagen. Ist Forever installiert, wird es ohne Zutun indexiert.

**Gut zu wissen:** Deckt nur ab, was im Client läuft. Keine Battle.net-Web-API, kein Arsenal, kein Auktionshaus.

### WoW UI Simulator

[github.com/Osso/wow-ui-sim](https://github.com/Osso/wow-ui-sim) · Repo · Kostenlos, Open Source · **Neu**

<img src="https://raw.githubusercontent.com/Osso/wow-ui-sim/master/docs/gallery/main-screen.png" width="640" alt="WoW UI Simulator: nachgebauter Hauptbildschirm">

Ein Simulator für die WoW-Oberfläche: Addons testen, Rahmenbäume ausgeben und Screenshots erzeugen, alles ohne Client und auch ohne Bildschirm. Damit lassen sich Addon-Tests automatisieren. Forever steht als eigenes Produkt in der Konfiguration.

### wow-ai

[github.com/chelinho139/wow-ai](https://github.com/chelinho139/wow-ai) · Addon + Begleitprogramm · Kostenlos, Open Source · **Neu**

<img src="https://raw.githubusercontent.com/chelinho139/wow-ai/main/docs/screenshot.jpg" width="640" alt="wow-ai: Chatfenster in Goldshire">

Ein Chatfenster in WoW, an dessen anderem Ende Claude Code, Codex oder ein anderer lokaler Agent sitzt. Addons dürfen nicht ins Netz, deshalb der Trick: Das Addon zeichnet deine Nachricht als Streifen farbiger Quadrate in die Bildschirmecke, ein Begleitprogramm liest ihn per Bildschirmaufnahme ab.

**Gut zu wissen:** Laut Autor wird kein Speicher gelesen und keine Eingabe erzeugt. Ob Blizzard das genauso sieht, ist offen. Ein Experiment.

**Alternativen:** [T3 Code for WoW](https://github.com/ryanrhughes/t3code-wow) (Zeigt laufende Agent-Threads von T3 Code unter deinen Quests).

### forever-bugs

[github.com/ClassicWoWCommunity/forever-bugs](https://github.com/ClassicWoWCommunity/forever-bugs) · Repo (Bug-Tracker) · Kostenlos · **Neu**

Kein Code, sondern Issues nach festem Schema: Was passiert, wie stellt man es nach, welche Quelle belegt das erwartete Verhalten. Nützlich, um zu prüfen, ob ein seltsames Verhalten ein bekannter Fehler ist.

## Plattform-Exoten

Offiziell läuft Forever auf Windows und macOS. Die Community hat es trotzdem auf Linux, Steam Deck, Android-Handhelds, das iPad und sogar die PS5 gebracht.

### Lightforge

[github.com/LightforgeProject/lightforge](https://github.com/LightforgeProject/lightforge) · Programm (Linux) · Kostenlos, Open Source (GPL-3.0)

<img src="https://raw.githubusercontent.com/LightforgeProject/lightforge/main/docs/play.jpg" width="640" alt="Lightforge: die Play-Seite">

Lightforge spricht Blizzards Verteilprotokolle selbst, in Rust neu geschrieben, und legt das Spiel so ab, dass auch der echte Client es lesen kann. Proton-GE lädt und prüft es selbst. Für die anderen Blizzard-Spiele richtet es Battle.net ein und reicht den Start weiter.

**Gut zu wissen:** Trägt die Versionsnummer einer Beta.

### DeckForever

[github.com/eliog/DeckForever](https://github.com/eliog/DeckForever) · Programm (Steam Deck) · Kostenlos, Open Source · **Neu**

<img src="https://raw.githubusercontent.com/eliog/DeckForever/main/docs/screenshots/09-app-window.png" width="640" alt="DeckForever: App-Fenster">

Blizzard unterstützt SteamOS nicht. DeckForever automatisiert den Weg, den die Community ohnehin geht: Battle.net unter GE-Proton als Nicht-Steam-Spiel. Die App kann die Installation auch reparieren, sichern und entfernen. Ein Begleit-Addon bringt Grafikvoreinstellungen mit, die auf dem Deck gemessen wurden.

**Gut zu wissen:** Letzter Stand im Repo von Mitte Oktober, also aus der Beta.

### WoW Foreverywhere

[github.com/YoruDev-Ryland/WoWForeverywhere](https://github.com/YoruDev-Ryland/WoWForeverywhere) · App (Android) · Kostenlos, Open Source (GPL-3.0)

<img src="https://raw.githubusercontent.com/YoruDev-Ryland/WoWForeverywhere/main/.github/readme/home.jpg" width="640" alt="Foreverywhere: Startbildschirm">

Die App lädt das Spiel direkt von Blizzards Servern, hält es aktuell und startet es. Es läuft Blizzards eigener Windows-Client für ARM64 unter Wine, nichts wird als x86 emuliert. Ein Addon-Manager ist eingebaut, und jede Ansicht lässt sich mit dem Controller bedienen.

**Gut zu wissen:** Inoffiziell. Du brauchst ein eigenes Battle.net-Konto mit Forever-Zugang.

**Alternativen:** [WoW Forever for Android](https://github.com/jaredgei/wow-forever-android) (Das ältere der beiden Android-Projekte), [DS Forever](https://github.com/Jreese702/DS-Forever) (Fork für den AYN Thor mit seinen zwei Bildschirmen).

### Tolkara

[github.com/tolkara/tolkara](https://github.com/tolkara/tolkara) · Repo (iPad/iPhone) · Kostenlos, Open Source

Tolkara funktioniert nach dem Vorbild von Wine: Das Programm bleibt unangetastet, nur die Systemaufrufe darunter werden von macOS nach iPadOS übersetzt. Getestet wurde es zuerst mit WoW Classic Era. Laut Repo loggen sich auch der Forever-Client ein und ist spielbar, experimentell sogar auf dem iPhone.

**Gut zu wissen:** Ein Entwicklerprojekt zum Selbstbauen. Du brauchst einen Mac, ein Apple-Entwicklerkonto oder einen Sideloading-Weg und eine eigene, legal erworbene Kopie.

### Forever Launcher (PS5)

[github.com/bizkut/ps5-forever](https://github.com/bizkut/ps5-forever) · Homebrew (PS5) · Kostenlos

<img src="https://img.youtube.com/vi/hlHsBxf-G6Y/maxresdefault.jpg" width="640" alt="Video: Forever Launcher auf der PS5">

Der Launcher lässt Battle.net und WoW über Wine laufen, mit DirectX 12 auf der Grafikeinheit der Konsole. Die mitgelieferten Einstellungen nutzen 4K mit HDR. Tastatur und Maus per USB funktionieren.

**Gut zu wissen:** Alpha, nur mit Jailbreak, und laut Autor ausdrücklich auf eigenes Risiko: Inoffizielle Software an einem Online-Spiel kann Folgen für den Account haben.

## Grauzone: nicht empfohlen

Der Vollständigkeit halber: Projekte, die technisch auffallen, aber gegen Blizzards Nutzungsbedingungen verstoßen. Wer sie benutzt, riskiert seinen Account.

> [!WARNING]
> Die Einträge in diesem Abschnitt sind keine Empfehlung.

### wow-fishing-forever

[github.com/rsamf/wow-fishing-forever](https://github.com/rsamf/wow-fishing-forever) · Repo · Kostenlos, Open Source

Technisch bemerkenswert, weil er weder Speicher liest noch eine Grafikkarte braucht: Er achtet auf das Interaktions-Icon über dem Schwimmer und auf das Platschen. Trotzdem bleibt er ein Bot.

**Gut zu wissen:** Automatisiertes Spielen verstößt gegen Blizzards Nutzungsbedingungen und kann zur Sperre führen. Das schreibt der Autor selbst ins README. Hier nur als Code-Studie genannt. Wer beim Angeln mehr erleben will, nimmt Pagle.

## Was diese Liste nicht ist

- **Keine Rangliste.** Die Reihenfolge innerhalb eines Kapitels ist eine redaktionelle Auswahl, kein Messergebnis.
- **Kein Funktionstest.** Geprüft wurde, ob ein Projekt existiert und was seine Quelle über es sagt. Kein Addon wurde für diese Liste im Spiel installiert und ausprobiert.
- **Keine Garantie für Zahlen.** Download-Zahlen, Guide-Mengen und Preise sind Angaben der jeweiligen Seite vom Prüftag und als solche gekennzeichnet.
- **Eine Momentaufnahme.** Forever ist wenige Tage alt. Viele Projekte tragen noch das Etikett Beta, manche wurden seit der Beta nicht mehr angefasst. Wo das auffiel, steht es beim Eintrag.
- **Nicht vollständig.** Allein auf GitHub liefert die Suche nach Forever-Projekten mehrere tausend Treffer. Hier steht eine Auswahl.

## So wurde geprüft

- **GitHub-Repos:** jedes Repo geklont, README und bei Bedarf einzelne Dateien gelesen, Datum des letzten Commits notiert.
- **CurseForge und Wago:** die Addon-Seite geöffnet und Beschreibung, Autor, letztes Update und Downloads abgelesen.
- **Webseiten:** die Startseite geöffnet und nur übernommen, was dort steht.
- **Bilder:** ausschließlich von der jeweiligen Originalquelle eingebunden, jede Bild-Adresse wurde am Prüftag abgerufen. Einträge ohne brauchbares Bild haben keins.
- **Korrekturen:** Wo ältere Übersichten etwas anderes behaupten als die Quelle, steht die Abweichung unter „Gut zu wissen“.

Die gesamte Datenbasis liegt in [`data/entries.json`](data/entries.json). README und [Webseite](https://kirchlive.github.io/wow-forever-fundstuecke/) werden daraus erzeugt (`tools/gen_readme.py`), die Webseite zeigt zusätzlich die 34 Einträge, die hier nur als Alternative genannt sind.

## Etwas beitragen

Ein Projekt fehlt, ein Link ist tot oder eine Angabe stimmt nicht mehr? Öffne ein Issue oder einen Pull Request. Neue Einträge gehören in `tools/build_data.py`, danach erzeugen `python3 tools/build_data.py` und `python3 tools/gen_readme.py` Datenbasis und README neu. Bitte nur Projekte vorschlagen, die erreichbar sind und erkennbar für Forever gebaut oder angepasst wurden, und keine Bots oder Automatisierung.

---

Fanprojekt ohne Verbindung zu Blizzard Entertainment. World of Warcraft ist eine Marke von Blizzard Entertainment, Inc. Bilder und Namen gehören ihren jeweiligen Urhebern und sind von deren eigenen Seiten eingebunden.
