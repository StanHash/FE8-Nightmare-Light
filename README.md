# FE8 Nightmare Modules : Better Edition

This is a small collection of FE8 Nightmare Modules for use with the buildfile method. They were simplified, clarified and corrected compared to their original counterpart.

My goal here is to only include modules for tables that are not easily and/or conveniently able to be edited through the buildfile method. This includes tables for Items/Characters/Class but excludes tables for like Pointer Arrays (let alone the "tables" for crit bonus and whatnot).

[For more information on how to use the buildfile method to build a GBAFE hack, check this guide.](https://tutorial.feuniverse.us)

# Included CSVs

The CSV Included here are provided with pre-filled fields that should be more readable than raw ripped csvs (some cells have had their content replaced with definitions). As long as you use the definitions included with this, the csv should represent the vanilla tables.

# HOW TO USE

In your buildfile project, make a folder for your tables (if that is not already done that is), download [circles' n2c/c2ea tools](http://feuniverse.us/t/nmm2csv-edit-tables-with-excel-instead-of-nightmare-updated-to-v1-0/1748?u=stanh) and put that in that folder, then take the whole thing from this folder and put it there too (*do* replace the `Table Definitions.txt` file). Then run c2ea (and NOT n2c or else you'll regenerate csvs, which would be missing the point of them being pre-filled) and include the generated `Table Installer.event` into your rom buildfile and voilà (the tutorial linked above probably explains this 776x better)

# I found an error/I want another Table

If you found an error and know how to github, you can pull request a fix right away. (If you don't know how to github and/or are lazy you can also contact me about it of course.)

If you have suggestions about other tables that should be included, feel free to ping me on the [FEU Topic](http://feuniverse.us/t/fe8-updated-nightmare-module-package-for-use-with-the-buildfile-method/2307) or the [FEU Discord](http://feuniverse.us/t/feu-discord-server/1480).
