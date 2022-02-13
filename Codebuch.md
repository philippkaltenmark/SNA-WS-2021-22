# Datensatz Bundestagsabgeordnete #
Codebuch Stand 2022-02, aktualisiert 2022-02
erstellt von Philipp Kaltenmark (pk092@hdm-stuttgart.de)

## Inhalt
- Nodes.csv (Nodelist)
- Edges.csv (Edgelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung

Das Netzwerk ist ein *ungerichtetes two-mode Akteursnetzwerk*.


# NODE-Attribute  
  
**id**  
Identische ID wie aus der edgelist zur eindeutigen Identifikation der Knoten.

**name_short**
Nachname der PolitikerInnen

**name**
Name der PolitikerInnen/Organisationen

**sex**    
Bitte geben Sie ihr Geschlecht an:  
1 = männlich 
2 = weiblich 
3 = divers
  
**birth**
Geburtsjahr

**position**
Aktuelle Position im Bundestag

1 = StaatssekretärIn
2 = BundesministerIn
3 = StaatsministerIn

**education**
höchster Bildungsabschluss

1 = Promotion
2 = Diplom
3 = Staatsexamen
4 = Sonstiges

**party**
Parteizugehörigkeit

1 = SPD
2 = DIE GRÜNEN
3 = FDP

**religion**
Religion

1 = katholisch
2 = evangelisch
3 = muslimisch

**kids**
Anzahl der Kinder

**twitter**
Anzahl der Twitter-FollowerInnen

1 = < 5000
2 = 5000 - 10000
3 = 10000 - 20000
4 = > 20000

**instagram**
Anzahl der Instagram-FollowerInnen

1 = < 3000
2 = 3000 - 5000
3 = > 5000

**facebook**
Anzahl der Facebook-FollowerInnen

1 = < 5000
2 = 5000 - 10000
3 = 10000 - 20000
4 = > 20000

**youtube**
Anzahl der YouTube-AbonnentInnen

1 = < 35
2 = 35 - 50
3 = 50 - 100
4 = > 100


# EDGE-Attribute

**id**  
eindeutige Codierung des Knoten

**relationship**
Art der Verbindung der PolitikerInnen zu Organisationen

1 = Ministerium
2 = politische Funktionen
3 = Ehrenamt
4 = Unternehmen und Aufsichtsräte
5 = Stipendien
6 = Berufstätigkeiten
7 = Studienort im In- und Auslands

**year**
Jahr, in dem Variable relationship erhoben wurde

##
