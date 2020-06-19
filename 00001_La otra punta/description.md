En la mayoría de los ejercicios que hiciste en este recorrido el cabezal comenzaba en la esquina inferior izquierda. Este no va a ser la excepción :stuck_out_tongue_winking_eye:. Lo que queremos hacer es llevar el cabezal al casillero de arriba a la derecha:

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
        size 3 3
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 3 3
        head 2 2
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

> Escribí un programa que lleve el cabezal del casillero `0 0` (abajo a la izquierda) al casillero `2 2` (arriba a la derecha).