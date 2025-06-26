# Guía de Contribución para "The Hopefully This Works Handbook"

¡Gracias por tu interés en contribuir a "The Hopefully This Works Handbook"! Este manual está diseñado para ser un recurso vivo y evolutivo, construido por y para la comunidad. Tu experiencia, tus anécdotas, tus herramientas favoritas y tus lecciones aprendidas son increíblemente valiosas.

> **Importante:** Al contribuir, aceptas regirte por nuestro [Código de Conducta](CODE_OF_CONDUCT.md).

## ¿Cómo Puedes Contribuir?

Hay muchas maneras de aportar a este manual, sin importar tu nivel de experiencia con Git o Markdown:

### 1. 🐛 Reportar Errores o Sugerir Mejoras

Si encuentras un error tipográfico, un enlace roto, una inconsistencia, o simplemente tienes una idea para mejorar una sección existente o añadir una nueva:

1. **Abre una "Issue" (incidencia) en GitHub.**
2. Ve a la sección de "Issues" de nuestro repositorio.
3. Haz clic en "New issue" (Nueva incidencia).
4. Describe claramente el problema o tu sugerencia. Sé lo más específico posible.
5. Si es una mejora, explica por qué crees que sería beneficiosa.

### 2. 💡 Proponer Nuevas Ideas o Contenido

¿Tienes una fase que crees que falta, una plantilla que te ha salvado la vida, o una lista de verificación esencial? ¡Nos encantaría verla!

1. **Abre una "Issue" (incidencia) en GitHub.**
2. Selecciona "New issue".
3. Utiliza un título claro que resuma tu propuesta (ej: "Nueva plantilla: Agenda para el Día del Evento").
4. Describe tu idea en detalle, explicando su propósito y cómo encajaría en el manual. Esto puede iniciar una discusión valiosa.

### 3. 🔧 Realizar Contribuciones Directas (Pull Requests)

Si te sientes cómodo trabajando con Git y Markdown, puedes contribuir directamente al código o al texto del manual.

#### Pasos para contribuir:

1. **Haz un "Fork" del repositorio**: Copia el repositorio a tu cuenta de GitHub.

2. **Clona tu "Fork" localmente**:
   ```bash
   git clone https://github.com/tu-usuario/the-hopefully-this-works-handbook.git
   ```

3. **Crea una nueva rama (branch)**:
   ```bash
   git checkout -b mi-contribucion-descriptiva
   ```
   > Usa un nombre que describa tu cambio, ej: `fix-typo-logistics` o `add-template-event-proposal`

4. **Realiza tus cambios**:
   - Edita los archivos Markdown (`.md`) para el contenido del `handbook/`
   - Añade nuevas plantillas en el formato adecuado en `templates/`
   - Crea nuevas checklists en `checklists/`
   - Añade o actualiza recursos en `resources/`
   - Asegúrate de que tus cambios se alineen con la estructura y el tono del manual

5. **Comprueba tu trabajo**: Asegúrate de que los enlaces funcionan y que el formato Markdown es correcto.

6. **Realiza un "commit" de tus cambios**:
   ```bash
   git commit -m "Descripción concisa de mis cambios"
   ```

7. **Sube tus cambios a tu "Fork"**:
   ```bash
   git push origin mi-contribucion-descriptiva
   ```

8. **Crea un "Pull Request" (Solicitud de Extracción)**:
   - Ve a tu "Fork" en GitHub
   - Deberías ver una opción para crear un "Pull Request" desde tu rama hacia la rama `main` de este repositorio
   - Describe claramente los cambios que has realizado y por qué son importantes
   - Haz referencia a cualquier "Issue" relacionada (ej: "Cierra #123")

### 4. 📖 Compartir Anécdotas y "War Stories"

Una de las esencias de este manual es aprender de las experiencias reales, incluso (y especialmente) de aquellas que no salieron como se esperaban. Si tienes una "war story" (historia de batalla) o una lección aprendida de un evento que organizaste:

- **Puedes abrir una "Issue"** y contarnos tu historia.
- **O puedes proponer un "Pull Request"** para añadirla (anonimizada si es necesario) en la sección `handbook/07-hopefully-it-worked-learnings.md` o en un nuevo archivo dentro de `examples-and-case-studies/`.

## 📋 Directrices Generales

- **Lenguaje**: El manual está en español. Mantengamos la consistencia.

- **Tono**: Conserva el tono pragmático, humorístico y de resiliencia del manual.

- **Claridad y Concisión**: Intenta que tus contribuciones sean fáciles de entender y directas al punto.

- **Markdown**: Utiliza el formato Markdown estándar para el contenido.

- **Licencia**: Todas las contribuciones a este repositorio se considerarán bajo la Licencia MIT.

---

## 🙏 ¡Gracias por ayudar a que "The Hopefully This Works" Handbook funcione aún mejor para todos!

*"La mejor contribución es aquella que viene del corazón y la experiencia... hopefully it helps others too!"*