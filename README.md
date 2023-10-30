# Java Application Project README

When you build a Java application project that has a main class, the IDE automatically copies all of the JAR files on the project's classpath to your project's `dist/lib` folder. The IDE also adds each of the JAR files to the `Class-Path` element in the application JAR file's manifest file (`MANIFEST.MF`).

## Running the Project

To run the project from the command line, follow these steps:

1. Navigate to the `dist` folder.
2. Type the following command:

```bash
java -jar "Notepad.jar"
