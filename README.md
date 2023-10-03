# cal - proleptic gregorian month calendar with coloring

This app tries to match `wsl ncal 10 2023 -b` output and was written as an excersize from the Command-Line Rust book. It doesn't follow the book solution though, but retains much of the tests (that were fixed to allows weeks that start on Monday, colorization and a different way to render the calendar).

Separating the codebase into a standalone repository allows to install `cal` as a tool on any OS:

```ps1
cargo install -f --git https://github.com/FallenGameR/Calendar
```
