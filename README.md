# Advent of Code 2026

Meine Lösungen für [Advent of Code 2026](https://adventofcode.com/2026), geschrieben in Rust. Das Projekt ist für die 24 Tage vom 1. bis 24. Dezember vorbereitet.

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

Für jeden Tag gibt es ein Modul `src/dayNN.rs`; die Tagesauswahl befindet sich in `src/lib.rs`. Die Module enthalten zunächst einen Platzhalter, bis das jeweilige Rätsel veröffentlicht ist. Ergänze beim Lösen Tests mit den Beispielen aus der Aufgabenstellung.

## CI

GitHub Actions prüft bei Pushes auf `main`, Pull Requests und manuellem Start Formatierung, Clippy und `cargo test` für alle Targets und Features. Die Tests in den Tagesmodulen können die Beispiel-Eingaben und -Ergebnisse der jeweiligen Aufgaben abdecken.

Lokal ausführen:

```sh
cargo fmt --all -- --check
cargo clippy --all-targets --all-features -- -D warnings
cargo test --all-targets --all-features
```
