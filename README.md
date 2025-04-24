# Actividad CSS – Flexbox y Animaciones con Keyframes

## Descripción

En esta actividad se han aplicado conceptos clave de **CSS Flexbox** y **animaciones mediante keyframes**

---

## CSS

### 1. **Flexbox**

Se ha utilizado `display: flex` para organizar los elementos de forma flexible y eficiente en el contenedor. Esto permite alinear y distribuir los elementos de manera dinámica.

- **Dirección de los ítems**:  
  `flex-direction: column;`  
  Esto organiza los elementos en una columna, uno debajo del otro.

- **Alineación y distribución**:
  - `justify-content: center;` – Centra los ítems a lo largo del eje principal.
  - `justify-content: space-between;` – Distribuye los ítems con espacio entre ellos.

### 2. **Animaciones con Keyframes**

Las animaciones permiten transiciones suaves entre estilos de un elemento.

- Se ha utilizado la regla `@keyframes`, que define el cambio de estilos a lo largo del tiempo.
- Las animaciones están compuestas por **puntos clave** (keyframes), que marcan el estado inicial y final del movimiento.
- Se pueden definir etapas intermedias utilizando porcentajes o palabras clave como `from` y `to`.

**Ejemplo básico:**

```css
@keyframes mover {
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(100px);
  }
}
```
