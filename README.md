# Máquina de Galton interactiva

La *Máquina de Galton interactiva* es una versión web modernizada del clásico tablero de clavos que permite experimentar con la distribución binomial y ver cómo se aproxima a la curva normal al aumentar el número de ensayos. El proyecto, creado por Juan José de Haro (2025), está disponible en [https://github.com/jjdeharo/maquina_galton](https://github.com/jjdeharo/maquina_galton).

## Descripción del proyecto

La aplicación muestra un tablero de clavos configurable y un histograma animado que registra la posición final de cada bola. Con los controles se puede ajustar:

- El número de filas del tablero, el tamaño de cada bola y la cantidad total de bolas a soltar.
- El intervalo de salida, la probabilidad `p` de desviarse hacia la derecha y el coeficiente de rebote.
- La gravedad expresada en múltiplos de `g` para acelerar o ralentizar la simulación.
- El idioma (español, catalán, gallego, euskera o inglés) y el tema visual (automático, claro u oscuro).

Cada contenedor inferior muestra el número de bolas que ha recibido y el histograma compara los datos obtenidos con la distribución binomial teórica y su aproximación normal.

La interfaz incluye un botón de ayuda que explica el funcionamiento de la máquina y cómo utilizarla en el aula para ilustrar conceptos de probabilidad y estadística.

## Uso

1. Ajusta los parámetros en el panel izquierdo; los cambios se aplican automáticamente.
2. Pulsa **Iniciar** para comenzar a soltar bolas y **Pausa** si necesitas detener la simulación.
3. Usa **Reiniciar** para volver a los valores iniciales.
4. Cambia de idioma o tema desde los selectores del encabezado.
5. Abre el botón **Ayuda** para leer una explicación detallada de la Máquina de Galton y la interpretación del experimento.

## Licencias

- Todo el código está publicado bajo licencia **AGPL v3**. Incluye un archivo `LICENSE.txt` con el texto completo de la licencia y se recomienda añadir una nota al inicio de cada archivo de código indicando que se aplica AGPL v3.
- Los materiales educativos y la documentación se ofrecen bajo **CC BY-SA 4.0**, lo que permite compartir y adaptar siempre que se atribuya y se mantenga la misma licencia.

### Pie de página de la aplicación

1. © [Juan José de Haro](https://bilateria.org)
2. Licencia del código: [AGPL v3](https://www.gnu.org/licenses/agpl-3.0.html) · Contenido: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
