# Formularios de debida diligencia – NETBROKER S.A. (Trivo)

Formularios web para el programa de prevención de lavado de activos, financiación del terrorismo y financiación de la proliferación (LA/FT/FP) de **NETBROKER S.A.**, actualizados conforme a la **Resolución Nro. UAFE-DG-2026-0017** de la Unidad de Análisis Financiero y Económico (UAFE).

Cada formulario se llena en línea, genera un PDF con los datos ingresados y se imprime para firmarlo a mano o con firma electrónica (FirmaEC).

## Formularios

| Archivo | Código | Formulario | Quién lo llena |
|---|---|---|---|
| `index.html` | — | Página de inicio con enlaces a todos los formularios | — |
| `formulario-cliente.html` | F-01 / F-02 | Conozca a su Cliente (persona natural / persona jurídica o fideicomiso) | Compradores, vendedores, arrendatarios, arrendadores, terceros pagadores, promotores y constructores |
| `formulario-licitud-fondos.html` | F-03 | Declaración de Licitud de Fondos y Registro de Pagos | El cliente, junto con el F-01 o F-02 |
| `formulario-proveedor.html` | F-04 / F-05 | Conozca a su Proveedor (persona natural / persona jurídica) | Proveedores de bienes y servicios |
| `formulario-comisionista.html` | F-04C | Conozca a su Proveedor – Comisionista Mercantil | Comisionistas mercantiles y referidores |
| `formulario-empleado.html` | F-06 | Conozca a su Empleado, Socio y Representante Legal | Empleados, socios o accionistas, representante legal y apoderados |

## Cómo se usa

1. Abrir el formulario que corresponda desde la página de inicio.
2. Llenar los campos obligatorios (marcados con `*`). Si un dato no aplica, escribir N/A.
3. Aceptar las declaraciones y pulsar **Descargar PDF para firmar**.
4. Imprimir el PDF, firmarlo y entregarlo a NETBROKER S.A. con los documentos de soporte que se listan al final del formulario.

## Privacidad

- Los datos **no se envían ni se guardan en ningún servidor**: el PDF se genera en el dispositivo de quien llena el formulario.
- El navegador puede guardar un borrador local para no perder lo escrito; el botón **Borrar todo** lo elimina.
- Este repositorio contiene solo los formularios en blanco. No subir aquí formularios llenos, expedientes, la matriz de riesgos ni el Manual de Prevención, que son documentos reservados (Res. UAFE-DG-2026-0017, Art. 13.2).

## Aspectos técnicos

- Páginas HTML estáticas, sin base de datos ni código de servidor. Funcionan en GitHub Pages o en cualquier hosting web.
- Requieren conexión a internet para cargar el generador de PDF ([jsPDF](https://github.com/parallax/jsPDF) 2.5.1 y jsPDF-AutoTable 3.8.2 desde cdnjs.cloudflare.com) y la tipografía Nunito Sans desde Google Fonts.
- Los archivos deben estar en la misma carpeta y conservar su nombre, porque `index.html` los enlaza por nombre.

## Actualizaciones

Para actualizar un formulario, reemplazar el archivo con la nueva versión manteniendo el mismo nombre. GitHub Pages publica el cambio en uno o dos minutos.

| Versión | Fecha | Cambio |
|---|---|---|
| 2 | Noviembre 2026 | Formularios actualizados según la Res. UAFE-DG-2026-0017; versión web con generación de PDF para firmar. |

---

Responsable: Oficial de Cumplimiento de NETBROKER S.A.
