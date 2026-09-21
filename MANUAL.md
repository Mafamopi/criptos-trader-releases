# Manual de uso

Criptos Trader sigue el precio de Solana, guarda tus compras y te dice si vas ganando o
perdiendo. Es la misma aplicación en Windows y en Android: las mismas pantallas, los mismos
cálculos y los mismos ajustes.

> ⚠️ **No es asesoría financiera.** La sugerencia que verás —*comprar*, *vender*,
> *mantener*— sale de una fórmula, no de alguien que sepa lo que va a pasar. Puede
> equivocarse y se equivocará. Las decisiones son tuyas y el dinero también.

---

## Índice

1. [Instalarla](#1-instalarla)
2. [La pantalla de inicio](#2-la-pantalla-de-inicio)
3. [Mi inversión](#3-mi-inversión)
4. [Plan de inversión](#4-plan-de-inversión)
5. [Alertas de precio](#5-alertas-de-precio)
6. [Estrategia](#6-estrategia)
7. [Ajustes](#7-ajustes)
8. [Dónde se guardan tus datos](#8-dónde-se-guardan-tus-datos)
9. [Si algo no funciona](#9-si-algo-no-funciona)

---

## 1. Instalarla

### Windows

Descarga **`CriptosTrader-win-Setup.exe`** de la
[última versión](https://github.com/Mafamopi/criptos-trader-releases/releases/latest) y
ejecútalo.

Windows dirá **«Windows protegió su PC»**. Es porque el instalador no está firmado, no
porque tenga nada malo: pulsa **Más información** → **Ejecutar de todas formas**.

No pide permisos de administrador ni pregunta dónde instalarse. Al terminar aparece una
ventanita pegada a la barra de tareas con el precio, y ahí se queda.

**Se actualiza sola.** Cuando haya una versión nueva la descarga y la aplica sin que tengas
que hacer nada.

> ¿Prefieres no instalar nada? En la misma página hay un
> **`CriptosTrader-win-Portable.zip`**: se descomprime y se ejecuta tal cual. A cambio, esa
> copia **no se actualiza sola**.

### Android

Descarga **`CriptosTrader-android.apk`** de la
[última versión](https://github.com/Mafamopi/criptos-trader-releases/releases/latest)
desde el propio teléfono y ábrelo.

La primera vez Android dirá que **no puede instalar apps de orígenes desconocidos**. Es lo
normal cuando una app no viene de Google Play:

1. Pulsa **Ajustes** en ese mismo aviso.
2. Activa **Permitir de esta fuente** para el navegador o el gestor de archivos que estés
   usando.
3. Vuelve atrás y pulsa **Instalar**.

Necesita **Android 6.0 o superior**.

**En Android no se actualiza sola.** Para pasar a una versión nueva, descarga el APK nuevo
y ábrelo: se instala encima y **conserva tus compras, alertas y ajustes**. No hace falta
desinstalar nada.

### iPhone

Todavía no. No es que falte el código —la app es la misma— sino que Apple no deja instalar
una aplicación descargada de una web: solo admite la App Store, TestFlight o que la firmes
tú mismo desde un Mac. Mientras eso no esté resuelto, publicar un archivo aquí sería
publicar algo que tu iPhone se negaría a abrir.

---

## 2. La pantalla de inicio

Es lo primero que ves y lo que más vas a mirar.

**El precio**, grande, y debajo la **variación de las últimas 24 horas** en verde si sube y
en rojo si baja.

**Tu resultado.** Cuánto ganas o pierdes ahora mismo con lo que hayas comprado, en dólares
y en porcentaje. Si todavía no has registrado ninguna compra, en su lugar hay un botón que
te lleva directo a donde se registran.

**Alertas que han saltado.** Aparece solo si ha saltado alguna. Guarda las últimas 20 de
esta sesión, la más reciente arriba.

**Sugerencia.** Una palabra —*comprar*, *vender* o *mantener*— con una línea explicando de
dónde sale. Se calcula con indicadores del mercado (medias móviles y RSI sobre velas de una
hora) y con tus propias compras. Si la apagas en [Estrategia](#6-estrategia), esta tarjeta
desaparece.

Debajo, los botones que llevan al resto: **Actualizar ahora**, **Mi inversión**, **Plan de
inversión**, **Alertas de precio**, **Estrategia**, **Ajustes** y **Manual de uso**.

> **Actualizar ahora** pide el precio sin esperar al siguiente ciclo. No hace falta usarlo:
> el precio se refresca solo.

---

## 3. Mi inversión

Aquí le dices a la app qué has comprado. Sin esto no puede calcular ni tu resultado ni el
plan.

### Techo total a invertir (USD)

Cuánto dinero estás dispuesto a poner en Solana **en total**, contando lo que ya compraste.

Es el error más fácil de cometer: si pones aquí solo lo que te queda por invertir, el plan
creerá que ya no hay margen y dejará de sugerir compras sin explicar por qué.

> Disponible = techo − lo que ya has comprado.

### Tus compras

Cada compra se registra con:

| Campo | Qué es |
|---|---|
| **Monto invertido (USD)** | Cuántos dólares pusiste en esa compra |
| **Precio de compra (USD/SOL)** | A qué precio estaba el SOL cuando compraste |
| **Fecha** | Opcional, en formato `2026-03-15` |

Pulsa **+ Agregar compra** para añadir una, o toca una de la lista para editarla o
borrarla.

Puedes registrar tantas como quieras. La app calcula tu precio medio y desde ahí tu
ganancia o pérdida.

> **Lo que registres vive solo en este dispositivo.** Las compras del teléfono y las del PC
> no se sincronizan: si usas los dos, tendrás que registrarlas en ambos.

---

## 4. Plan de inversión

Responde a una pregunta: *¿debería comprar ahora, y cuánto?*

Arriba, cuatro cifras: **techo total**, **ya invertido**, **disponible** y **precio del
SOL**.

Debajo, la **acción sugerida** con su explicación: cuánto invertiría, por qué, y qué escalón
de tu escalera se ha activado.

Y después, la parte más útil: **qué pasó las otras veces**. Para cada objetivo de precio te
dice cuántas veces el mercado estuvo así antes, cuánto tardó en llegar — y también las veces
que no llegó. Están puestas a propósito: un plan que solo enseña los casos buenos no es un
plan, es publicidad.

Necesita el histórico del mercado, así que la primera vez tarda unos segundos. Si no has
puesto el techo, te lo dirá con un botón para ir a arreglarlo.

---

## 5. Alertas de precio

Para no tener que estar mirando.

### Crear una

Pulsa **+ Agregar alerta**:

- **Cuándo avisar**: *Al caer a…* o *Al subir a…*
- **Precio (USD)**: el nivel que dispara el aviso.
- **Máx. avisos al día (opcional)**: vacío usa el límite general; `0` significa sin límite.
- **Activa**: si está apagada, se queda guardada pero no avisa.

Cada alerta de la lista tiene su propio interruptor al lado, para encenderla y apagarla sin
abrir el formulario.

### Que no te agote a avisos

Una alerta no se repite mientras el precio siga del mismo lado: avisa al cruzar, y se vuelve
a armar cuando el precio cruza de vuelta.

Encima de eso está el **máximo de avisos por alerta y día** (3 por defecto), que puedes
cambiar en general o alerta por alerta.

### Avisos

- **Avisarme cuando salte una alerta** — el interruptor principal. Apagado, no llega nada.
- **…aunque la app esté cerrada** *(solo Android)* — comprueba el precio de fondo cada
  **15, 30 o 60 minutos**. Menos de 15 no lo permite Android.
- **…y de los cambios de sugerencia** *(solo Android)* — avisa también cuando la sugerencia
  cambie.
- En Windows, además: avisos de **sugerencia de compra**, **de venta** y de
  **actualización disponible**.

**Comprobar ahora** hace una comprobación por el mismo camino que la automática. Si una
alerta está cruzada, el aviso llega en unos segundos: sirve para confirmar que todo está
bien configurado sin esperar.

> **Android pide permiso para notificar.** Si falta, la pantalla lo dice y te ofrece un
> botón para darlo. Sin ese permiso no llega ningún aviso, por muchos interruptores que
> enciendas.

---

## 6. Estrategia

Aquí decides **cómo de agresivo** quieres que sea el plan.

### Perfil de riesgo

Cuatro: **Conservador**, **Equilibrado**, **Agresivo** y **Personalizado**.

### Escalera de compra

La idea: cuanto más ha caído el precio desde su máximo de los últimos 30 días, más inviertes.

Los escalones son cuatro caídas —**5 %, 10 %, 15 % y 25 %**— y cada perfil dice qué
porcentaje invertir en cada uno:

| Caída | Conservador | Equilibrado | Agresivo |
|---|---|---|---|
| −5 % | 5 % | 10 % | 20 % |
| −10 % | 10 % | 20 % | 40 % |
| −15 % | 15 % | 30 % | 60 % |
| −25 % | 25 % | 40 % | 80 % |
| **Tope en señal extrema** | 50 % | 70 % | 100 % |

**Ese porcentaje es del capital que te queda disponible, no del total.** Es lo que hace que
la escalera se modere sola: si inviertes el 20 %, te queda el 80 %, y el escalón siguiente
se calcula sobre ese 80 %. Así no te quedas sin dinero justo cuando el precio está en su
mejor momento, que es lo que arruina una compra escalonada cuando la caída se alarga.

Los números solo se pueden editar en **Personalizado**. En los otros tres se ven, pero no se
tocan: son el perfil.

> El **tope en señal extrema** es el máximo que se compromete de una sola vez cuando todos
> los indicadores apuntan a lo mismo. El Agresivo llega al 100 % a propósito —es el
> «invierte todo»— y por eso no es el valor por defecto.

### Sugerir cuándo y cuánto invertir o vender

El interruptor de arriba. Apagado, la app se limita a enseñarte el precio y tu resultado, y
no sugiere nada en ninguna pantalla.

---

## 7. Ajustes

### Cada cuánto se consulta el precio

En el **teléfono**: 30 s, 1 min, 2 min, 5 min o 10 min. El mínimo es 30 segundos, y no es
un capricho: cada consulta enciende la radio del teléfono y eso lo paga la batería.

En **Windows**: desde 5 segundos, porque un PC enchufado no tiene ese problema.

También puedes escribir un número propio en **Otro (segundos)**.

### Ticker de la barra de tareas *(solo Windows)*

Cómo se ve la ventanita: **iniciar con Windows**, **tamaño de la letra**, **opacidad del
fondo**, y qué mostrar —**variación 24 h**, **tu resultado**, **la sugerencia**—.

En el teléfono esta sección no aparece: describe algo que allí no existe.

### Tema

El aspecto de la aplicación.

### Gráfico

La dirección que abre **Abrir gráfico**. Viene puesta y puedes cambiarla por la del sitio
que prefieras.

### Log detallado

Apagado por defecto. Enciéndelo solo si algo va mal y quieres ver qué está pasando por
dentro; deja el registro mucho más largo.

---

## 8. Dónde se guardan tus datos

**En tu dispositivo, y en ningún otro sitio.**

La app no tiene cuentas, no pide registro, no envía tus compras ni tus alertas a ninguna
parte. Lo único que sale a internet es la consulta del precio y del histórico del mercado.

Eso tiene una consecuencia que conviene saber: **si desinstalas, se borra todo**, y el PC y
el teléfono no comparten nada.

---

## 9. Si algo no funciona

**No aparece el precio, o dice que no pudo consultarlo.**
La app te lo dirá con todas las letras en vez de enseñarte un precio viejo como si fuera de
ahora. Suele ser la red: algunas redes de oficina y algunos países bloquean las fuentes de
precio. Comprueba tu conexión y espera al siguiente ciclo.

**No llega ninguna alerta en Android.**
Por orden: que el interruptor **Avisarme cuando salte una alerta** esté encendido; que el
**permiso de notificaciones** esté dado —la pantalla de alertas lo avisa si falta—; que la
alerta concreta esté **activa**; y que no hayas gastado ya su máximo de avisos del día.
Después usa **Comprobar ahora** para confirmarlo sin esperar.

**Las alertas llegan tarde con la app cerrada.**
Es Android decidiendo cuándo. La comprobación de fondo pide un hueco cada 15, 30 o 60
minutos, pero el sistema lo concede cuando le conviene para no gastar batería. Si el
teléfono tiene un ahorro de energía agresivo, conviene excluir la app de esa optimización.

**El plan dice que no hay capital disponible.**
Casi siempre es el **techo total**: tiene que incluir lo que ya compraste. Revísalo en
[Mi inversión](#3-mi-inversión).

**Windows dice que protegió mi PC.**
El instalador no está firmado. **Más información** → **Ejecutar de todas formas**.

**Quiero quitarla.**
En Windows, desde *Configuración → Aplicaciones → Criptos Trader → Desinstalar*. En Android,
como cualquier otra app: mantener pulsado el icono → *Desinstalar*.

---

Desarrollado por [Marlon Morales](https://www.linkedin.com/in/marlon-morales-8b5372136).
