Four In A Line is a multiplayer Connect Four game. It can be played on a network, or against an AI game player.

The AI game player uses the algorithm developed by Keith Pomakis but then rewritten in Java.

The network layer uses RMI without using the callback pattern, which ensures that the game will be compliant with firewalls.

Connect Four is a trademark of Hasbro. I designated an implementation of the game and an AI player of it, but not the game itself.

In case you want to reuse some parts of the project in a proprietary product, please contact me for licensing issues at address |julien\_aubin\_lm| #AT# /yahoo/ DOT `fr` .


**Update information** : the new version, 1.3.6, now supports to be installed in a location which does not contain spaces. It requires a JVM 1.6+ and brings a huge speed improvement when using the AI player, two new AI strength levels and a better UI.

**System requirements**

- Linux/Unix

- Windows

- MacOS

- Java 1.6 or higher, downloadable from http://java.sun.com

**Launching the game**
- Extract the ZIP archive in a directory of your choice.

- Windows users : double click the fourinaline.jar file.

- Linux/Unix and MacOS users : depending on the environment you have, double click the fourinaline.jar file or launch the following command : `java -jar fourinaline.jar`

**Note to Linux users**

The game won't work with the GNU Classpath JVM. Please ensure that you have installed properly the official Sun JVM, or even the OpenJDK JVM. Note that under the OpenJDK JVM fonts may look ugly, especially if the Metal look and feel is used under your environment.

Then you must run the update-alternatives tool to ensure that the following commands point to the official Sun JVM commands :

java

rmiregistry

If you want to compile the game, you must also ensure that the following commands point to the official Sun JVM commands :

javac

rmic