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
5. [Estrategia](#5-estrategia)
6. [Ajustes](#6-ajustes)
7. [La ventanita de la barra de tareas](#7-la-ventanita-de-la-barra-de-tareas)
8. [El icono junto al reloj](#8-el-icono-junto-al-reloj)

---

## 1. La pantalla de inicio

Es lo primero que ves y lo que más vas a mirar.

**El precio**, grande, y debajo la **variación de las últimas 24 horas** en verde si sube y
en rojo si baja.

**Tu resultado.** Cuánto ganas o pierdes ahora mismo con lo que hayas comprado, en dólares y
en porcentaje. Si aún no has registrado ninguna compra, en su lugar hay un botón que te
lleva directo a donde se registran.

**Alertas que han saltado.** Aparece solo si ha saltado alguna. Guarda las últimas 20 de
esta sesión, la más reciente arriba.

**Sugerencia.** Una palabra —*comprar*, *vender* o *mantener*— con una línea explicando de
dónde sale. Se calcula con indicadores del mercado (medias móviles y RSI sobre velas de una
hora) y con tus propias compras. Si la apagas en [Estrategia](#5-estrategia), esta tarjeta
desaparece.

Debajo, los botones:

| Botón | Qué hace |
|---|---|
| **Actualizar ahora** | Pide el precio sin esperar al siguiente ciclo |
| **Mi inversión** | Solo aparece si ya registraste alguna compra |
| **Plan de inversión** | Cuánto invertir ahora, y qué pasó otras veces |
| **Alertas de precio** | Crear y administrar avisos |
| **Estrategia** | Perfil de riesgo y escalera de compra |
| **Ajustes** | Intervalo, apariencia, gráfico |
| **Manual de uso** | Esto que estás leyendo, dentro de la app |

No hace falta usar *Actualizar ahora*: el precio se refresca solo.

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

Debajo, la **acción sugerida** con su explicación: cuánto invertiría, por qué, y qué escalón
de tu escalera se ha activado.

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
- **Avisarme cuando haya una actualización** *(Windows)*
- **…aunque la app esté cerrada** *(Android)* — comprueba el precio de fondo cada **15, 30 o
  60 minutos**, que se elige en **Cada cuánto**. Menos de 15 no lo permite Android.
- **…y de los cambios de sugerencia** *(Android)* — avisa también cuando la sugerencia
  cambie.

**Comprobar ahora** *(Android)* hace una comprobación por el mismo camino que la automática.
Si una alerta está cruzada, el aviso llega en unos segundos: sirve para confirmar que todo
está bien configurado sin esperar.

Los avisos **quedan en el panel de notificaciones** después de desvanecerse, así que una
alerta que salta mientras no miras la pantalla no se pierde.

> **Android pide permiso para notificar.** Si falta, la pantalla lo dice y te ofrece un botón
> para darlo. Sin ese permiso no llega ningún aviso, por muchos interruptores que enciendas.

---

## 5. Estrategia

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

## 6. Ajustes

### Cada cuánto se consulta el precio

En el **teléfono**: 30 s, 1 min, 2 min, 5 min o 10 min. El mínimo es 30 segundos, y no es un
capricho: cada consulta enciende la radio del teléfono y eso lo paga la batería.

En **Windows**: 5 s, 10 s, 15 s, 30 s, 1 min, 2 min o 5 min.

En **Otro (segundos)** puedes escribir un número propio; debajo se lee el rango admitido y el
intervalo que está funcionando ahora mismo.

### Ticker de la barra de tareas *(solo Windows)*

Toda esta sección describe la ventanita, así que en el teléfono no aparece.

| Ajuste | Qué hace |
|---|---|
| **Iniciar con Windows** | La app se abre sola al encender el PC |
| **Tamaño de la letra** | Lo grande que se ve el texto del ticker |
| **Opacidad del fondo** | De transparente a sólido |
| **Mostrar variación 24 h** | Enseña o esconde el porcentaje del día |
| **Mostrar mi resultado** | Enseña o esconde tu ganancia o pérdida |
| **Mostrar la sugerencia** | Enseña o esconde la palabra final |

**Tema**: **Oscuro**, **Claro**, **Solana** o **Personalizado**.

Con **Personalizado** aparecen ocho colores para tocar uno a uno: **Fondo**, **Símbolo**,
**Precio**, **Subida**, **Bajada**, **Sugerir comprar**, **Sugerir vender** y **Sugerir
mantener**. Con un tema predefinido no se muestran, porque el tema los decide.

### Gráfico

La dirección que abre **Abrir gráfico**. Viene puesta y puedes cambiarla por la del sitio que
prefieras.

### Log detallado

Apagado por defecto. Enciéndelo solo si algo va mal y quieres ver qué está pasando por
dentro: anota cada precio y cada indicador, y eso engorda mucho el registro.

### La versión

Al final del todo se lee qué versión tienes abierta. Es el primer dato que hace falta si algo
falla. En Windows, una copia que no se instaló se marca **(sin instalar)**: es la que no se
actualiza sola.

---

## 7. La ventanita de la barra de tareas

*(Solo Windows.)*

Es una tira pegada a la barra de tareas que va marcando el precio mientras trabajas:

```
SOL $99.88 ▲2.81% +$27.20 (+1.4%) mantener
```

Qué aparece ahí lo eliges tú en [Ajustes](#6-ajustes).

- **Arrástrala** para moverla donde quieras. Se queda donde la dejes.
- **Púlsala** para abrir la configuración.
- **Botón derecho** abre el mismo menú que el icono del reloj.
- **Se aparta sola.** Si abres un juego o un vídeo a pantalla completa, se esconde y vuelve
  cuando sales.
- Se mantiene **por encima** de las demás ventanas, y nunca es más alta que la barra de
  tareas.

---

## 8. El icono junto al reloj

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
