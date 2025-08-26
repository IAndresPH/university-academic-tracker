# university-academic-tracker – Historias de Usuario

Este apartado forma parte de la documentación del proyecto **University Academic Tracker**.  
Su propósito es centralizar las **historias de usuario (HU)** que detallan las funcionalidades del sistema, asociadas a las épicas definidas en cada corte.

---

## ¿Qué es una historia de usuario?
Una historia de usuario es una descripción breve y simple de una funcionalidad del sistema, escrita desde la perspectiva del usuario final.  
Ejemplo de formato:  
> Como **[rol]**, quiero **[acción]** para **[beneficio esperado]**.

---

## Nomenclatura de Historias de Usuario
La numeración de las HU está diseñada para reflejar el **corte académico** al que pertenecen y la **épica asociada**:

- **Corte 1 – EP-1 (Configuración y gestión de notas)**  
  - HU-001 a HU-010  

- **Corte 2 – EP-2 (Seguimiento y organización académica)**  
  - HU-101 a HU-110  

- **Corte 3 – EP-3 (Reportes y alertas proactivas)**  
  - HU-201 a HU-210  

De esta forma, el identificador HU permite identificar de inmediato a qué épica y corte pertenece.  

---

## Organización
Cada historia de usuario será documentada en un archivo independiente dentro de la carpeta correspondiente a su corte:  

```plaintext
user-stories/
├─ EP-1/
│  ├─ HU-001.md
│  ├─ HU-002.md
│  └─ ...
├─ EP-2/
│  ├─ HU-101.md
│  ├─ HU-102.md
│  └─ ...
└─ EP-3/
   ├─ HU-201.md
   ├─ HU-202.md
   └─ ...