# Rhythm Game Online: Modcharting Documentation
Welcome to the modcharting guide for the game.
This will go over all of the functions in the system.

## Functions
### `getObjectNumber(direction)`
Returns the strum clip with the direction of `direction`.

### `setNoteY(target, newY)`
Moves the corrosponding strum to `newY`.

### `setNoteX(target, newX)`
Moves the corrosponding strum to `newX`.

### `setNoteOpacity(target, newAlpha)`
Gives `target` an opacity of `newAlpha`.

### `setNoteRotation(target, newAngle)`
Rotates `target` to `newAngle`.

### `switchNoteYPos(isInit)`
Used to move the notes to the correct positions (`isInit`), does not work otherwise for some reason.

The getting functions (`getNoteY`, `getNoteX`, `getNoteOpacity`, `getNoteRotation`) are all self-explanatory.

## Variables
### `showOnlyNotes`
If checked, everything disappears but the notes.
