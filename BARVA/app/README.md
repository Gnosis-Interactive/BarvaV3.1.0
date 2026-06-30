# Java Bar Sim v3

**A sophisticated pub management simulation game built in Java Swing.**

## Quick Start

```bash
# Windows (fallback-safe; Nimbus if FlatLaf jar not present)
javac -encoding UTF-8 -cp "libs/*;." *.java
java -cp "libs/*;." Main

# Linux/macOS
javac -encoding UTF-8 -cp "libs/*:." *.java
java -cp "libs/*:." Main
```

Optional visual enhancement: add `libs/flatlaf-3.4.jar` (see `libs/README.md`).

**Requirements**: JDK 17+ (uses Java records)

## FlatLaf (recommended visual theme)

`UiTheme.apply()` will use FlatLaf automatically when the FlatLaf jar is on the classpath, and will safely fall back to Nimbus otherwise.

1. Download `flatlaf-<version>.jar` from the FlatLaf releases/Maven page.
2. Place it in `libs/` (this repository now includes the `libs/` folder).
3. Compile and run with classpath including `libs/*`:

```bash
javac -encoding UTF-8 -cp "libs/*:." *.java
java -cp "libs/*:." Main
```

Fallback mode (no FlatLaf jar) still works:

```bash
javac -encoding UTF-8 *.java
java Main
```

## Documentation

All documentation has been moved to the **[UserGuide](UserGuide/)** folder:

- **[README.md](UserGuide/README.md)** - Complete project overview and getting started guide
- **[PLAYER_GUIDE.md](UserGuide/PLAYER_GUIDE.md)** - Complete gameplay guide with strategies and all systems
- **[DRIVER_MECHANICS_GUIDE.md](UserGuide/DRIVER_MECHANICS_GUIDE.md)** - Deep dive into service/stability drivers
- **[GAME_DESCRIPTION.md](UserGuide/GAME_DESCRIPTION.md)** - Detailed design document and mechanics
- **[DEVELOPER_GUIDE.md](UserGuide/DEVELOPER_GUIDE.md)** - Technical reference for developers and modders
- **[DevNotes.md](UserGuide/DevNotes.md)** - System integration and architecture notes

## Credits

**Design & Development**: LuxZen-Tao  
**Platform**: Java Swing (cross-platform)

**Your pub awaits. Make your choices count.**
