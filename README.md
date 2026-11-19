# Supermass · Control de mercancía

Aplicación web instalable (PWA) para escanear facturas, recibir mercancía, verificar diferencias y controlar caducidades de productos perecederos.

**Más barato para tu hogar.**

## Funciones

- Captura de facturas con proveedor, número, fecha y llegada esperada.
- Escaneo de códigos de barras con la cámara o entrada manual.
- Recepción con conteo por línea, faltantes, sobrantes y notas.
- Caducidades por lote con estados: vencido, crítico, próximo y vigente.
- Corrección de cualquier dato capturado.
- Respaldo y restauración en JSON.
- Funciona sin conexión una vez cargada y se puede instalar en el dispositivo.

## Uso

Abre <https://morfeo388-web.github.io/> en Chrome, Edge o Safari y elige «Instalar aplicación» o «Agregar a inicio».

Los datos se guardan en el almacenamiento local del navegador. Descarga un respaldo desde **Ajustes** antes de borrar los datos del sitio o cambiar de dispositivo.

## Desarrollo local

Sirve la carpeta con cualquier servidor estático:

```sh
python -m http.server 8787
```

Abre <http://127.0.0.1:8787/>.

## Identidad

Rojo `#D31C1F`, amarillo `#FFE500` y tipografía Montserrat. Massito acompaña la experiencia. La tipografía se distribuye bajo SIL Open Font License.
