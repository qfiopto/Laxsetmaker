Lacrosse Play Designer – Instruction Manual

Overview

The Lacrosse Play Designer is a web-based tool that allows you to
design, save, load, animate, and export lacrosse plays.
It includes full and half-field views, player role selection (Attack,
Midfield, Defense, SSDM, LSM, Goalie), route drawing, ball toggling,
play animation, and PDF/export options.

------------------------------------------------------------------------

Features

-   Add Players: Place players of different roles (A, M, D, SSDM,
    LSM, G) onto the field.
-   Drag & Drop: Move players to custom positions by dragging them.
-   Add Routes: Draw routes for players with customizable curves (High,
    Slight, Hook).
-   Route Editing:
    -   Toggle Curve: Flips the curve direction of a route.
    -   Delete Route: Removes the last route segment for the selected
        player.
-   Ball Control: Assign or remove a ball from a player. Ball moves with
    player.
-   Save & Load Plays:
    -   Save plays to local storage in your browser.
    -   Load saved plays from a dropdown menu.
    -   Delete saved plays if no longer needed.
    -   Download a play file to your computer, and re-load it later.
-   Play Animation:
    -   Start Play: Players move along their routes smoothly over ~3
        seconds.
    -   Reset Play: Resets all players to their starting positions and
        clears movement.
-   Field Modes:
    -   Switch between Full Field and Half Field.
-   Export PDF:
    -   Export all saved plays into a single PDF document with field
        diagrams.
-   Export/Import Plays:
    -   Export plays as downloadable JSON files.
    -   Import JSON files back into the tool to restore saved plays.

------------------------------------------------------------------------

Controls

Top Controls

-   Play Name Box → Type a name before saving a play.
-   Save Play → Saves the current play into local storage.
-   Load Play → Loads the currently selected play from the dropdown.
-   Delete Play → Removes the currently selected play.
-   Saved Plays Dropdown → Select between stored plays.

Player Controls

-   Role Select Dropdown → Choose the role (A, M, D, SSDM, LSM, G).
-   Add Player → Places a new player on the field.
-   Delete Player → Removes the selected player.
-   Toggle Ball → Adds/removes a ball from the selected player.

Route Controls

-   Route Type Dropdown → Choose High Curve, Slight Curve, or Hook.
-   Add Route → Adds a route from the selected player.
-   Toggle Curve → Flips the route curve direction.
-   Delete Route → Removes the last route from the selected player.

Play Animation

-   Start Play → Animates all players along their routes (approx. 3
    seconds).
-   Reset Play → Returns all players to starting positions and stops
    animation.

Exporting

-   Export PDF → Generates a PDF of all saved plays.
-   Export Play (Download) → Saves plays to your computer as .json file.
-   Import Play (Upload) → Loads .json file back into the designer.

Field Mode

-   Full/Half Field Dropdown → Switches between full and half-field
    layouts.

------------------------------------------------------------------------

Mouse & Touch Controls

-   Click/Tap Player → Selects player (highlighted in blue glow).
-   Drag Player → Move player around the field.
-   Click/Tap Route Dot → Move or drag to adjust a route endpoint.

------------------------------------------------------------------------

Storage & Files

-   Plays are automatically saved in your browser’s localStorage
    (persists until cleared).
-   Plays can also be exported to .json files for backup or sharing.
-   Use the Import Play button to reload .json files into the designer.
-   PDF export creates a multi-page PDF with field diagrams of each
    play.

------------------------------------------------------------------------

Tips

-   Always name your play before saving.
-   If switching plays, clear unused players to avoid overlap.
-   Use the Reset Play button after animation to restore positions.
-   Export regularly to back up your work.
