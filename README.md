# Praktikum 12: Framework Lanjutan (CRUD)

## Membuat Database: Studi Kasus Data Artikel

## <u>Membuat Database</u>

`CREATE DATABASE lab_ci4;`

## <u>Membuat Tabel</u>

``
CREATE TABLE artikel (
id INT(11) auto_increment,
judul VARCHAR(200) NOT NULL,
isi TEXT,
gambar VARCHAR(200),
status TINYINT(1) DEFAULT 0,
slug VARCHAR(200),
PRIMARY KEY(id)
);
``