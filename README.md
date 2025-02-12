# secureshare_backend

## See also

Build a Secure File Sharing App with Rust, Axum, Next.js & ShadCN | End-to-End Encryption</br>
[https://www.youtube.com/watch?v=t5w2dauFmhM]

AarambhDevHub/file-share-rust-backend</br>
[https://github.com/AarambhDevHub/file-share-rust-backend]

AarambhDevHub/file-share-frontend</br>
[https://github.com/AarambhDevHub/file-share-frontend]

## Setting Up the Rust Project
Creating Migrations, Designing the Database Schema

>See Cargo.toml under [dependencies]

## Managing Environment Variables

...

## Installing SQLx-CLI

```
cargo install sqlx-cli --no-default-features --features native-tls,postgres
```

## Creating Migrations, Designing the Database Schema

```
sqlx migrate add tables
```
## Setting Up the Database

```
sqlx database create
sqlx migrate run
```

## Configuring Environment Settings

...

## Defining Data Models

...

## Implementing DTOs with Validation

...