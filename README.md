# 🚀 CloudFormation: Infraestructura en Alta Disponibilidad con NGINX

Este repositorio contiene una plantilla en formato YAML para desplegar una infraestructura de **alta disponibilidad** en AWS utilizando **CloudFormation**. La plantilla crea automáticamente una arquitectura que incluye instancias EC2 con **NGINX**, un **Load Balancer**, y configuración para escalabilidad básica.

---

## 📦 Características del Stack

- ✅ 2 instancias EC2 en **zonas de disponibilidad distintas**
- ✅ Balanceo de carga mediante **Elastic Load Balancer (ALB)**
- ✅ Instalación automática de **NGINX**
- ✅ Escalado automático con un **Auto Scaling Group**
- ✅ Configuración de red con **VPC, subredes públicas, tabla de rutas e Internet Gateway**
- ✅ Grupo de seguridad que permite tráfico **HTTP (80)** y **SSH (22)**

---

## 📁 Estructura de Archivos

```plaintext
cloudformation_alta_disponibilidad.yaml
README.md
