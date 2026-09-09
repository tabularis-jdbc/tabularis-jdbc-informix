# tabularis-jdbc-informix

Informix driver for [Tabularis](https://tabularis.dev), powered by JDBC and [JBang](https://jbang.dev).

Part of the [tabularis-jdbc](https://github.com/tabularis-jdbc/tabularis-jdbc) family — a single generic JDBC engine packaged per database with the right Tabularis capabilities.

## Install

Download the latest release zip from [Releases](https://github.com/tabularis-jdbc/tabularis-jdbc-informix/releases), extract into the Tabularis plugins folder:

| Platform | Path |
|----------|------|
| macOS    | `~/Library/Application Support/tabularis/plugins/jdbc-informix/` |
| Linux    | `~/.local/share/tabularis/plugins/jdbc-informix/` |
| Windows  | `%APPDATA%\tabularis\plugins\jdbc-informix\` |

Restart Tabularis. **Informix** appears in the connection catalogue.

## Connection

Use the database field with a JDBC URL (the `jdbc:` prefix is optional):

```
informix-sqli://localhost:9088/mydb
```

## Requirements

- Java 17+ (JBang bootstraps itself)

## Development

This plugin is generated from [tabularis-jdbc](https://github.com/tabularis-jdbc/tabularis-jdbc). To modify the core JDBC engine, contribute there.
