REGLAS GENERALES PARA TENER EN CUENTA: 

.!IMPORTANTE.

## Convenciones Git

- Usar **`main`** para la rama principal
- Para las demás ramas, usar Snake Case. 
Si quiero trabajar sobre el feature de login, podría ser `login_feature` | `login` | `users_auth`  inclusive. Algo que sea descriptivo a lo que se realizará.
- Cuando guardemos un commit, usar el prefijo en el mensaje:
    - ***Indicar el tipo*** de commit (los principales)
        1.  `feat`: Una nueva característica o contribución a una
        2.  `fix`: Una solución a un bug o error
        3. `docs`: Documentación
        4. `perf`: Código que mejora el performance
        5. `refactor`: Código que no es sobre docs, no mejora el performance o es sobre una característica. Usualmente solo cambia la forma de algo ya hecho sin que entre en un **perf.**
        6. `test`: Cuando se trata de código para testing


EJEMPLOS: https://prnt.sc/2D2YEj7mZ6xI  -- Copiar y pegar en el buscador el link

¡No hacer ningún commit sin especificar su función!


## Nomenclatura (Estrategias de Nombrado)

1. Utilizar inglés para todo
    
    Con el 99% de los paquetes generalmente, ***tendremos que usar este idioma***
    
    Si queremos un empleo con un gran salario, generalmente, ***tendremos que usar este idioma***
    
    Si queremos trabajar remoto, generalmente , ***tendremos que usar este idioma***
    
    Si quieren lucir este proyecto en su CV y que lo buenos recruiters lo tomen en cuenta, generalmente, ***tendremos que usar este idioma***
    
    ¡Razones para usar el inglés sobran!
    
    Si les cuesta, siempre tengan a un lado el traductor de Google y hagan como muchos compañeros devs en sus inicios 👌
    
    --------------------------------------------------------------------------------------

2. Camel Case para:

- Funciones
- Variables

No importa si el nombre de la función o variable es largo, sean lo más descriptivos y declarativos posible.

Si alguien externo, colaborador, jefe, entusiasta, quien sea, quiere comprender el código, lo mejor que se puede hacer es: ¡Escribir bien para ahorrar tiempo!

- Eviten acortar las palabras y cosas por el estilo.
- Sean lo más declarativos y descriptivos posible

*Escriban para ustedes en 3 meses, cuando ya no se acuerden del código, lo puedan retomar sin problemas*

EJEMPLO> https://prnt.sc/jOy7MIovwhSe -- Copiar y pegar en el buscador el link


--------------------------------------------------------------------------------------


3. **Pascal Case** para:
    - Clases de los Servicios
    - En todas las Clases donde tengan poder de edición
    - Clases | Modelos Sequelize
    👁️¡Ojo! Los modelos, son clases, las propiedades y columnas de estos, se usará Snake Case (Punto 4)
    
    Aquí es muy importante que no recorten palabras, sean lo más descriptivos posible

    EJEMPLO> https://prnt.sc/mOimTbY-ajmq -- Copiar y pegar en el buscador el link


4. **Snake Case** se usará para
    - ORM Sequelize cuando indiquemos el nombre de tablas sql
    - En las migraciones, cuando se creen las tablas, verificar el nombrado y *verificarlo* cuando se usa en el modelo
    
    En este caso, la tabla `users`, se crea con ese nombre. Pero Si se tendría que hacer la entidad de números telefónicos de los usuarios, sería algo como: `users_phones`

    EJEMPLO> https://prnt.sc/i6oUXrsi4nRn -- Copiar y pegar en el buscador el link


5.  Usar Dot Notation en vez de Bracket Notation 

 EJEMPLO> https://prnt.sc/Zo_ljm-SEYx1 -- Copiar y pegar en el buscador el link