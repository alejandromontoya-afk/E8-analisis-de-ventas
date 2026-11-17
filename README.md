analisis de ventas

Equipo E8 · Análisis de Datos Intermedio · Estud-IA (Capa 2)

## Brief v1

| Campo | Respuesta |
|---|---|
| Usuario y decisión | ¿Quién decide qué, y cada cuánto? | jefe comercial, decide que lotería tiene mejor desempeño en ventas en los últimos 5 años
| Pregunta | ¿Qué quieres responder? |cual lotería tuvo mayores ventas en los últimos 5 años
| Fuente con API | Enlace al endpoint (…/resource/xxxx-xxxx.json) |https://www.datos.gov.co/resource/2zg4-ahca.json?$q=Medell%C3%ADn&$limit=5
| Qué representa una fila |representa el valor mensual de cada lotería a nivel nacional |
| Campo que la identifica |año, mes, lotería, valor de ventas |
| Cada cuánto se actualiza |trimestral |
| Dato a confirmar |valor de ventas, llega como texto|
| Tres indicadores | 1.variacion del valor de ventas mensual · 2.vriacion de ventas anual · 3. variación según la loteria |
| Terminó bien si… | Una regla que se responde sí o no y que otra persona puede verificar / termino bien, si. la lotería de Medellín es la que más ventas tiene (pendiente)
| No vamos a construir | predicción de ventas|

## Contrato de datos

- Una fila es:
- La identifica:
- Si llega una fila repetida:
- Si falta un campo:

## Bitácora de decisiones

| Fecha | Decisión | Por qué |
|---|---|---|
| | | |

## Reglas del repositorio

- Es público: nada de datos personales, contraseñas, tokens ni llaves.
- Las credenciales van en un archivo `.env`, que Git ignora (ver `.gitignore`). `.env.example` muestra qué variables hacen falta, sin valores.
- Cada commit explica en su mensaje qué se decidió y por qué.
