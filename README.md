
# Duelo de Magos

## 1. Introducción

Duelo de Magos es un juego creado con HTML, CSS y JavaScript. En el juego participan tres jugadores que tienen que atacarse entre ellos hasta que solamente quede uno con vida.

### Objetivo

El objetivo es eliminar a los otros dos jugadores y conseguir ser el último que siga vivo.

### Manual de instrucciones

1. Pulsar START para comenzar.
2. Cada jugador tiene 100 puntos de vida.
3. Cuando sea tu turno, puedes atacar o pasar.
4. Antes de atacar, tienes que elegir a quién quieres atacar.
5. Cada jugador tiene diferentes probabilidades de acertar.
6. Los ataques quitan entre 1 y 20 puntos de vida.
7. Gana el último jugador que tenga vida.

---

## 2. Código HTML

El HTML es la parte que crea los elementos que aparecen en la pantalla del juego.

He utilizado diferentes elementos:

- `div`: para separar las zonas de los jugadores.
- `h2` y `h3`: para los títulos.
- `button`: para crear los botones.
- `select`: para elegir los objetivos y las probabilidades.
- `span`: para mostrar la vida de cada jugador.

### Ejemplo de código

```html
<div class="jugador">
    <h3>Jugador 1</h3>
    <p>Vida: <span id="vida1">100</span></p>
    <button onclick="atacar(1)">Atacar</button>
</div>
```

Este código muestra el nombre del jugador, sus puntos de vida y el botón para atacar.

### Capturas del juego

Aquí se pueden ver algunas imágenes de cómo es el juego.

![Inicio](capturas/inicio.png)

Aquí se ve el inicio del juego principial tras darle al botón START. 


## 3. Código JavaScript

JavaScript es la parte que hace que el juego funcione. Se encarga de controlar los ataques, la vida y los turnos.

### Ejemplo de código

```javascript
let dano = Math.floor(Math.random() * 20) + 1;
```

Esta línea genera un número aleatorio entre 1 y 20, que representa los puntos de daño de un ataque.

---

## 4. Acerca de

**Creador:** Ángel Gómez Riera.

**Proyecto realizado para:** Actividad de programación.

**Tecnologías utilizadas:** HTML, CSS y JavaScript.

**Dedicatoria:**

Este proyecto se lo dedico a mi familia, pareja, amigos. OS AMO <3