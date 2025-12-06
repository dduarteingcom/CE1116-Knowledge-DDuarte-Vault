---
Fecha de creación: 2025-08-14 18:23
Fecha de Modificación: 2025-08-14 18:23
tags:
  - networking
Tema: Necesidad del usuario
---


## 📚 Idea/Concepto 
Una dirección IP pública en el cloud es un identificador global y enrutable en internet que el proveedor asigna a recursos expuestos hacia el exterior, como balanceadores de carga, gateways de aplicaciones, firewalls o, en casos puntuales, máquinas virtuales.
Estas IPs suelen ser globalmente únicas en el espacio público y pueden ser dinámicas (cambian) o reservadas/estáticas (se mantienen fijas para DNS, integraciones, clientes).  
Normalmente no se exponen directamente todos los recursos internos, sino que la IP pública se asocia a un punto de entrada controlado que luego enruta hacia redes privadas (VPC/subredes) mediante reglas de seguridad y balanceo.  
Las buenas prácticas incluyen restringir el acceso mediante firewalls, listas de control y grupos de seguridad a solo los puertos, protocolos y rangos de IP necesarios, evitando exponer directamente servicios sensibles como bases de datos o paneles de administración.
## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Virtual Private Cloud (VPC)]] [[Iaas vs Paas vs SaaS]][[Cloud Hibrido]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 