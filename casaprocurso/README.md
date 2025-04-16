# CasaProCurso – Plataforma de Cursos Online com Laravel + Sail (Docker)

Este projeto é uma plataforma SaaS para venda de cursos online práticos como instalação elétrica, ar-condicionado, conserto de geladeira, chuveiro, fogão e muito mais.

---

## ✅ Requisitos

- Windows com WSL 2 instalado
- Docker Desktop rodando
- Terminal WSL com Ubuntu (20.04 ou superior)
- Acesso à internet para baixar imagens do Docker

---

## 🚀 Passo a passo para iniciar o projeto

Abra o terminal WSL (Ubuntu) e execute:

```bash
curl -s https://laravel.build/casaprocurso | bash
cd casaprocurso
./vendor/bin/sail up -d
