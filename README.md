server-data
===========

The Server Files

Dies sind die ServerFiles von TheManaWorld,
Informationen zum Kompilieren findet ihr unter: http://wiki.themanaworld.org/index.php/Setting_up_eAthena_on_Linux

Naming Konventions
==================

Um die Ordnung innerhalb des Codes zu wahren, wurde eine Konvention definiert,
welche deutlich besagt, dass die Startblöcke der NPC's(L_) folgend benannt werden
müssen:
   * Im Englischen Bereich wird einfach nur ein "L_" genutzt. Beispiel: L_Start
   * Beim Deutschsprachigen Bereich der NPC-Dateien wird vorranstehend "LG_" genutzt. Beispiel: "LG_Start"
   * Desweiteren ist darauf zu achten, dass der Name des Fertigen Npc in diesen klammern
    "[ ]" geschrieben wird. Bsp.: "001-1.gat,110,71,0|script|Sandra|114,"  wird zu  "001-1.gat,110,71,0|script|[Sandra]|114,"
   * Bugs bzw. Tickets("Issues") werden in den Checklisten(Benannt nach
    Npc_Checklist Map-Submap.txt) nach "DONE#ISSUE-NUMMER" erstellt/eingefügt. Beispiel: "//*DONE--is#99*//"
    für Ticket Nr. 99.
