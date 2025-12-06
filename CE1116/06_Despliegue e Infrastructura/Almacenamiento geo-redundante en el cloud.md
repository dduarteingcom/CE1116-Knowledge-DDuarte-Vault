---
Fecha de creación: 2025-08-14 18:23
Fecha de Modificación: 2025-08-14 18:23
tags:
  - storage_redundancy
Tema:
---


## 📚 Idea/Concepto 

El almacenamiento geo-redundante replica los datos entre dos o más regiones físicamente separadas, de forma que una copia sobreviva incluso ante la caída total de una región por desastres o fallos de gran escala.  
Normalmente combina replicación síncrona dentro de una región (entre zonas de disponibilidad) con replicación asíncrona hacia la región emparejada, lo que reduce al mínimo la pérdida de datos.
Este modelo es la base de muchas estrategias de recuperación ante desastres, permitiendo restaurar datos y reiniciar servicios en otra región con tiempos de inactividad reducidos (mejor RTO) a costa de mayor complejidad, latencia entre regiones y costo.  
No garantiza por sí mismo que la aplicación “mágicamente” corra en otra región; garantiza que los datos estén disponibles para ser usados en un plan de failover bien diseñado.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
-[[Almacenamiento redundante en zona en el cloud]][[Almacenamiento redundante localmente en el cloud]][[Cloud Hibrido]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 