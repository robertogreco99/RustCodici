# Cargo

- si crea un nuovo progetto con 
  ``` cargo new project_name ```
- si crea una libreria con 
 ```cargo new --lib library_name (questo serve per creare una libreria)  ```
- si compila con ```cargo build```
- si esegue un progetto con ```cargo run```

## Cargo.toml

- [package] : fornisce informazioni sul progetto corrente 
- [dependencies] : posso indicare le eventuali librerie che il progetto intende utilizzare 

## Cargo.lock

- trovo tutte le librerie risolte ricorsivamente, tutte esplicitate con la loro versione

## Target

- c'è un file che si chiama CACHEDIR.TAG e un json (descrive dettagli della compilazione)