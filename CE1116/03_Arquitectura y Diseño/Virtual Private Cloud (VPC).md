---
Fecha de creación: 2025-08-14 18:23
Fecha de Modificación: 2025-08-14 18:23
tags:
  - networking
  - deployment_model
Tema:
---


## 📚 Idea/Concepto 

Una Vpc  es una red virtual privada y lógicamente aislada dentro de un proveedor de nube pública, donde vos definís el rango de IP (CIDR), las subredes, las tablas de ruteo y las reglas de seguridad.
Dentro de esa VPC desplegás recursos (VMs, contenedores, bases gestionadas, etc.) que solo se pueden comunicar según las reglas de red que configures (security groups, NACLs, rutas).  
El aislamiento es por defecto frente a otras cuentas y VPC, cualquier conexión hacia internet, otras VPC o tu datacenter on-prem se habilita explícitamente vía Internet Gateway, NAT Gateway, VPN o enlaces dedicados.  
Es como un data center en la nube, mismo control de segmentación y zonas de fallo (AZs), pero gestionado vía UI, CLI o API en lugar de hardware físico.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Cloud Hibrido]] [[Public IP en el cloud]] [[Iaas vs Paas vs SaaS]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 