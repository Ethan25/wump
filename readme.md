Request Message Format:
--------------------------------
| COMMAND | SP | ARGUMENT | \n |
--------------------------------

Where COMMAND is one of the following (with argument):
JOIN player_name
HELP optional_section
MOVE target_room
SHOOT target_room
QUIT

Response Message Format:
-----------------------------------------------------------------
| CODE | message                                           | \n |
-----------------------------------------------------------------
| CURRENT_ROOM                                             | \n |
-----------------------------------------------------------------
|ADJ_RM_COUNT | SP | ADJ_RM1 | SP | ADJ_RM2 | SP | ADJ_RM3 | \n |
-----------------------------------------------------------------
| messages                                                 | \n |
-----------------------------------------------------------------

