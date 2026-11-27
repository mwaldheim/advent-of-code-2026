# Advent of Code 2026

Meine Lösungen für [Advent of Code 2026](https://adventofcode.com/2026), geschrieben in Rust.

## Voraussetzungen

- Rust stable (Edition 2024)

## Ausführen

Lege den persönlichen Input für Tag 1 unter `inputs/day01.txt` ab und starte:

```sh
cargo run -- 1
```

Alternativ kann der Input-Pfad explizit angegeben werden:

```sh
cargo run -- 1 path/to/input.txt
```

Die persönlichen Input-Dateien unter `inputs/` werden nicht versioniert.

## Lösungen ergänzen

Die Tagesauswahl befindet sich in `src/lib.rs`; die jeweilige Lösung kommt in `src/dayNN.rs`. `src/day01.rs` dient als Vorlage. Tests starten mit:

```sh
cargo test
```
