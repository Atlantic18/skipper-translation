Archive contains empty language file for your translations and folders with gui elements.
Keep the folder structure intact so you can see the dialogue windows in QT Linguist:

1. Extract the archive on your computer
2. Use QT linguist from \linguist and open the src\Translations\*.ts file

If you want to prepare new translation simply copy the texts_empty.ts under new name. From the text header remove the language identifier:

e.g. turn this:
<?xml version="1.0" encoding="utf-8"?>

<!DOCTYPE TS>

<TS version="2.0" language="cs_CZ">

into this:
<?xml version="1.0" encoding="utf-8"?>

<!DOCTYPE TS>

<TS version="2.0">

and open the new .ts file in QT Linguist, you will be prompted to set a new language upon loading of the file.