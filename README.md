# Java_Game_Project
By Sebastian Calzadilla


Game development project on JavaFx.


## Libraries

The javafx-sdk folder contains the JavaFx libraries you will need to install in order to run a JavaFx project like mine.

They will need to be added to the project in properties > Java Build Path > Libraries > Add external JARs...

## Miscellaneous bugs

In case you run into the following error when compiling the project

Error: Could not find or load main class application.Main
Caused by: java.lang.NoClassDefFoundError: javafx/application/Application

Use the following lines in the VM arguments part of the run configuration:

--module-path "\path\to\javafx-sdk-11.0.2\lib"

--add-modules javafx.controls,javafx.fxml

## Credits

The code was adapted and learned from the Youtube channel:

[javacraving](https://www.youtube.com/watch?v=DkIuA5ZEZ_U)

