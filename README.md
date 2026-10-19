# MatFin Lab — Matemática Financiera en juego

**Curso:** 2BA Soporte, PET Colonia — 2026  
**Asignatura:** Matemática  
**Docente:** Domingo Pérez  
**Formato:** aplicación autónoma de **un solo archivo HTML**, sin dependencias ni servidor propio.

## Descripción breve para GitHub

Juego interactivo de Matemática Financiera con rutas de aprendizaje, ejercicios, pistas, calculadora, fórmulas y seguimiento individual del progreso. Desarrollado para Matemática de 2BA Soporte PET Colonia, 2026. Docente: Domingo Pérez.

## Contenidos

| Ruta | Planificación | Temas principales | Ejercicios |
|---|---|---|---:|
| 1. Reparto proporcional | 19 al 25/10 | Razones, reparto directo e inverso | 10 |
| 2. Porcentajes | 26/10 al 01/11 | Porcentaje, parte, total, equivalencias | 10 |
| 3. Aumentos y descuentos | 02 al 08/11 | Precios finales, descuentos y aumentos sucesivos | 10 |
| 4. Interés simple | 09 al 15/11 | Capital, tasa, tiempo, interés y monto | 10 |
| 5. Interés compuesto | 16 al 22/11 | Capitalización y comparación con interés simple | 10 |
| 6. Problemas reales | 23 al 29/11 | Compras de tecnología, cuotas, créditos y decisiones financieras | 10 |

**Total: 60 ejercicios**, con respuestas numéricas ingresadas por el estudiante y preguntas de opción múltiple.

## Cómo utilizarlo

1. Descargá `MatFin_Lab_2BA_PET_2026.html` y abrilo con un navegador moderno (Chrome, Edge o Firefox).
2. Introducí **nombre y apellido**. Si ya existe ese estudiante en el navegador, se reanuda su perfil. Si no existe, se crea otro.
3. Seleccioná una de las seis rutas y resolvé los ejercicios. Podés solicitar hasta tres pistas y utilizar herramientas sin penalización.
4. Completá respuestas numéricas y comprobá los resultados para sumar puntos de experiencia (XP). Las pistas reducen parte de los puntos posibles y los reintentos pueden afectar la recompensa.
5. Consultá la **calculadora**, las **fórmulas generales y sustituidas** o el **borrador** del ejercicio.
6. Usá el **Laboratorio** para comparar interés simple/compuesto, descuentos sucesivos y repartos, o participá del reto relámpago de ocho preguntas.

### Calculadora

- Operaciones: `+`, `-`, `*`, `/` y paréntesis.
- Potencias: `^` (ejemplo: `10000*(1+10/100)^2`).
- Porcentaje: `%` equivale a dividir entre 100.
- Factorial: `!` (ejemplo: `5!`).
- Combinatorias: `C(n;k)` (ejemplo: `C(5;2)`).
- Variaciones sin repetición: `P(n;k)` (ejemplo: `P(5;2)`).
- Raíz cuadrada: `sqrt(x)`.
- Se aceptan **coma decimal** y **punto decimal**; se admiten valores con agrupación de miles en notación española.

Las combinatorias están disponibles como parte de la calculadora matemática, aunque no constituyen un tema central de esta planificación de Matemática Financiera.

## Guardado individual del avance

El perfil se identifica por **nombre y apellido normalizados**. Se convierten las letras a MAYÚSCULAS, se eliminan tildes y se normalizan los espacios. Por ejemplo, `María Sánchez`, `MARIA SANCHEZ` y `maría   SANchez` identifican al **mismo estudiante**.

La aplicación guarda automáticamente en el **almacenamiento local del navegador** los ejercicios superados, XP, rachas, pistas usadas, borradores y resultados de retos. Las diferentes personas que usen el mismo navegador tienen perfiles separados por su nombre normalizado.

### Exportación e importación JSON

1. Entrá en **Mi progreso**.
2. Elegí **Exportar mi JSON** para generar un respaldo de un estudiante, o **Respaldo de todos los perfiles** para exportar las personas guardadas en ese navegador.
3. Para recuperar el avance, entrá en **Mi progreso > Importar JSON** y elegí el archivo correspondiente.
4. Si ya existe un perfil con el mismo nombre normalizado, se solicita confirmación antes de reemplazarlo.

El formato JSON registra el identificador de la aplicación, su versión, el estudiante normalizado, la fecha de exportación y los datos de su avance.

**Importante:** un sitio publicado en GitHub Pages es estático. No puede escribir automáticamente un archivo JSON en el repositorio ni compartir el avance entre distintos celulares/computadoras. El guardado local funciona en **ese navegador y dispositivo**, siempre que los datos del sitio no se borren y se permita almacenamiento local. Para trasladar información entre dispositivos es necesario **exportar e importar el JSON**. Para seguimiento centralizado y automático de un grupo se necesitaría incorporar un servicio externo de almacenamiento y autenticación, lo que no está incluido en esta versión autónoma.

El acceso por nombre **no es autenticación con contraseña**; cualquier persona que utilice el mismo navegador puede abrir un perfil si conoce el nombre. Evitá guardar información sensible en los borradores.

## Publicación en GitHub Pages

1. Creá un repositorio nuevo en GitHub.
2. Descargá **`index.html`** (o renombrá `MatFin_Lab_2BA_PET_2026.html` a `index.html`).
3. Subí ese **único archivo** a la raíz del repositorio (el README es opcional).
4. En **Settings > Pages**, seleccioná **Deploy from a branch** y la rama `main`, carpeta `/ (root)`.
5. Guardá los cambios y abrí la URL que GitHub Pages muestre tras completar la publicación.

El juego no requiere CDN, frameworks, imágenes remotas ni instalación de paquetes. Funciona sin conexión una vez descargado como archivo local. No incorpora servidores ni remite automáticamente datos de estudiantes a terceros.

---

Material didáctico elaborado para **Matemática — 2BA Soporte, PET Colonia (2026)**. **Docente: Domingo Pérez.**
