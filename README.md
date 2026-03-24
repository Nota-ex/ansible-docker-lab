<img width="2525" height="1302" alt="image" src="https://github.com/user-attachments/assets/39fd8faa-71c2-4cf3-a6c7-574d08b1437d" />

<img width="1913" height="1152" alt="image" src="https://github.com/user-attachments/assets/59543096-0c5f-4ecc-9588-aad31137573f" />




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
