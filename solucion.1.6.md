### 1.6 logs + utilidade rndc + nsupdate

# 1. Fai que no equipo darthvader se faga un log de todas as consultas (/var/log/bind/queries.log) e de todas as actualizacions (/var/log/bind/update.log) a dous ficheiros de log diferentes. Captura a configuración. Amosa as capturas dos dous ficheiros de log, despois de facer consultas e actualizacións e transferencias de zona.
![imagen2](./imaxes1.6/Captura2.png)

![imagen3](./imaxes1.6/Captura3.png)

![imagen1](./imaxes1.6/Captura1.png)

# 2. Investiga como co comando "dig" podes pedir unha copia dunha zona.
Con el comando dig starwars.lan axfr
![imagen4](./imaxes1.6/Captura4.png)

# 3. Permite que o equipo darthvader poida ser controlado coa utilidade rndc desde un cliente ubuntu ou debian. Fai unha captura do servidor reiniciandose.
![imagen5](./imaxes1.6/Captura5.png)

# 4. Instala unha zona dinámica no servidor darthvader chamada galaxia.lan e introduce os rexistros aaylasecura (192.168.20.239) e yarua (192.168.20.238). Esta zona debe ser cargada mediante rndc, e o servidor reiniciado con rndc. Proba tamén a eliminala con rndc. Inclue capturas do resultado dos comandos, comprobando tamén que se poden facer consultas.

![imagen6](./imaxes1.6/Captura6.png)

![imagen7](./imaxes1.6/Captura7.png)

![imagen8](./imaxes1.6/Captura8.png)

![imagen9](./imaxes1.6/Captura9.png)

![imagen10](./imaxes1.6/Captura10.png)

# 5. Mediante a utilidade nsupdate, engade un rexistro chamado darthmaul (192.168.20.144) á zona starwars.lan empregando chaves.

![imagen12](./imaxes1.6/Captura12.png)

![imagen11](./imaxes1.6/Captura11.png)

