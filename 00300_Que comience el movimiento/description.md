Hasta ahora lo que vimos no fue muy emocionante, porque no te enseñamos cómo darle instrucciones a la máquina y sólo te mostramos un tablero :disappointed:. En este ejercicio vamos a aprender una de las órdenes que podemos darle a la máquina: mover el cabezal.

Por ejemplo, partiendo de un tablero **inicial** vacío con el cabezal en el origen (abajo a la izquierda), podemos fácilmente crear un programa que mueva el cabezal una posición hacia el **norte**:

<table class= "table table-borderless" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 3 3
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 3 3
        head 0 1
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

El **código** del programa (es decir, el **texto** de la descripción de la solución que le daremos a la computadora) que logra esto es el siguiente:

```gobstones
program {
  Mover(Norte)
}
```

> ¿No nos creés? Escribí el código anterior en el editor y dale Enviar.