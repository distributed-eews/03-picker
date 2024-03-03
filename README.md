# Dokumentasi Deploy Picker dengan Docker Compose

## Overview

Layanan Picker adalah layanan yang digunakan untuk melakukan prediksi dengan melakukan integrasi dengan layanan ML melalui REST API.

## Requirements

- Docker dan Docker Compose terinstal pada sistem.
- Layanan Kafka sudah terdeploy.
- Pastikan environment variables sudah sesuai.

## Deployment Steps

### 1. Menjalankan Docker Compose

Setelah konfigurasi selesai, jalankan Docker Compose untuk memulai proses pembuatan layanan:

```sh
docker-compose up -d
```

## Catatan

- Lihat `docker-compose.double.yaml` untuk melalukan deployment lebih dari 1 layanan dalam 1 vm.
