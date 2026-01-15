### Historias de Usuario para el MVP

#### **Historia de Usuario 1**
**Como** Lector casual,
**Quiero** combinar hasta 3 hashtags para encontrar historias que me interesen.

**Criterios de Aceptación:**
- La búsqueda devuelve solo ítems que contienen todos los tags.
- La paginación o el resultado muestra los 20 mejores resultados.

#### **Historia de Usuario 2**
**Como** Lector avanzado,
**Quiero** ver "más como esto" para descubrir obras similares.

**Criterios de Aceptación:**
- Se muestran 3 recomendaciones basadas en tags compartidos.

#### **Historia de Usuario 3**
**Como** Creador,
**Quiero** registrar mi obra con título, portada, descripción y tags para que me encuentren.

**Criterios de Aceptación:**
- El formulario valida los tags y crea un registro público.

#### **Historia de Usuario 4**
**Como** Usuario,
**Quiero** marcar favoritos para guardarlos.

**Criterios de Aceptación:**
- El favorito se asocia al `user_id`.
- El usuario ve su lista de favoritos.

#### **Historia de Usuario 5**
**Como** Admin,
**Quiero** recibir reportes y eliminar contenido inapropiado.

**Criterios de Aceptación:**
- Existe una cola con estados (nuevo, en revisión, resuelto).

#### **Historia de Usuario 6**
**Como** Visitante,
**Quiero** suscribirme en la *landing page* a la beta.

**Criterios de Aceptación:**
- La suscripción guarda el correo electrónico y el origen (cómo se enteró de la app).