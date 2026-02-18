# MJur: Zotero Zitierstil für juristische Arbeiten 

## Allgemeine Infos

-   Der Zitierstil orientiert sich an in rechtswissenschaftlichen Publikationen weit verbreiteten Zitierweisen.
-   Ziel ist es die zitierte Fundstelle allein anhand der in den jeweiligen Fußnoten dargestellten Informationen ohne große Umwege auffinden zu können. Daher wird auch nicht von einer Fußnote auf andere Fußnoten verwiesen
-   Jede zitierte Quelle soll zudem einfach dem entsprechenden Eintrag im Literaturverzeichnis zuzuordnen sein. Daher werden bspw. ggf. die Begründer der Werke mit aufgeführt, sofern diese noch immer nach diesen zitiert werden oder Eigennamen von Büchern oder Kommentaren den Herausgebern im Literaturverzeichnis vorangestellt.


LOC = Locator, also welche S./Rn./§/… zitiert wird

## Buch (=Book)

### Benötigte Items

-   Autor
-   Titel
-   Auflage (nur Zahl; falls 1. Freilassen)
-   Ort
-   Datum (Jahr genügt)
-   Ggf. Kurztitel
-   Ggf. Herausgeber (=Editor)
-   Ggf. Begründer (=Series Editor)
-   Ggf. Eigenname (bsp.: MüKo; =Translator)

### Zitierweise

#### Fußnote

##### Mit Eigennamen (=Translator):

\<Eigenname\>/\<Autoren\>, LOC.

##### Ohne Eigennamen:

*\<Autoren & Herausgeber\>*, \<Kurztitel; falls nicht vorhanden Titel\>, LOC.

Bsp.: *Vitzthum/Proelß/Bothe*, Völkerrecht, S. 24.

#### Literaturverzeichnis

\<Eigenname (ggf.)\>, \<*Begründer (ggf.)*\> (Begr.)/*\<Herausgeber (ggf.)\>* (Hrsg.)/*\<Autoren\>*, \<Titel\>, \<Auflage\>, \<Ort\> \<Datum (Jahr)\>.

Bsp.: *Vitzthum, Wolfgang Graf (Hrsg.)/Proelß, Alexander (Hrsg.)/Bothe, Michael*, Völkerrecht, 8. Auflage, Berlin/Boston 2019.

Bsp. Kommentar mit Eigennamen: MüKo BGB, *Henssler, Martin/Krüger, Wolfgang*, Münchener Kommentar zum Bürgerlichen Gesetzbuch, 9. Auflage, München 2023.

### Weitere Hinweise

-   Wird eine **Vorauflage** zitiert, muss dies im Kurztitel kenntlich gemacht werden.
-   Für Bücher mit unterschiedlichen Autoren je Kapitel & Kommentare beachte [Kommentar](#kommentar-entry-encyclopedia)

## Kommentar (=Entry-Encyclopedia)

### Benötigte Items

-   *Titel (Dient nur der besseren Übersicht in Zotero; wird nicht zitiert)*
-   Autor
-   Kommentar-Titel (=Encyclopedia Titel)
-   Ggf. Kurztitel
-   Ggf. Herausgeber (=Editor)
-   Ggf. Begründer (=Series Editor)
-   Ggf. **Stand** oder **Vorauflage** (=Extra)

### Zitierweise

#### Fußnote

##### Mit Kurztitel:

\<Kurztitel\>/*\<Autor\>*, \<Extra\>, LOC

Bsp.: MüKo BGB/AuthorLast, Rn. 27; BeckOGK BGB/*Voigt*, Stand 01.02.2025, § 823 Rn. 54.

##### Ohne Kurztitel:

*\<Autor\>*, in: \<Begründer (wenn vorhanden, sonst) Herausgeber\>, \<Kommentar-Titel\>, \<Extra\>, LOC

Bsp.: *Schabas/Pecorella*, in: Ambos, Rome Statute of the ICC, Art. 45, Rn. 23; *Schabas/Pecorella*, in: Ambos, Rome Statute of the ICC, 1. Auflage, Art. 45, Rn. 23; *Schuster/Hunzinger*, in: Schuster/Grützmacher, IT-Recht, § 69c UrhG, Rn. 7.

#### Literaturverzeichnis

Da nicht jedes einzelne Kapitel eines Kommentars ins Literaturverzeichnis aufgenommen werden soll werden hier zunächst folgende Dummy-Einträge als Erinnerung ins Literaturverzeichnis aufgenommen. Diese müssen am Ende der Arbeit manuell entfernt werden:

##### Mit Kurztitel:

**\_\_ reminder \_\_ - \<Kurztitel\>** - \<Titel des Zoteroeintrags\>.

Bsp.: **\_\_ reminder \_\_** - **MüKo BGB**, - (MüKo § 3).

##### Ohne Kurztitel:

**\_\_ reminder \_\_ - \< Kommentar-Titel\>** - \<Titel des Zoteroeintrags\>.

Bsp.: **\_\_ reminder \_\_** - **Ambos, Rome Statute of the ICC**, - (Ambos, Rome Statute of the ICC Art. 35).

### Weitere Hinweise

-   Die Kommentare können als Bücher im **Literaturverzeichnis** aufgenommen werden. Hierzu kann bspw. auf der letzten Seite eine Dummy-Fußnote hinzugefügt werden, in der alle verwendeten Kommentare aufgezählt werden.
    -   Siehe [Buch -\> Literaturverzeichnis -\>](#literaturverzeichnis) Bsp. Kommentar mit Eigennamen.
-   Bücher, deren **einzelne Kapitel unterschiedliche Autoren** haben, und deren einzelne Kapitel nicht jeweils im Literaturverzeichnis aufgeführt werden sollen, müssen wie Kommentare angelegt werden. Das betrifft insbesondere **Handbücher**.

## Urteil (=Case)

### Benötigte Items

-   *Titel (Dient nur der besseren Übersicht in Zotero; wird nicht zitiert)*
    -   *Achtung: Je nach Formatierung des Titels wird hieraus teilweise ein Kurztitel (hier also „Name des Urteils“, s.u.) abgeleitet. Das betrifft insb. Titel die Punkte oder Doppelpunkte enthalten*
-   Ggf. Autor (z.B. für **Schlussanträge** des Generalanwaltes, diese sollten im Feld „Extra“ als solche kenntlich gemacht werden)
-   Gericht (=Authority)
-   Datum (=Date Decided)
-   Aktenzeichen (=Docket Number)
-   Ggf. Name des Urteils (=Kurztitel)
-   Ggf. Veröffentlicht in (=Reporter)
-   Ggf. ECLI (=Rights)
-   Ggf. Extra (insb. für Schlussanträge des Generalanwalts)
-   Ggf. Jahrgang der Zeitschrift (o.ä.) in dem das Urteil veröffentlicht wurde (=Reporter Volume)
-   Ggf. Seitenzahlen (=Page)

### Zitierweise

#### Fußnote

\<Gericht\>, \<Extra (ggf.)\> \<*Autor (ggf.)*\>, \<*Name des Urteils (ggf.)*\>, \<Datum\>, \<Aktenzeichen\>, \<ECLI (ggf.)\> veröffentlicht in \<veröffentlicht in (ggf.)\> \<Reporter Volume (ggf.)\>, \<Erste Seite (ggf.)\>, LOC.

Bsp.: BGH, 10.11.2022, 5 StR 283/22, veröffentlicht in NJW 2023, 123, 124; International Criminal Court, *The Prosecutor v. Omar Hassan Ahmad Al Bashir*, 4.3.2009, ICC-02/05-01/09; EuGH, *Top System*, 10.6.2021, C‑13/20, ECLI:EU:C:2021:811, Rn. 50; EuGH, Schlussanträge des Generalanwalts *Szpunar*, *Top System*, 3.10.2021, C-13/20, ECLI:EU:C:2021:193, Rn. 59.

#### Literaturverzeichnis

\- wird nicht aufgeführt -

## Dokument

### Benötigte Items

-   Titel (Falls eine Organisation „Autor“/Herausgeber des Dokumentes ist, muss dies hier ebenfalls genannt werden, bspw.: „OHCHR, Ukraine - civilian casualty update“
-   Datum
-   URL
-   Hinzugefügt am (=Date added)
-   Ggf. Autor (Nur natürliche Personen, **wird kein Autor genannt, muss die Organisation im Titel genannt werden**)
-   Ggf. veröffentlichende Organisation (=Publisher)
-   Ggf. Dokumentennummer (=Archive)

### Zitierweise

#### Fußnote

##### Mit Autor:

*\<Autor\>*, \<Kurztitel (oder Titel, Publisher)\>, \<Dokumentennummer (ggf.)\>, \<Datum\>, LOC.

Bsp.: *Balaban/Boehm/Brodowski u. a.*, Whitepaper zur Rechtslage der IT-Sicherheitsforschung - Reformbedarf aus Sicht der angewandten Sicherheitsforschung, FZI, S. 13

##### Ohne Autor:

\<Publisher\>, \<Kurztitel, bzw. Titel\>, \<Dokumentennummer (ggf.)\>, \<Datum\>, LOC.

Bsp.: UN-Generalversammlung, Resolution, A/RES/ES-11/1, 2.3.2022, S. 24.

#### Literaturverzeichnis

*\<Autor (ggf.)\>*, \<Titel\>, \<Dokumentennummer (ggf.)\>, \<Datum\>, \<URL\>, zul. abger. \<Hinzugefügt am\>.

Bsp.: UN-Generalversammlung, Resolution, A/RES/ES-11/1, 2.3.2022, https://undocs.org/A/RES/ES-11/1, zul. abger. 21.9.2023.

## Website

### Benötigte Items

-   Titel
-   Website-Titel
-   Hinzugefügt am (=Date added)
-   URL
-   Ggf. Autor
-   Ggf. Datum

### Zitierweise

#### Fußnote

##### Mit Autor:

*\<Autor\>*, \<Titel\>, \<Website-Titel\>, \<Datum; sonst Hinzugefügt am\>.

Bsp.: *Dannenbaum*, Mechanisms for Criminal Prosecution of Russia’s Aggression Against Ukraine, Just Security, 10.3.2022.

##### Ohne Autor:

\<Website-Titel\>, \<Titel\>, \<Datum; sonst Hinzugefügt am\>.

Bsp.: FAZ.NET, Studie: Große Mehrheit will Ausbau der Verteidigungsfähigkeit, 13.2.2024; Europarat, 46 Mitgliedstaaten, zul. abger. 13.2.2024.

#### Literaturverzeichnis

##### Mit Autor:

*\<Autor\>*, \<Titel\>, \<Datum (ggf.)\>, \<URL\>, zul. abger. \<Hinzugefügt am\>.

Bsp.: *Dannenbaum, Tom*, Mechanisms for Criminal Prosecution of Russia’s Aggression Against Ukraine, 10.3.2022, https://www.justsecurity.org/80626/mechanisms-for-criminal-prosecution-of-russias-aggression-against-ukraine/, zul. abger. 5.2.2024.

##### Ohne Autor:

\<Website-Titel\>, \<Titel\>, \<Datum (ggf.)\>, \<URL\>, zul. abger. \<Hinzugefügt am\>.

Bsp.: FAZ.NET, Studie: Große Mehrheit will Ausbau der Verteidigungsfähigkeit, 13.2.2024, https://www.faz.net/aktuell/politik/inland/studie-grosse-mehrheit-will-ausbau-der-verteidigungsfaehigkeit-19515825.html, zul. abger. 13.2.2024.

Europarat, 46 Mitgliedstaaten, https://www.coe.int/de/web/portal/46-members-states, zul. abger. 13.2.2024.

## Artikel (= Journal Article)

### Benötigte Items

-   Autor
-   Journal-Titel (=Publication)
-   Ggf. Journal-Kurztitel (=Journal Abbr)
-   Datum (Jahr genügt)
-   Seiten (=Pages)
-   Ggf. Ausgabe (=Issue; Nur falls es mit in die Fußnote und ins Literaturverzeichnis aufgenommen werden soll. sonst freilassen)

### Zitierweise

#### Fußnote

##### Ohne Ausgabe:

*\<Autor\>*, \<Journal-Kurztitel; sonst Journal-Titel\> \<Datum (Jahr)\>, \<Erste Seite\>, LOC.

Bsp.: *Morlok/Hientzsch*, JuS 2011, 1, 2; *Heller*, Journal of Genocide Research 2022, 1, 15.

##### Mit Ausgabe:

*\<Autor\>*, \<Journal-Kurztitel; sonst Journal-Titel\> \<Ausgabe\>/\<Datum (Jahr)\>, \<Erste Seite\>, LOC.

Bsp.: *Gubitz/Buchholz*, wistra 9/2018, 369, 372.

#### Literaturverzeichnis

##### Ohne Ausgabe:

\<Autor\>, \<Titel\>, \<Journal Titel\> \<Datum (Jahr)\>, S. \<Seiten\>.

Bsp.: *Morlok, Martin/Hientzsch, Christina*, Das Parlament als Zentralorgan der Demokratie - Eine Zusammenschau der einschlägigen parlamentsschützenden Normen, Juristische Schulung 2011, S. 1–9.

*Heller, Kevin J.*, Options for Prosecuting Russian Aggression Against Ukraine: A Critical Analysis, Journal of Genocide Research 2022, S. 1–24.

*Mit Ausgabe:*

\<Autor\>, \<Titel\>, \<Journal Titel\> \<Ausgabe\>/\<Datum (Jahr)\>, S. \<Seiten\>.

Bsp.: *Gubitz, Michael/Buchholz, Momme*, Strafbarkeitsrisiken Im Holzhandel, wistra: Zeitschrift für Wirtschafts- und Steuerstrafrecht 9/2018, 369–372.

## Kapitel (=Book-Section)

### Benötigte Items

-   Autor
-   Buchautor
-   Kapiteltitel (=Titel)
-   Buchtitel
-   Buch-Auflage (Falls 1. Freilassen)
-   Ort
-   Datum (Jahr genügt)
-   Seiten
-   Ggf. Buch-Kurztitel (=Short Title)
-   Ggf. Buchherausgeber (=Editor)

### Zitierweise

#### Fußnote

\<Autor\>, in: \<Buch-Kurztitel, sonst Buchtitel\>, LOC.

Bsp.: Bachmann, in: FS Schmidt, S. 45

#### Literaturverzeichnis

\<Autor\>, \<Kapiteltitel\>, in: \<Buchautoren & -herausgeber\>, \<Buchtitel\>, \<Ort\> \<Datum (Jahr)\>, S. \<Seiten\>.

Bsp.: *Bachmann, Gregor*, Die Änderung personengesellschaftsrechtlicher Satzungsbestandteile bei der KGaA, in: Bitter, Georg (Hrsg.), Festschrift für Karsten Schmidt zum 70. Geburtstag, Köln 2009, S. 41–57.

### Weitere Hinweise

-   Für Bücher mit unterschiedlichen Autoren je Kapitel & Kommentare beachte II. Kommentar

## Bundestagsdrucksachen (=Manuscript)

Empfohlene Abkürzung für Bundestagsdrucksache: „**BT-Drs.“**

(und andere Quellen, die keine Erwähnung im Literaturverzeichnis finden sollen)

### Benötigte Items

-   Titel
-   Ggf. Kurztitel
-   Ggf. Autor
-   Ggf. Datum

### Zitierweise

#### Fußnote

\<Autor (ggf.)\>, \<Titel oder Kurztitel\>, \<Datum\>, LOC.

Bsp.: BT-Drs. 12/4022, 18.2.1992, S. 5.

#### Literaturverzeichnis

\- wird nicht aufgeführt –

## Gesetze

Ermöglicht vor allem die Zitation von Erwägungsgründen in der Fußnote

Empfohlene Abkürzung für Erwägungsgrund: ErwG

### Benötigte Items

-   Public Law Number
-   Ggf. Kurztitel

### Zitierweise

#### Fußnote

\<Kurztitel (ggf.)\>, \<Public Law Number\>, LOC.

Bsp.: Datenbank-RL, RL 96/9, ErwG 46.

#### Literaturverzeichnis

\- wird nicht aufgeführt –

## Vortrag/Presentation

### Benötigte Items

-   Autor
-   Titel
-   Ggf. Kurztitel
-   Meeting Name (Name der Veranstaltung?)
-   Ggf. URL der Aufzeichnung
-   Datum

### Zitierweise

#### Fußnote

*\<Autor\>*, \<Titel oder Kurztitel\>, \<Meeting Name\>, \<Datum\>, \<LOC\>.

Bsp.: *Kaspar*, Projekt Bucketchallenge, 38. Chaos Communication Congress, 28.12.2024.

#### Literaturverzeichnis

*\<Autor\>*, \<Titel oder Kurztitel\>, \<Meeting Name\>, \<Datum\>, \<URL\>.

Bsp.: *Kaspar*, Projekt Bucketchallenge, 38. Chaos Communication Congress, https://media.ccc.de/v/38c3-projekt-bucketchallenge.

