

<br/>
<div align="center">
<h1 align="center">🛠️ Rust Prisma Boilerplate</h1>
<p align="center">

A streamlined starting point for integrating **Prisma Client Rust** into your projects
<br/>
<a href="https://github.com/ShaanCoding/makeread.me/wiki"><strong>Explore the docs »</strong></a>
<br/>
</p>
</div>





This boilerplate leverages the powerful **Prisma Client Rust** tool by [Brendonovich](https://github.com/Brendonovich/prisma-client-rust) to simplify database interactions in Rust.This project was set up using the guidance of the video tutorial by [Wander Watterson](https://youtu.be/G3PvtKklJX0?si=UJ2iY4xaZZK6INBY), making it easier for you to kickstart A Rust and Prisma Project.


## 🛠️ Installation

### 1. Install Cargo Generate
To begin, install **Cargo Generate**:

```bash
cargo install cargo-generate
```

### 2. Generate the Boilerplate
Create a new project using the following command:

```bash
cargo generate --git https://github.com/notenderdreams/Rust-Prisma-Boilerplate.git
```

Now, Give  your project a name and it's ready to go!



## ⚙️ Configuration

### 1. Set the Database Provider
In the `schema.prisma` file, define the database provider in the `datasource` block. Supported providers include:

- PostgreSQL
- MySQL
- SQLite
- SQL Server
- MongoDB
- CockroachDB

### 2. Configure the Database URL
Update the `DATABASE_URL` in the `.env` file to point to your database.

### 3. Pull the Database Schema (Optional)
If you already have an existing database, run the following command to generate a Prisma schema based on your database:

```bash
cargo prisma db pull
```

### 4. Define Your Models
Customize your `schema.prisma` file by adding your application-specific models.

### 5. Generate the Prisma Client
Once your models are defined, generate the Prisma Client by running:

```bash
cargo prisma generate
```

### 6. Push Changes to the Database
To apply the schema changes to your database, run:

```bash
cargo prisma db push
```

---

## 📚 Resources

- [📑Prisma Client Rust Documentation](https://prisma.brendonovich.dev/)

- [🎬 Video Tutorial](https://youtu.be/G3PvtKklJX0?si=UJ2iY4xaZZK6INBY)



<div align="center">
<a href="https://github.com/notenderdreams/Rust-Prisma-Template/issues/new?labels=bug&amp;template=bug_report.md">Report Bug .</a>
<a href="https://github.com/notenderdreams/Rust-Prisma-Template/issues/new?labels=enhancement&amp;&template=feature_request.md">Request Feature</a>
</div>