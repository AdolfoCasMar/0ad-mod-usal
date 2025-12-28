# 0ad-mod-usal
Este es un mod del juego 0AD para los alumnos de la USAl del Grado en Desarrollo de Aplicaciones 3D Interactivas y Videojuegos
Proyecto de Modding 0 A.D. - Entornos 3D y Personajes

Asignatura: [Nombre de tu Asignatura]

Institución: Universidad de Salamanca (USAL)

Profesor: [Tu Nombre]
1. Introducción

Este repositorio contiene el mod de trabajo para la asignatura. El objetivo es sustituir y mejorar los activos (assets) 3D del juego original 0 A.D. por vuestros propios modelados y animaciones.
2. Requisitos Previos

Antes de empezar, debes tener instalado:

    0 A.D. (Alpha 26 o superior): Descargar aquí

    Blender (3.0 o superior): Para el modelado y rigging.

    Git: Para gestionar vuestras entregas.

3. Configuración del Entorno de Trabajo

Para que el juego reconozca vuestro trabajo, debéis clonar este repositorio en la carpeta de mods del usuario:
Rutas según Sistema Operativo:

    Windows: %Documents%\My Games\0ad\mods\

    Linux: ~/.local/share/0ad/mods/

    macOS: ~/Library/Application Support/0ad/mods/

Pasos:

    Abre una terminal en la carpeta mencionada arriba.

    Clona el repositorio: git clone https://github.com/tu-organizacion/0ad-mod-clase.git

    Asegúrate de que la carpeta se llame exactamente igual que el ID definido en el mod.json.

4. Estructura del Repositorio

    /art/meshes/structural/: Ubicación para los modelos de Entornos (casas, templos, muros). Formato .dae.

    /art/meshes/skeletal/: Ubicación para los modelos de Personajes y mallas con esqueleto.

    /art/textures/skins/: Texturas (Diffuse, Normal, Specular).

    /art/actors/: Archivos XML que vinculan la malla 3D con su textura y animaciones.

5. Flujo de Trabajo y Entrega

Para mantener el orden en la clase, seguiremos este protocolo:

    Crea tu rama: No trabajes en main. Crea una rama con tu nombre: git checkout -b apellido-nombre.

    Modelado en Blender:

        Usa escala métrica (1 unidad = 1 metro).

        Exporta como Collada (.dae).

        Importante: Al exportar personajes, asegúrate de marcar "Selection Only" y "Include Armatures".

    Prueba en el juego:

        Abre 0 A.D. -> Mod Selection -> Activa "Proyecto Modelado 3D Clase".

        Ve a Tools -> Atlas Editor para colocar tu modelo en un mapa y verificar escalas y texturas.

    Subida (Commit): git add . git commit -m "Añadido modelo de casa celta - v1" git push origin apellido-nombre

6. Herramientas Útiles

    Actor Editor: Disponible dentro de las herramientas del juego para previsualizar modelos en tiempo real.

    0 A.D. Blender Addon: Recomendado para facilitar la exportación de animaciones.
