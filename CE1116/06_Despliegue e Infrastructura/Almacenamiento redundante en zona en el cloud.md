---
Fecha de creación: 2025-08-14 18:23
Fecha de Modificación: 2025-08-14 18:23
tags:
  - storage_redundancy
Tema:
---


## 📚 Idea/Concepto 
El almacenamiento redundante en zona replica los datos de forma síncrona entre múltiples zonas de disponibilidad dentro de la misma región del proveedor cloud.  
Cada zona se ubica en dominios de fallo distintos (diferentes data centers o edificios), lo que permite que la aplicación siga operando incluso si una zona completa deja de estar disponible.  
Este esquema mejora la disponibilidad y la durabilidad frente a fallos de infraestructura a nivel de zona, manteniendo latencias bajas al permanecer dentro de la misma región.  
Suele tener un costo mayor que el almacenamiento solo local a una zona, pero evita puntos únicos de fallo asociados a un único data center.
## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Almacenamiento redundante en zona en el cloud]][[Almacenamiento geo-redundante en el cloud]][[Escalamiento horizontal y vertical en cloud]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 