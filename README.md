# Ansible + Docker Lab

Proyecto de automatización usando Ansible y Docker para gestionar múltiples servidores Ubuntu.

---

## Descripción

Este proyecto crea 5 servidores Ubuntu usando Docker y automatiza su configuración con Ansible.

---

## Tecnologías

- Docker
- Docker Compose
- Ansible
- Ubuntu

---

## Arquitectura

- 5 contenedores Ubuntu
- Acceso por SSH
- Automatización con Ansible

---

## Pasos para ejecutar

### 1. Levantar servidores

```bash
cd docker
docker compose up -d --build