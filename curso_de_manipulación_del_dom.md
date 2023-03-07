# Curso de Manipulación del DOM

## 1. ¿En qué momento se construye el DOM?
    Critical Rendering Path.

## 2. Una Web API nos permite…
    Utilizar JS para manipular el DOM.

## 3. El siguiente NO es un selector de nodos
    getElementByDataset

## 4. Cuál es la diferencia entre el tipo de dato NodeList y Array?
    NodeList no tiene métodos como map, filter o some.

## 5. ¿Qué tipo de dato retorna el selector querySelectorAll?
    NodeList

## 6. El método correcto para crear un nuevo nodo es:
    document.createElement
## 7. Cuál es la diferencia entre append() y appendChild()?
    append permite agregar más de un solo nodo.

## 8. El siguiente NO es un método para agregar nodos
    appendBefore

## 9. La mejor forma de agregar un nodo es:
    Ninguna es mejor que otra. Cada cual tiene su caso de uso.

## 10. Para el DOM, la diferencia entre un atributo y una propiedad es
    Los atributos se usan solo como valores iniciales. Luego son todas propiedades.

## 11.La siguiente línea de código, asumiendo que node ni ninguno de sus padres es null:
    node.parentElement.parentElement.removeChild(node); 
    Da como resultado:
    #Error, solo se puede eliminar un hijo directo.

## 12. La forma en que JavaScript reacciona a lo que sucede en el navegador se realiza por
    Eventos

## 13. La técnica de Delegar Eventos consiste en:
    Utilizar un solo evento en el nodo padre para reaccionar a lo que sucede en los hijos.

## 14. Lo siguiente es FALSO sobre Eventos
    Solo los <button> pueden tener Eventos.

## 15. La Web API de Intl (internationalization) nos permite:
    Dar formato a fechas y monedas

## 16. La Web API de Intersection Observer permite:
    Conocer cuándo un elemento es visible en el viewport.

## 17.Cuando hablamos de manipulación del DOM, la siguiente afirmación es FALSA
    Necesito librerias externas como jQuery para hacerlo.

## 18. El método appendChild() se utiliza para:
    Agregar un nodo al final de un contenedor padre.

## 19. Al hablar sobre Eventos, la siguiente afirmación es FALSA:
    Solo se puede agregar un evento por nodo.

## 20. ¿Cómo se evita que un Evento se siga propagando?
    Utilizando event.stopPropagation() en el nodo donde debe parar.
