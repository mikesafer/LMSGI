# EJERCICIO MARKDOWN LMSGI
![Titulo](https://www.imaginarycloud.com/blog/content/images/size/w754/2023/03/JSON-vs-Yaml.webp)

# Enunciado
>1. Crear repositorio público en Github.
>2. Información y ejemplo sobre YAML.
>3. Información y ejemplo sobre JSON.
>4. Comparativa entre ambos.

## Introducción

YAML (Yet Another Markup Language) y JSON (JavaScript Object Notation) son formatos de serialización de datos comunes utilizados en aplicaciones web y de backend. Ambos tienen sus propias características y ventajas, y es importante comprender las diferencias entre ellos para elegir el formato adecuado en diferentes situaciones.

### [YAML](https://www.mclibre.org/consultar/informatica/lecciones/formato-yaml.html)

YAML es un formato legible por humanos que se usa comúnmente para la configuración, los archivos de definición y otros datos estructurados. A continuación se muestra un ejemplo de un archivo YAML que representa la información de un usuario:

```yaml
usuario:
  nombre: Miguel Sáez
  edad: 38
  email: miguelsaez@email.com
```

### [JSON](https://www.mclibre.org/consultar/informatica/lecciones/formato-json.html)

JSON es un formato de intercambio de datos ligero y fácil de leer que se utiliza ampliamente en aplicaciones web y de backend. El mismo ejemplo de información de usuario en JSON se vería así:

```json
{
  "usuario": {
    "nombre": "Miguel Sáez",
    "edad": 38,
    "email": "miguelsaez@email.com"
  }
}
```

## Comparativa

Ambos formatos tienen similitudes, como la capacidad de representar datos estructurados y la legibilidad para los humanos. Sin embargo, existen algunas diferencias clave:

- **Legibilidad**: YAML tiende a ser más legible para los humanos debido a su sintaxis simplificada y su enfoque en la legibilidad.
- **Compatibilidad con lenguajes**: JSON es ampliamente compatible con muchos lenguajes de programación, mientras que YAML puede tener problemas de compatibilidad con ciertos lenguajes.
- **Uso de comas y comillas**: JSON requiere el uso de comas y comillas para estructurar los datos, mientras que YAML utiliza la indentación para definir la estructura.
- **Extensiones**: YAML tiene la capacidad de incluir comentarios y referencias, lo que lo hace más flexible en ciertos casos.

>[!NOTE]
>**En resumen, la elección entre YAML y JSON depende de las necesidades específicas del proyecto, la legibilidad para los humanos y la compatibilidad con los lenguajes de programación utilizados.**
