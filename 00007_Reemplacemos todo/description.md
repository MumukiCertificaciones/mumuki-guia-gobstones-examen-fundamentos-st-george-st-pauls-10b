Ahora que tenemos nuestro procedimiento `ReemplazarMejorado` ¡vamos a usarlo!

Queremos cambiar toda una hilera:

<table class= "table" style="width:100%">
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
        size 4 1
        cell 0 0 Verde 1
        cell 1 0 Verde 1
        cell 2 0 Verde 1
        cell 3 0 Verde 1
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 4 1
        cell 0 0 Azul 1
        cell 1 0 Azul 1
        cell 2 0 Azul 1
        cell 3 0 Azul 1
        head 3 0
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

> Escribí un programa que utilizando `repeat` y `ReemplazarMejorado` reemplace las bolitas verdes por azules.