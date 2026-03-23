***Plantilla de Apuntes***
En esta carpeta se encuentra la plantilla utilizada para la confección de apuntes y minutas del seminario. El diseño del documento es modular, de manera que los parámetros son sencillos de modificar en caso de que se quiera adaptar para exposiciones de otra instancia.

***📦Archivos***
El repositorio incluye el archivo template.zip, el cual contiene la estructura completa del proyecto para su uso directo en Overleaf o cualquier distribución local de LaTeX. Asimismo, se adjunta plantilla.pdf como una previsualización terminada, permitiendo revisar el diseño final, los entornos matemáticos y la jerarquía visual.

***📂 Estructura del Proyecto***
Plaintext
.
├── main.tex             # Archivo principal (aquí se escribe el contenido)
├── config/
│   ├── preambulo.sty    # Carga de paquetes, macros y entornos de teoremas
│   └── portada.sty     # Configuración del título, autores y afiliación
└── img/                 # Repositorio de imágenes y logos

***🚀 Guía de Uso***
1. Metadatos
En el preámbulo de main.tex, actualiza el título de la sesión, el nombre del expositor y la fecha:

Fragmento de código
\title{Título de la sesión}
\author{Nombre del expositor}
\date{\today}

2. Entornos Matemáticos
La plantilla incluye entornos preconfigurados para mantener la consistencia visual:

Definiciones: \begin{defn} ... \end{defn}

Axiomas: \begin{axm} ... \end{axm}

Teoremas y Lemas: \begin{thm} y \begin{lem} (incluyen soporte para \begin{proof})

Ejemplos: \begin{exmp} ... \end{exmp}

***🛠️ Personalización***
Si deseas cambiar el comportamiento global del documento (como el grosor de las líneas del encabezado o los colores de los teoremas), debes modificar los archivos dentro de la carpeta config/.

paquetes.sty: Controla la lógica de los contadores y el estilo de los teoremas.

portada.sty: Contiene el comando \encabezadoUC que genera la cabecera institucional.