# Panaderia

Bosquejo del Modelo para una panaderia, para la base de datos. Se ha tomado en cuenta que la panaderia, no solo venden pan, tambien tienen charcuteria, ventan de quesos.jamon, etc.. Importante, he visto el software PANEX para guiarme. Luego vi otros programas y agregue otras cosas.

### Nombre

Nombre del pan, español, frances, ingles, camaleon, azucarado...

### Precio

precio del pan por unidad

### Fecha

para la factura es importante la fecha y la hora.

### Coste Indirecto

Este es el coste que no se puede reflejar directamente en el producto, como la electricidad, el agua, el alquiler del local...

### Peso por unidad

Estoes para mas que todo la charcuteria. En panaderia tambien se usa para la receta.. Este peso se refiere al peso unitario, es decir si se trata de pan, peso de un solo pan.

### Tipo

Hablando de Panaderia, por ahora se me ocurren dos tipos. Pan a <b> Granel </b>  y Pan <b> envasado </b>. Por ejemplo el envasado, puede ser el pan en rebanadas que viene en bolsa, el pan de banquete que tambien viene en bolsa.

### Masa

Bueno, si esperamos hacer muchos tipos de panes, tener recetas en el software, debemos tener este campo. Este campo sera como un vector que se ira llenado por el admin. Por ejemplo agregara masa del biscocho, masa del pan frances, masa del paneton.

### Categoria

Dentro de la panaderia encontramos productos de panaderia, de pasteleria como tortas.. Nose aun si charcuteria hace parte de las categorias.

### Peso Total o pesada

Aqui se refiere al peso de la masa. Por ejemplo cuando la formula ya este guardada en el sistema, el sistema podra indicar cuantos panes salen solo colocando el peso total de la masa.


### Producto o ingrediente

Esto debe ser un vector, este corresponde a un solo producto, dentro del vector deberia ir 
<b> Nombre </b> , <b> Precio </b> , <b> Existencia </b> , <b> peso </b> 

### Costo por unidad

### Costo de la receta

### Precio sugerido de venta

### Impuesto

### Formula o Receta

### Merma

### Precio de Venta

se llena manualmente, el administrador debe colocar el precio.

</br>

Es un objecto, que tiene varios campos, esto para el caso donde agreguemos un modulo para las formula del pan, es decir la receta.
En el objecto deberias ir los  siguientes campos

</br>

<b> Nombre </b> 
</br>
<b> Tipo </b> 
</br>
<b> Categoria </b> 
</br>
<b> Masa </b> 
</br>
<b> Peso Total </b> 
</br>
<b> Unidades del peso total </b> 
</br>
<b> kilogramos por lote </b> 
</br>
<b> Peso por unidad (en gramos) </b> 
</br>
<b> Costo de formula </b> 
</br>
<b> Costo Indirecto </b> 
</br>
<b> Precio sugerido por venta </b> 
</br>
<b> merma </b> 
</br>



<font color="red">este texto se pone rojo</font>
