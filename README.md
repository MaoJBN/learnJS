Apuntes de clases sobre los componentes 
nos ubicamos en la carpeta components
se cra el componente la primera en mayuscula y el .astro ejemplo (Button.astro)
dentro de ese archivo 
hacemos el apartado de js
---
---
y despues sigue el codigo html

IMPORTANTE (La Importacion)
En donde yo quiera que se importe por ejemplo el index

COPIAMOS DENTRO DE LO SIGUIENTE

---
import Button from 'lugar del componente';
---

copiamos el html normal del HTML

y en el HTML del index copiamos 

<Buttom />

y sale la componente que colocamos 

---
conts {text} = Astro.props
---

Leer la documentacion de las componentes

