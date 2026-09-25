# Manual de uso

Cómo se usa Criptos Trader, pantalla por pantalla. Es la misma aplicación en Windows y en
Android: las mismas pantallas y los mismos cálculos. Lo que solo existe en Windows va
marcado.

> ⚠️ **No es asesoría financiera.** La sugerencia que verás —*comprar*, *vender*,
> *mantener*— sale de una fórmula, no de alguien que sepa lo que va a pasar. Puede
> equivocarse. Las decisiones son tuyas y el dinero también.

---

## Índice

1. [La pantalla de inicio](#1-la-pantalla-de-inicio)
2. [Mi inversión](#2-mi-inversión)
3. [Plan de inversión](#3-plan-de-inversión)
4. [Alertas de precio](#4-alertas-de-precio)
5. [Noticias](#5-noticias)
6. [Estrategia](#6-estrategia)
7. [Ajustes](#7-ajustes)
8. [La ventanita de la barra de tareas](#8-la-ventanita-de-la-barra-de-tareas)
9. [El icono junto al reloj](#9-el-icono-junto-al-reloj)

---

## 1. La pantalla de inicio

Es lo primero que ves y lo que más vas a mirar.

**El precio**, grande, y debajo la **variación de las últimas 24 horas** en verde si sube y
en rojo si baja.

A la derecha del precio está el icono de **actualizar** (**↻**): pide el precio en ese momento,
sin esperar al siguiente ciclo. Mientras llega, la flecha gira y el icono no se puede volver a
pulsar; en cuanto contesta —o falla— vuelve a su sitio. No hace falta usarlo: el precio se
refresca solo.

Debajo, en pequeño, **el precio en tu moneda y cuánto vale un dólar** (por ejemplo
*≈ $471.042 COP* y *1 USD = $3.912,30 COP · hoy*). La moneda sale de la región de tu
dispositivo (en el navegador, de tu zona horaria, y si no la hay, del idioma del navegador); si
es EE. UU., no aparece. Tocando la línea del dólar se lee de dónde sale la tasa y
de qué día es: es una referencia, tu banco aplica la suya.

El precio sale del servidor de Criptos Trader, que lo consulta para todos a la vez: el PC, el
teléfono y el navegador ven **el mismo número, de la misma fuente y con la misma hora**. Al pie
de la pantalla se lee de dónde viene y de qué hora es (por ejemplo, *Binance.US · 10:45:37*).
Si tiene más de 30 segundos, lo dice (*hace 45 s*). Si el servidor no responde, la app lo pide
directo a CoinGecko o Binance para no dejarte sin precio, y avisa de que **puede diferir de tus
otros dispositivos**.

**Tu resultado.** Cuánto ganas o pierdes ahora mismo con lo que hayas comprado, en dólares y
en porcentaje. Si aún no has registrado ninguna compra, en su lugar hay un botón que te
lleva directo a donde se registran.

**Los iconos de arriba.** A la derecha de *SOLANA* hay tres, en este orden: el
**periódico** abre las [Noticias](#5-noticias), la **campana** abre los avisos y el
**engranaje** abre los [Ajustes](#7-ajustes).

En el PC y en el navegador, **al pasar el ratón por encima de cualquier icono** sale lo que
hace: *Noticias*, *Avisos*, *Ajustes*, *Actualizar precio*, *Borrar este aviso* en la ✕ de
cada aviso y *Volver* en la **‹** de arriba a la izquierda de cada pantalla.

**El periódico.** Lleva un número rojo cuando hay titulares que todavía no has abierto
(*9+* si son más de nueve). Cuenta también los que llegaron con la app cerrada. Cómo dejan de
contar lo explica la sección de [Noticias](#5-noticias).

**La campana.** Recoge los avisos que te da la app:
alertas de precio, cambios de sugerencia, datos de la FED y del desempleo y versiones nuevas.
En el teléfono también los que llegan con la app cerrada, por push o por la comprobación de
fondo. Las noticias no van aquí. Cuando hay avisos que aún no has visto, la campana lleva un
número rojo (*9+* si son más de nueve).

Tócala para ver la lista, el más reciente arriba: cada aviso con su título, el mensaje y
cuándo llegó (*hoy 14:05*, *ayer 09:30* o la fecha). Los que no habías visto llevan un punto
azul al lado. Abrir la lista los da por vistos y el número desaparece. La **✕** de cada aviso
lo borra, y **Limpiar todo** los borra todos después de pedirte confirmación. Se guardan
aunque cierres la app: como mucho los últimos 100, y los de más de 30 días se borran solos.

**Tasa de la FED.** El rango de tipos de interés que fija la Reserva Federal de Estados
Unidos, con el tipo efectivo del último día hábil y la fecha del dato. Es contexto, no
consejo: cuando la FED sube o baja el tipo, el mercado entero se mueve, y esta tarjeta te
dice en qué ambiente estás. Lo publica la propia Reserva Federal de Nueva York; aparece en
cuanto se ha podido leer una vez, y se queda ahí aunque luego te quedes sin conexión.

**Desempleo en EE. UU.** La tasa del último mes publicado, con el mes al que corresponde.
Junto al tipo de la FED son las dos cifras que mueven el mercado entero cuando salen. Lo
publica el *Bureau of Labor Statistics*, una vez al mes.

El dato se pide a dos sitios: primero al **BLS**, que es quien lo publica, y si no contesta
—su servicio gratuito atiende 25 consultas al día por conexión— a la **Reserva Federal de
San Luis**, que publica el mismo número. Que se caiga uno no te deja sin dato.

El último dato conocido **se queda en pantalla** aunque hoy no se haya podido comprobar si
hay uno más nuevo; cuando es el caso, lo dice debajo. Un dato mensual sigue siendo cierto
aunque hoy falle la conexión.

Solo si nunca se ha podido traer ninguno verás un **—**, y debajo el motivo. Se vuelve a
intentar solo; no hay nada que tocar.

**Sugerencia.** Dos, una por cada dinero, cada una con una línea explicando de dónde sale:

- **Con lo disponible** — *comprar* o *esperar*. Solo mira el mercado: indicadores (medias
  móviles y RSI sobre velas de una hora) y cuánto ha caído. Cuando toca esperar, dice cuánto
  tienes disponible y a qué precio empezaría tu escalera de compra.
- **Con lo comprado** — *cobrar* o *mantener*. Solo mira tu ganancia: sugiere cobrar una
  parte desde **+20 %**. Solo aparece si tienes compras registradas.

Van por separado a propósito: cobrar parte de lo que ya ganó y comprar más abajo con otro
dinero no es contradictorio. Si la apagas en [Estrategia](#6-estrategia), esta tarjeta
desaparece.

Debajo, los botones:

| Botón | Qué hace |
|---|---|
| **Mi inversión** | Solo aparece si ya registraste alguna compra |
| **Plan de inversión** | Cuánto invertir ahora, y qué pasó otras veces |
| **Alertas de precio** | Crear y administrar avisos |
| **Estrategia** | Perfil de riesgo y escalera de compra |
| **Manual de uso** | Esto que estás leyendo, dentro de la app |

Noticias y Ajustes no están en esta lista: se abren con sus iconos de arriba. Tampoco está
*Actualizar ahora*: ahora es el icono **↻** junto al precio.

---

## 2. Mi inversión

Aquí le dices a la app qué has comprado. Sin esto no puede calcular ni tu resultado ni el
plan.

### Techo total a invertir (USD)

Cuánto dinero estás dispuesto a poner en Solana **en total**, contando lo que ya compraste.

Es el error más fácil de cometer: si pones aquí solo lo que te queda por invertir, el plan
creerá que ya no hay margen y dejará de sugerir compras sin explicar por qué.

> Disponible = techo − lo que ya has comprado.

### Tus compras

Pulsa **+ Agregar compra**. Cada una lleva:

| Campo | Qué es |
|---|---|
| **Monto invertido (USD)** | Cuántos dólares pusiste en esa compra |
| **Precio de compra (USD/SOL)** | A qué precio estaba el SOL cuando compraste |
| **Fecha** | Opcional, en formato `2026-03-15` |

Toca una compra de la lista para **editarla** o **eliminarla**. Puedes registrar tantas como
quieras: la app calcula tu precio medio y desde ahí tu ganancia o pérdida, y debajo de la
lista resume el total invertido.

> Lo que registres vive solo en este dispositivo. Las compras del teléfono y las del PC no
> se sincronizan: si usas los dos, tendrás que registrarlas en ambos.

---

## 3. Plan de inversión

Responde a una pregunta: *¿debería comprar ahora, y cuánto?*

Arriba, cuatro cifras: **techo total**, **ya invertido**, **disponible** y **precio del
SOL**.

Debajo, dos **acciones sugeridas**, cada una con su explicación:

- **Con lo disponible**: cuánto invertiría, por qué y qué escalón de tu escalera se ha
  activado. Si toca esperar, dónde empieza la escalera.
- **Con lo comprado**: cuánto venderías de tu posición al llegar a tu objetivo de ganancia, o
  por qué mantener.

Y después, la parte más útil: **qué pasó las otras veces**. Para cada objetivo de precio te
dice cuántas veces el mercado estuvo así antes, cuánto tardó en llegar — y también las veces
que no llegó. Están puestas a propósito: un plan que solo enseña los casos buenos no es un
plan, es publicidad.

Necesita el histórico del mercado, así que la primera vez tarda unos segundos. Si no has
puesto el techo, te lo dirá con un botón para ir a arreglarlo.

---

## 4. Alertas de precio

Para no tener que estar mirando.

### Crear una

Pulsa **+ Agregar alerta**:

| Campo | Qué es |
|---|---|
| **Cuándo avisar** | *Al caer a…* o *Al subir a…* |
| **Precio (USD)** | El nivel que dispara el aviso |
| **Máx. avisos al día** | Opcional. Vacío usa el límite general; `0` es sin límite |
| **Activa** | Apagada se queda guardada, pero no avisa |

Se guarda con **Guardar**. Desde el mismo formulario puedes **Eliminar esta alerta** o
**Cancelar**.

Cada alerta de la lista tiene su propio interruptor al lado, para encenderla y apagarla sin
abrir el formulario.

### Que no te agote a avisos

Una alerta no se repite mientras el precio siga del mismo lado: avisa al cruzar, y se vuelve
a armar cuando el precio cruza de vuelta.

Encima de eso está el **máximo de avisos por alerta y día** (3 por defecto), que puedes
cambiar en general o alerta por alerta.

### Avisos

- **Avisarme cuando salte una alerta** — el interruptor principal. Apagado, no llega nada.
- **Avisarme de las sugerencias de compra** *(Windows)*
- **…y de las de venta** *(Windows)*
- **Avisarme cuando haya una actualización** — en Windows la versión ya está descargada y
  solo falta reiniciar; en Android el aviso lleva a la página de descargas, porque un APK no
  puede instalarse solo. En Android, con los avisos por push activos, llega **en cuanto se
  publica** (el servidor lo mira cada 15 minutos), aunque la app esté cerrada; sin push, la
  comprobación de fondo lo mira como mucho cada 6 horas. Se avisa una vez por versión
- **Avisarme cuando la FED cambie el tipo de interés** — cubre los dos datos de Estados
  Unidos: el tipo de la FED y el desempleo. El rango objetivo solo cambia en las ocho
  reuniones anuales de la FED, y el desempleo se publica una vez al mes, así que son unos
  veinte avisos al año en total. Que el tipo efectivo se mueva unas centésimas dentro del
  rango no avisa: eso pasa casi a diario y no es una decisión de nadie. Se mira **dos veces
  al día**, y el desempleo solo cuando puede haber uno nuevo; apagarlo también ahorra esas
  consultas cuando la app está cerrada.
- **Avisarme cuando haya noticias nuevas** — **un aviso por noticia**, con el titular, la
  entradilla y la hora a la que salió; al tocarlo se abre el artículo. La más nueva queda
  arriba. Tiene su propio **máximo de noticias avisadas al día** (3 por defecto, 0 = sin
  límite), justo debajo del interruptor: si llegan más, se avisa de las más nuevas y el
  resto se ve en la pantalla de noticias.
- **…aunque la app esté cerrada** *(Android)* — comprueba el precio de fondo cada **15, 30 o
  60 minutos**, que se elige en **Cada cuánto**. Menos de 15 no lo permite Android.
- **…y de los cambios de sugerencia** *(Android)* — avisa también cuando la sugerencia
  cambie. Lo disponible y lo comprado avisan cada uno por su lado.

Con la app cerrada, **los avisos de noticias bastan para que el teléfono compruebe**, aunque
no tengas ninguna alerta activa; si solo hacen falta las noticias, no se pide ni el precio.
Los datos de EE. UU. viajan en esa misma comprobación y no piden una propia. Con alertas y
noticias apagadas, con la app cerrada no llegan; la pantalla de alertas te lo dice cuando
es el caso.

**Comprobar ahora** *(Android)* hace una comprobación por el mismo camino que la automática.
Si una alerta está cruzada, el aviso llega en unos segundos: sirve para confirmar que todo
está bien configurado sin esperar.

Los avisos **quedan en el panel de notificaciones** después de desvanecerse, así que una
alerta que salta mientras no miras la pantalla no se pierde.

En Android salen en **dos grupos** del sistema: *Alertas de precio* y *Noticias y datos*.
Las noticias, además, se apilan juntas bajo *Noticias de Solana*.
Puedes silenciar uno sin tocar el otro desde los ajustes de notificaciones de Android, que
es donde mucha gente los apaga.

> **Android pide permiso para notificar.** Si falta, la pantalla lo dice y te ofrece un botón
> para darlo. Sin ese permiso no llega ningún aviso, por muchos interruptores que enciendas.

---

## 5. Noticias

Los últimos titulares sobre Solana, del más nuevo al más viejo. Salen de
**Cointelegraph**, de su canal dedicado a Solana: no es un río de noticias generales
filtrado a ojo, es el canal de la moneda.

Se llega con el **periódico** de arriba en la pantalla de inicio.

Cada titular **es el enlace**: al tocarlo se abre la noticia completa en el navegador.
Debajo va la entradilla y la hora a la que se publicó, en tu hora.

**Los que no has leído llevan un punto azul** al lado, y son los que cuenta el número del
periódico. Un titular deja de contar cuando **lo abres** para leerlo; entrar en la pantalla
no basta. **Marcar todas como leídas**, arriba, los da todos por leídos de una vez (no se
borra nada; solo aparece si queda alguno sin leer). Lo leído se guarda aunque cierres la app,
y es de cada dispositivo: lo que leas en el teléfono sigue sin leer en el PC.

La primera vez que abres esta versión, los titulares que ya estaban cuentan como leídos: el
número empieza a contar con los que lleguen después.

> Si abres una noticia desde el **aviso del teléfono**, también cuenta como leída: el número
> baja aunque no hayas entrado en la app.

**Los titulares llegan en inglés y la app los traduce.** Debajo de cada uno, en letra
pequeña, queda el titular original: la traducción es automática y puede torcer un nombre o
una cifra, y el artículo que abre el enlace está en inglés. Si alguna entradilla no se pudo
traducir, no se muestra —un titular en español con dos líneas en inglés debajo se lee peor
que un titular solo— y suele aparecer en la siguiente actualización.

Si en algún momento no se puede traducir, el titular sale **en su idioma** y ya está: la app
no te dirá nada al respecto, porque no hay nada que puedas hacer y se arregla solo.

Los avisos de noticias también llegan traducidos.

**Actualizar** pide el canal al momento. No hace falta usarlo: la app lo mira sola cada
cuarto de hora mientras está abierta, y también con la app cerrada si tienes encendido el
aviso de noticias.

Si el canal no contesta, la pantalla lo dice. Lo que ya se había traído sigue ahí.

> ⚠️ Los titulares son información, no una recomendación. Que una noticia sea buena no
> significa que el precio vaya a subir, ni al revés.

---

## 6. Estrategia

Aquí decides **cómo de agresivo** quieres que sea el plan.

**Sugerir cuándo y cuánto invertir o vender** es el interruptor de arriba. Apagado, la app se
limita a enseñarte el precio y tu resultado, y no sugiere nada en ninguna pantalla.

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
la escalera se modere sola: si inviertes el 20 %, te queda el 80 %, y el escalón siguiente se
calcula sobre ese 80 %. Así no te quedas sin dinero justo cuando el precio está en su mejor
momento, que es lo que arruina una compra escalonada cuando la caída se alarga.

Los números solo se pueden editar en **Personalizado**. En los otros tres se ven, pero no se
tocan: son el perfil.

> El **tope en señal extrema** es el máximo que se compromete de una sola vez cuando todos
> los indicadores apuntan a lo mismo. El Agresivo llega al 100 % a propósito —es el «invierte
> todo»— y por eso no es el valor por defecto.

---

## 7. Ajustes

### Cada cuánto se consulta el precio

En el **teléfono**: 30 s, 1 min, 2 min, 5 min o 10 min. El mínimo es 30 segundos, y no es un
capricho: cada consulta enciende la radio del teléfono y eso lo paga la batería.

En **Windows**: 5 s, 10 s, 15 s, 30 s, 1 min, 2 min o 5 min.

En **Otro (segundos)** puedes escribir un número propio; debajo se lee el rango admitido y el
intervalo que está funcionando ahora mismo.

### Moneda local

En qué moneda se enseñan el precio convertido y el dólar de la pantalla de inicio:
**Automática** (la de la región del dispositivo, que se ve entre paréntesis), una moneda elegida
de la lista, o **No mostrar**. Mientras no han llegado las tasas, la lista solo ofrece
**Automática** y **No mostrar**; si las que llegan no traen la moneda elegida, una nota lo dice
debajo.

### Ticker de la barra de tareas *(solo Windows)*

Toda esta sección describe la ventanita, así que en el teléfono no aparece.

| Ajuste | Qué hace |
|---|---|
| **Iniciar con Windows** | La app se abre sola al encender el PC |
| **Tamaño de la letra** | Lo grande que se ve el texto del ticker |
| **Opacidad del fondo** | De transparente a sólido |
| **Mostrar variación 24 h** | Enseña o esconde el porcentaje del día |
| **Mostrar mi resultado** | Enseña o esconde tu ganancia o pérdida |
| **Mostrar la sugerencia** | Enseña o esconde la sugerencia del final: *comprar* y/o *vender*, o *mantener* si no hay nada que hacer |

**Tema**: **Oscuro**, **Claro**, **Solana** o **Personalizado**.

Con **Personalizado** aparecen ocho colores para tocar uno a uno: **Fondo**, **Símbolo**,
**Precio**, **Subida**, **Bajada**, **Sugerir comprar**, **Sugerir vender** y **Sugerir
mantener**. Con un tema predefinido no se muestran, porque el tema los decide.

### Gráfico

La dirección que abre **Abrir gráfico**. Viene puesta y puedes cambiarla por la del sitio que
prefieras.

### Mi cuenta

Con una cuenta, tus **compras, techo, alertas, estrategia y qué avisos quieres** están iguales
en el PC y en el teléfono, sin pasar archivos. Lo de la pantalla —tema, colores, el ticker,
iniciar con Windows— no viaja: cada dispositivo tiene el suyo.

La primera vez que abres la app te lo ofrece: **Crear cuenta**, **Ya tengo cuenta** o **Ahora
no**. Después está siempre en *Ajustes → Mi cuenta*.

- **Crear cuenta** — nombre de usuario, correo y contraseña (mínimo 8 caracteres). El usuario y
  el correo no pueden estar repetidos. Lo que tienes en ese dispositivo pasa a la cuenta.
- **Iniciar sesión** en otro dispositivo — con tu **usuario o tu correo**, y la contraseña.
  - Si ese dispositivo ya tenía compras o alertas propias, te pregunta: **Cargar los de mi cuenta**
    (queda solo lo de la cuenta) o **Juntar con los de este dispositivo** (se suman sin perder nada).
  - Si está recién instalado, carga lo de tu cuenta directamente.
- **La sesión queda iniciada**: no vuelve a pedirte la contraseña. Si cierras sesión, recuerda tu
  usuario para que solo tengas que escribir la contraseña. La contraseña no se guarda en el
  dispositivo.
- **Olvidé mi contraseña** — escribe tu correo y te llega un código de 6 cifras; con él pones una
  contraseña nueva. **Si no lo ves, mira en spam.** Al ponerla, se cierra la sesión en tus otros
  dispositivos.
- **Cambiar contraseña** y **Cerrar sesión**, en la misma pantalla.

Sincroniza solo: al abrir la app, cada 5 minutos mientras está abierta y unos segundos después de
cada cambio. La pantalla dice cuándo fue la última vez, o qué falló.

**Si cambias lo mismo en dos dispositivos:** dos compras nuevas quedan las dos; la misma compra
editada en los dos se queda con la edición más reciente; y si en uno la borras y en el otro la
editas después, se conserva: nada se borra en silencio.

Tus datos se guardan en el servidor de Criptos Trader, que puede leerlos: es lo que permite
recuperar la cuenta si olvidas la contraseña.

### Desde el navegador

La misma app, sin instalar nada: **https://criptostrader.serviciosmultiplesorion.com**.
Entra con tu cuenta y ves lo mismo que en el PC y en el teléfono. La primera vez tarda unos
segundos en cargar; después, casi nada.

**Avisos en el navegador:** con la pestaña abierta, aunque estés en otra pestaña o en otro
programa, las alertas, los cambios de sugerencia, las noticias y los datos de EE. UU. llegan
como notificaciones del navegador. La primera vez pulsa **Dar permiso** en *Alertas*: el
navegador solo deja pedirlo después de que toques algo. Si estás mirando la pestaña no sale
notificación, porque ya lo ves en la app. Con la pestaña cerrada no llega nada.

**El precio en la pestaña:** el título de la pestaña lleva el precio delante
(*$116.13 ▲2.3% · Criptos Trader*), así lo ves sin entrar. Con la pestaña de fondo el navegador
la frena y se renueva más o menos una vez por minuto. Si el precio se queda viejo, sale con ⏸.

### Vincular sin cuenta

Otra forma, sin usuario ni contraseña, para quien prefiera que **ni el servidor pueda leer sus
datos**: los dispositivos se unen con un vínculo y todo **se cifra en el dispositivo antes de subir**. A
cambio, no hay recuperación: si pierdes el vínculo y todos tus dispositivos, lo del servidor no se
puede leer. No se usa a la vez que una cuenta.

- **Empezar aquí (primer dispositivo)** — escribe la dirección del servidor
  (`https://sync.serviciosmultiplesorion.com`) y pulsa. Sube lo que tienes en este dispositivo.
- **Vincular otro dispositivo** — enseña un vínculo; cópialo y pásatelo al otro dispositivo (por
  ejemplo por correo o mensaje a ti mismo). Quien tenga ese vínculo puede ver y cambiar tus
  datos: no se lo pases a nadie más.
- En el otro dispositivo, pega el vínculo y elige:
  - **Unirme y usar sus datos** — lo normal en un dispositivo recién instalado: se queda con
    lo del primero y no duplica las alertas por defecto.
  - **Unirme juntando con los de aquí** — si ya tenías compras registradas en los dos.

Después sincroniza solo: al abrir la app, cada 5 minutos mientras está abierta y unos
segundos después de cada cambio. La tarjeta dice cuándo fue la última vez, o qué falló.

**Si cambias lo mismo en dos dispositivos:** dos compras nuevas quedan las dos; la misma compra
editada en los dos se queda con la edición más reciente; y si en uno la borras y en el otro
la editas después, se conserva: nada se borra en silencio.

**Desvincular** deja tus datos en el dispositivo. Si además borras el servidor, los demás dejan de
sincronizar. Guarda el vínculo o exporta una copia de vez en cuando: si pierdes todos tus
dispositivos, lo del servidor no se puede leer sin él.

### Mis datos

**Exportar** guarda tus compras, alertas y estrategia en un archivo; **Importar** lo trae a
este dispositivo, preguntándote antes si **unir** (no se pierde nada de ningún lado) o
**reemplazar** (queda solo lo del archivo). Sirve como copia de seguridad o para pasar tus
datos sin servidor. El archivo **no va cifrado**: guárdalo donde guardarías un extracto del
banco.

### Log detallado

Apagado por defecto. Enciéndelo solo si algo va mal y quieres ver qué está pasando por
dentro: anota cada precio y cada indicador, y eso engorda mucho el registro.

### La versión

Al final del todo se lee qué versión tienes abierta. Es el primer dato que hace falta si algo
falla. En Windows, una copia que no se instaló se marca **(sin instalar)**: es la que no se
actualiza sola.

---

## 8. La ventanita de la barra de tareas

*(Solo Windows.)*

Es una tira pegada a la barra de tareas que va marcando el precio mientras trabajas:

```
SOL $99.88 ▲2.81% +$27.20 (+1.4%) mantener
```

Qué aparece ahí lo eliges tú en [Ajustes](#7-ajustes).

- **Arrástrala** para moverla donde quieras. Se queda donde la dejes.
- **Púlsala** para abrir la configuración.
- **Botón derecho** abre el mismo menú que el icono del reloj.
- **Se aparta sola.** Si abres un juego o un vídeo a pantalla completa, se esconde y vuelve
  cuando sales.
- Se mantiene **por encima** de las demás ventanas, y nunca es más alta que la barra de
  tareas.

---

## 9. El icono junto al reloj

*(Solo Windows.)*

Pasando el ratón por encima se lee el precio y la variación del día. Pulsándolo se abre la
configuración. Con el botón derecho sale el menú:

| Opción | Qué hace |
|---|---|
| **Configuración** | Abre la app en la pantalla de inicio |
| **Alertas** | Va directo a las alertas de precio |
| **Plan de inversión** | Va directo al plan |
| **Actualizar ahora** | Pide el precio sin esperar |
| **Abrir gráfico** | Abre el gráfico en tu navegador |
| **Iniciar con Windows** | Se marca cuando está activado |
| **Ocultar ticker** / **Mostrar ticker** | Quita o devuelve la ventanita |
| **Buscar actualizaciones** | Mira si hay versión nueva |
| **Salir** | Cierra la app del todo |

Cerrar la ventana de configuración **no cierra la app**: sigue viva en la bandeja. Se sale
por **Salir**.

La entrada de actualizaciones va cambiando sola: dice *Buscando actualizaciones…* mientras
mira, y **Reiniciar para actualizar a X** cuando ya está descargada y solo falta reiniciar.

---

Desarrollado por [Marlon Morales](https://www.linkedin.com/in/marlon-morales-8b5372136).
