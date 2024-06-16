# Grinder
Paper fork for the use on grindclub.eu
The goal is to optimize Paper more for networks.

How To (Compiling Jar From Source)
------
To compile, you need JDK 21 and an internet connection.

Clone this repo, run `./gradlew applyPatches`, then `./gradlew createMojmapBundlerJar` from your terminal. You can find the compiled jar in the project root's `build/libs` directory.

To get a full list of tasks, run `./gradlew tasks`.
