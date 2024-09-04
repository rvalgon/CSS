# Selectores
Los selectores se utilizan para delimitar los _elementos HTML_ de nuestra página web a los que les queremos aplicar un estilo concreto.

## Selector de **elemento**
Con los selectores de elementos podemos darle un estilo concreto a un elemento HTML.

````css
h1 {

}
````


## Selector **ID**
Con los selectores **id** podemos dar un estilo concreto a ciertas partes de nuestro documento HTML.

````css
#titulo {

}
````
````html
<h1 id="titulo">Título</h1>
 ````
La peculariedad de los selectores **id** es que están pensados para darle estilo a elementos concretos, sin que este estilo se repita en otras partes de nuestro documento HTML. Es decir, su función no es ser reutilizable.

## Selector **Class**
Con los selectores **class** podemos dar estilos a partes simlares de nuestro documento HTML.
````
.box {

}
````
La peculariedad de los selectores **class** es que están pensados para que estilizar, de forma similar, partes que se repiten dentro de nuestro documento HTML. Es decir, su función es ser reutilizables.