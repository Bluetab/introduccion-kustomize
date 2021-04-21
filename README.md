# **Introducción a Kustomize**

Kustomize es una herramienta para tratar los ficheros YAML de kubernetes como plantillas, de forma que podemos personalizar distintos elementos manteniendo una base común. Es un instrumento muy útil cuando necesitamos desplegar el mismo código en distintos entornos aplicando pequeñas modificaciones.

Este repositorio forma parte de la charla [Introducción a Kustomize](https://youtu.be/uPtIRBOd2AE).Contiene varios ejemplos para aprender a usar esta herramienta desde cero.

Para más información se puede consultar la [guía oficial](https://kubectl.docs.kubernetes.io/guides/config_management/).

## **Componentes**

1. **Images**: Parametrizar el nombre y el tag de las imágenes docker.
2. **Config Maps**: Distintas formas de modificar las variables de entorno de los contenedores.
3. **Labels y Annotations**: Etiquetas y anotaciones comunes a todos los elementos desplegados de forma automatizada.
4. **Patches**: Elemento genérico para modificar cualquier parte del código.

## **Licencia**

Este workshop está licenciado bajo licencia GPLv3 (ver [LICENSE](LICENSE) para más detalle).

## **Autor**

Javier Rodríguez [github](https://github.com/JevyanJ) | [linkedIn](https://www.linkedin.com/in/javier-rodriguez-87541a32)
