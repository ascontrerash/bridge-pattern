# Bridge Design Pattern

Este patrón de diseño permite desacoplar una abstracción de su implementación, 
de manera que ambas puedan variar de forma independiente.

Supongamos que tenemos una clase abstracta en la que se define un método que deberá 
implementar cada clase que herede de ella: ¿cómo haríamos si una clase hija necesitase 
implementarlo de forma que realizase acciones diferentes dependiendo de determinadas circunstancias?.

En estos casos resultaría útil el patrón Bridge ya que 'desacopla una abstracción' 
(un método abstracto) al permitir indicar (durante la ejecución del programa) a una clase qué 'implementación' 
del mismo debe utilizar (qué acciones debe realizar).
