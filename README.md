# 🕹️ Sopa de Letras by Chibi: Edición Groovy 🌈

Este proyecto es un juego de Sopa de Letras (Word Search) con una interfaz gráfica (GUI) de estilo retro, desarrollado en Python utilizando la librería Tkinter.

## 📝 Descripción del Juego

El objetivo es encontrar todas las palabras secretas escondidas en el tablero de letras.

### 🎮 Cómo Jugar

1.  **Selección de Dificultad:** Al iniciar, elige entre tres dificultades:
    * **Groovy Fácil:** Tablero pequeño (8x8) y pocas palabras.
    * **Retro Medio:** Tablero mediano (10x10) y más palabras.
    * **Vintage Pro:** Tablero grande (12x12) y el mayor número de palabras.
2.  **Selección de Letras:** Haz clic en la primera letra de una palabra y luego continúa haciendo clic en las letras adyacentes hasta que completes la palabra. **Importante:** La selección debe ser en línea recta (horizontal, vertical o diagonal).
3.  **Comprobar:** Una vez seleccionada la palabra completa, haz clic en el botón **"Comprobar"**.
    * Si la palabra es correcta y es una de las palabras objetivo (incluyendo el orden inverso), se marcará en verde en el tablero y se tachará en el panel lateral.
    * Si no es correcta, la selección se limpiará.
4.  **Botones de Ayuda:**
    * **Limpiar:** Deshace la selección actual.
    * **Pista:** Revela y marca automáticamente una de las palabras aún no encontradas.
    * **Nueva Sopa / Volver al Inicio:** Permite empezar un nuevo juego o cambiar la dificultad.

¡El juego finaliza cuando encuentras todas las palabras!

---

## 🛠️ Requisitos e Instalación

Para poder jugar, debes **descargar el archivo fuente** del juego y ejecutarlo en tu computadora.

### Requisitos

Necesitas tener instalado:

* **Python 3.x**
* **Tkinter** (Normalmente viene incluido con la instalación estándar de Python).

### Ejecución

1.  **Descarga el código:** Asegúrate de tener el archivo `sopa_de_letras.py` (el script que subiste) en una carpeta local.
2.  **Abre tu terminal/consola** (Símbolo del sistema, PowerShell, Terminal, etc.).
3.  **Navega a la carpeta** donde guardaste el archivo:
    ```bash
    cd /ruta/donde/guardaste/el/archivo
    ```
4.  **Ejecuta el script de Python:**
    ```bash
    python sopa_de_letras.py
    ```

5.  **O descarga el exe: **
    ```bash
    sopa_de_letras.exe
    ```

**Nota:** El código fuente hace referencia a un archivo de ícono (`IconoDeAmbos.png`) y un listado de palabras (`listado-general.txt`). Si estos archivos no están presentes en la misma carpeta que el script, el juego usará las palabras predeterminadas y podría mostrar errores en la consola al intentar cargar el ícono, pero la funcionalidad principal no se verá afectada.