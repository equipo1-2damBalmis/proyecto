## Pantalla de Escritorio: Panel Principal de Administración (Vista Resumen)

**Rol de la pantalla:** Pantalla de inicio (Dashboard) posterior al inicio de sesión del administrador.
**Formato del contenedor raíz:** Ventana panorámica de escritorio (relación de aspecto 16:9). Distribución principal mediante Flexbox horizontal dividida en dos zonas fijas sin solapamientos: Barra Lateral Izquierda (20% del ancho) y Área Principal Derecha (80% del ancho).

---

### 1. Barra Lateral Izquierda (Menú Vertical de Acciones Rápidas)
Contenedor vertical fijo que ocupa el 20% del ancho total (aprox. 260 px) y el 100% de la altura de la ventana, aplicando el estilo corporativo principal del sistema:

* **Cabecera Superior:**
  * Icono lineal de edificio residencial situado a la izquierda del título de marca **"Comunify"**.
* **Bloque Central de Acciones (Disposición en columna vertical, alineados uno debajo del otro con separación uniforme):**
  * Subtítulo de sección: **"Acciones Rápidas"**.
  * **Botón de acción 1:** Icono izquierdo de documento/factura con símbolo más y texto **"+ Nueva Factura"**.
  * **Botón de acción 2:** Icono izquierdo de recibo con marca de verificación y texto **"✓ Validar Pagos"**.
  * **Botón de acción 3:** Icono izquierdo de megáfono y texto **"+ Publicar Aviso"**.
  * **Botón de acción 4:** Icono izquierdo de urna/formulario de encuesta y texto **"+ Nueva Votación"**.
  * **Botón de acción 5:** Icono izquierdo de silueta de usuario con símbolo más y texto **"+ Alta Propietario"**.
* **Pie de Barra Lateral (Anclado en el extremo inferior izquierdo):**
  * Botón de salida con icono izquierdo de puerta/flecha de cierre y texto **"Cerrar Sesión"**.

---

### 2. Área Principal Derecha: Nivel Superior (Barra de Navegación Horizontal)
Contenedor superior dispuesto en una sola fila horizontal (`justify-content: space-between`) que separa las pestañas de navegación a la izquierda y el perfil de usuario a la derecha:

* **Grupo Izquierdo (Pestañas de Navegación Principal en línea horizontal):**
  1. Pestaña 1 (Estado Activo / Seleccionado): **"Resumen"** (aplicar estilo de botón/pestaña activa destacada).
  2. Pestaña 2 (Estado Inactivo): **"Cuentas y Gastos"**.
  3. Pestaña 3 (Estado Inactivo): **"Vecinos y Cuotas"**.
  4. Pestaña 4 (Estado Inactivo): **"Comunicaciones"**.
* **Grupo Derecho (Identificador de Usuario):**
  * Etiqueta de texto **"Admin: Presidente"** acompañada a su derecha de un icono circular de avatar de perfil.

---

### 3. Área Principal Derecha: Nivel Intermedio (Fila de 3 Tarjetas de Resumen / KPIs)
Tres tarjetas contenedoras de idéntico ancho y alto, alineadas estrictamente en una única fila horizontal (`display: flex; flex-direction: row; gap: 20px`):

1. **Tarjeta 1 (Izquierda - Saldo Global):**
   * Estilo de tarjeta estándar del sistema.
   * Título superior centrado: **"Saldo Comunidad"**.
   * Importe principal centrado en tamaño grande y negrita: **"4.850,00 €"**.
   * Subtítulo inferior centrado (aplicar estilo semántico de variación positiva): **"+2% este mes"**.
2. **Tarjeta 2 (Centro - Gastos Mensuales):**
   * Estilo de tarjeta estándar del sistema.
   * Título superior centrado: **"Gastos del Mes"**.
   * Importe principal centrado en tamaño grande y negrita: **"1.255,00 €"**.
   * Subtítulo inferior centrado (estilo de texto secundario neutro): **"Facturas registradas"**.
3. **Tarjeta 3 (Derecha - Deuda Acumulada):**
   * Estilo de tarjeta con énfasis semántico de alerta/deuda pendiente.
   * Título superior centrado: **"Cuotas Pendientes"**.
   * Importe principal centrado en tamaño grande, negrita y estilo de alerta: **"376,50 €"**.
   * Subtítulo inferior centrado: **"3 vecinos con deudas"**.

---

### 4. Área Principal Derecha: Nivel Inferior (Rejilla Asimétrica de 2 Columnas)
Contenedor inferior dividido horizontalmente en dos columnas: Columna Izquierda (65% del ancho) y Columna Derecha (35% del ancho).

#### 4.1. Columna Izquierda (65% del ancho): Tarjeta de "Distribución de Gastos"
Tarjeta contenedora de altura completa dividida internamente en cabecera, cuerpo central y pie:
* **Cabecera de la tarjeta (Fila horizontal con elementos en los extremos):**
  * Extremo izquierdo: Título de sección en negrita **"Distribución de Gastos (Octubre 2026)"**.
  * Extremo derecho: Control desplegable (selector dropdown) con el texto **"Octubre 2026 ▾"**.
* **Cuerpo central de la tarjeta (Dividido en 2 mitades horizontales):**
  * **Mitad Izquierda (Gráfico):** Gráfico circular de anillo (Donut Chart) dividido en 5 segmentos proporcionales diferenciados visualmente. En el centro hueco del anillo se muestra el texto en dos líneas centradas: **"Total:"** arriba y **"1.255,00 €"** en negrita abajo.
  * **Mitad Derecha (Leyenda de Categorías):** Lista vertical de 5 filas alineadas a la izquierda. Cada fila incluye un indicador circular a la izquierda (vinculado a su segmento del gráfico) seguido del concepto e importe exacto:
    * `●` **"Luz (500 €)"**
    * `●` **"Agua (300 €)"**
    * `●` **"Limpieza (200 €)"**
    * `●` **"Ascensor (155 €)"**
    * `●` **"Seguro (100 €)"**
* **Pie de la tarjeta (Alineado en la esquina inferior derecha):**
  * Botón de acción secundario con el texto **"+ Añadir Gasto / Derrama"**.

#### 4.2. Columna Derecha (35% del ancho): 2 Tarjetas Apiladas Verticalmente

* **Tarjeta Superior Derecha (Resumen de Impagos):**
  * Título superior en negrita alineado a la izquierda: **"Vecinos con Deudas"**.
  * Lista vertical de 3 elementos. Cada fila muestra un indicador circular de estado pendiente a la izquierda seguido del piso y la deuda entre paréntesis:
    * `●` **"2ºB (125,50 €)"**
    * `●` **"4ºA (125,50 €)"**
    * `●` **"1ºC (125,50 €)"**
  * Esquina inferior derecha: Botón de navegación secundario con el texto **"Gestionar"** (conecta con la pantalla detallada de gestión de propietarios).

* **Tarjeta Inferior Derecha (Resumen de Comunicados):**
  * Situada inmediatamente debajo de la tarjeta "Vecinos con Deudas".
  * Título superior en negrita alineado a la izquierda: **"Últimos Avisos"**.
  * Fila de contenido horizontal compuesta por: icono triangular de advertencia (`⚠`) a la izquierda, texto **"Corte de agua..."** en el centro y marca de hora **"12:00"** alineada a la derecha.
  * Esquina inferior derecha: Enlace de acción con flecha **"Ver historial →"**.

---

### 5. Restricciones Estrictas de Maquetación y Renderizado
* **Alineación:** Mantener las 3 tarjetas superiores de KPIs estrictamente en la misma línea horizontal y los 5 botones de "Acciones Rápidas" en una única columna vertical dentro de la barra lateral izquierda.
* **Espaciado interno:** Aplicar márgenes internos (`padding`) amplios en todas las tarjetas para evitar que los textos, el gráfico de anillo o los botones toquen los bordes de sus contenedores o se superpongan entre sí.
* **Fidelidad de textos:** Renderizar única y exclusivamente las etiquetas, cifras y textos en español especificados entre comillas en este documento, sin añadir botones genéricos ni textos de prueba adicionales.