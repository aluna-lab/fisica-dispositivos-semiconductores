# Física de Dispositivos Semiconductores · laboratorios interactivos

Laboratorios virtuales y teoría para la asignatura **Física de Dispositivos Semiconductores** de la Licenciatura en Tecnología, ENES Juriquilla, UNAM.

Cada página es un archivo HTML autónomo que funciona en cualquier navegador moderno, sin instalar nada y sin servidor. Tiene dos pestañas:

- **Laboratorio**: controles, gráficas interactivas, lecturas, ecuaciones evaluadas con los valores elegidos y retos para el alumno.
- **Teoría**: explicación breve de los conceptos y de las fórmulas principales de la unidad.

## Contenido

| Archivo | Unidad | Tema |
|---|---|---|
| `index.html` | — | Página de inicio del curso con todas las unidades |
| `u1-cristales-y-bandas.html` | 1 | Redes de Si, Ge y GaAs, índices de Miller, zona de Brillouin, bandas por pseudopotencial empírico, Kronig–Penney, masa efectiva |
| `u2-portadores.html` | 2 | Densidad de estados × Fermi–Dirac, semiconductor intrínseco y dopado, dependencia con T, sistemas 3D, 2D, 1D y 0D |
| `u3-transporte.html` | 3 | Deriva y movilidad, dispersión, saturación de velocidad, difusión, relación de Einstein, efecto Hall |
| `u4-fotoluminiscencia.html` | 4 | Fotogeneración, recombinación radiativa, SRH y Auger, cuasiniveles de Fermi, espectros de PL y TRPL |
| `u5-union-pn.html` | 5 | Diagrama de bandas, Poisson, ley de la unión, curva I–V, capacitancia C–V, ruptura Zener y avalancha |
| `u7-pl-raman-2d.html` | 4 y 7 | PL y Raman de monocapas, bicapas y heteroestructuras de TMDs (MoS₂, MoSe₂, WS₂, WSe₂) |

Para abrir directamente la teoría de una unidad se puede agregar `#teoria` al final de la dirección, por ejemplo `u3-transporte.html#teoria`.

## Publicar con GitHub Pages

1. Crea un repositorio nuevo en GitHub y sube todos los archivos de esta carpeta a la raíz de la rama `main` (incluido `.nojekyll`).
2. En el repositorio entra a **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
4. Después de uno o dos minutos el sitio queda en `https://<tu-usuario>.github.io/<nombre-del-repositorio>/`.

Para usarlo sin internet basta con abrir `index.html` en el navegador. Las tipografías se cargan de Google Fonts; sin conexión se usan tipografías del sistema y todo lo demás funciona igual.

## Modelos y fuentes

Los cálculos se hacen en el navegador con modelos simplificados con fines didácticos; los valores numéricos son aproximados. Cada página indica al pie los modelos y las referencias que usa, entre ellas:

- Pseudopotencial empírico: Cohen y Bergstresser, Phys. Rev. 141, 789 (1966).
- Movilidad: Arora, Hauser y Roulston, IEEE Trans. Electron Devices (1982), para Si; Sotoodeh, Khalid y Rezazadeh, J. Appl. Phys. (2000), para GaAs.
- Parámetros de materiales a 300 K: Neamen; Sze y Ng, *Physics of Semiconductor Devices*; Ioffe NSM Archive.
- Excitones en TMDs: potencial de Rytova–Keldysh; masas y apantallamiento de Goryca et al., Nat. Commun. 10, 4172 (2019); alineación de bandas de Kang et al., Appl. Phys. Lett. 102, 012111 (2013).

## Autoría y licencia

© 2026 Elodie Strupiechonski (ENES Juriquilla, UNAM) y Andrés de Luna Bugallo (CFATA, UNAM).

Este material se distribuye bajo la licencia [Creative Commons Atribución 4.0 Internacional (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.es). Puedes copiarlo, adaptarlo y redistribuirlo, incluso con fines comerciales, siempre que des crédito a los autores e indiques si hiciste cambios.
