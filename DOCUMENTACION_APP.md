Entendido 🙌, aquí tienes tu mismo texto pero con todos los **títulos en negrita**, sin cambiar ni mejorar nada del contenido:

---

# **Documentación del Proyecto**

---

## **Prompts Utilizados con IA**

Durante el desarrollo utilicé varias herramientas de IA (Gemini y Qwen). Algunos de los prompts más útiles fueron:

# **Lista de Prompts Iniciales y Resultados**

---

## **1. Crear la Estructura del Proyecto**

**Prompt:**
*"Crea la estructura de carpetas para un proyecto Android llamado 'FraseMotivadoraPersonalizada'. Debe incluir los siguientes paquetes:

* activities/ para la clase MainActivity.java.
* models/ para la clase Quote.java.
* network/ para la clase ApiService.java."*

**Resultado Obtenido:**
La estructura se generó correctamente en `src/main/java/com/example/motivation_app/`.
Esto ayudó a mantener el código ordenado desde el inicio.

---

## **2. Configurar build.gradle (Module: app)**

**Prompt:**
*"Configura el archivo build.gradle del módulo app para un proyecto Android con Java. Incluye las siguientes dependencias:

* OkHttp para solicitudes HTTP.
* Gson para parsear JSON.
* ConstraintLayout para diseños modernos.

**Resultado Obtenido:**
El `build.gradle` quedó configurado con las dependencias necesarias.
El uso de **ConstraintLayout** y **Material Components** me permitió mejorar la interfaz desde el inicio.

---

## **3. Crear AndroidManifest.xml**

**Prompt:**
*"Crea el archivo AndroidManifest.xml para un proyecto Android llamado 'FraseMotivadoraPersonalizada'. Incluye el permiso de internet y declara la actividad principal MainActivity."*

**Resultado Obtenido:**
Se generó un `AndroidManifest.xml` funcional con el permiso de **INTERNET** y la actividad principal declarada.
Esto evitó errores de permisos al hacer pruebas con llamadas de red.

---

## **4. Layout de la Pantalla Principal**

**Prompt:**
Crea el layout XML para la pantalla principal de una app de frases de motivación usando ConstraintLayout. Debe tener un EditText centrado para ingresar la emoción, un Button centrado abajo que diga 'Generar Frase Motivadora', un TextView para mostrar la frase, otro TextView para mostrar el autor, Incluye un ProgressBar para indicar carga.

**Resultado Obtenido:**
Se visualizo cada uno en pantalla, texto a ingresar, boton , frase generada y autor.

---

## **Reflexión sobre los Prompts Iniciales**

Estos primeros prompts fueron clave porque me dieron una **base sólida** para el proyecto: estructura, dependencias y estructura.
La IA me ayudó a ahorrar tiempo en tareas repetitivas (como configurar `build.gradle` o `AndroidManifest`), y yo pude enfocarme en lo creativo(de que se basara en las emociones y me diera una frase motivadora aleatoria).

---

## **Resultados Obtenidos**

* **Código de interfaz:** Se generó un `activity_main.xml` básico usando `ConstraintLayout`, lo que facilitó la responsividad.
* **Se generarón frases motivadoras** de forma aleatoria con cada click en el botón de generar frases.
* **Buena visualización** de lo generado, básico y sencillo para el usuario.

---

## **Problemas Encontrados y Soluciones con IA**

1. **Problema:** El `RelativeLayout` que usaba al inicio no era responsivo en todas las pantallas.

   * **Solución con IA:** Se me sugirió cambiar a `ConstraintLayout`, y con ejemplos de código entendí cómo anclar elementos de forma flexible.

2. **Problema:** Algunos errores en referencias de ID dentro del XML y Java.

   * **Solución con IA:** Qwen me recomendó correcciones automáticas y Gemini me mostró cómo estructurar mejor el `findViewById`.

3. **Problema:** errores en el Androidmanifest y gradles.

   * **Solución con IA:** Con prompts pedí me ayudara a encontrar los erroes, y a corregirlos despúes de encontrarlos para que quedara funcional la app.

---

## **Reflexión Final**

La experiencia de usar herramientas de IA como **Gemini, Qwen y Copilot** fue muy enriquecedora. Nos ayudaron a ahorrar tiempo, resolver errores y, sobre todo, a que la app quedara funcional con respecto a lo que necesitabamos; el generar frases motivadoras por medio de emociones ingresadas o palabras clave.

No siento que la IA haya hecho el trabajo por mí, sino que fue como un **mentor digital** que me iba dando ideas y ejemplos. Yo siempre tuve que validar, corregir y decidir qué quedaba mejor para mi proyecto y claro, también tomar encuenta las codificaciones que iba estructurando la IA, e ir aprendiendo poco a poco de lo que me generaba.

En conclusión: **usar IA en desarrollo de apps no reemplaza al programador, sino que potencia la creatividad y acelera el aprendizaje.**
