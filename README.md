# TINY SIGFOX

## TINY SIGFOX IMAGEN

![](https://github.com/TECA-IOT/Tiny-sigfox/blob/master/imagenes/TinySigfox.png)


## Caracteristicas

- Diseño simple y robusto para aplicaciones de bajo consumo de energia. 
- Incorpora el chip WISSOL WSSFM11R2DAT a bordo para conexiones a red Sigfox para regione RC4.
- Incorpora una antena Helicoidal y conector tipo UF-L para colocar antenas externas.
- Ideal para aplicaciones con microcontroladores externos, Pic, Arduino, Arm, Raspberry Pi etc. Comunicacionvia  puerto Serial RX,TX a 9600 baudios y niveles de tension de 3.3V.
- Voltaje de Funcionamiento interno de 3.3V.
- Puede ser alimentado directamente con 2 Baterias Alcalinas, o baterias de litio 1S.

## Caracteristicas Electricas

| Descripcion| Unidad                    |
| ------------- | ------------------------------ |
| Voltaje de Funcionamiento  |  3.3 Voltios    |  
| Voltaje  Maximo de Entrada  |  3.6 Voltios    | 
| Voltaje minimo de Entrada   | 2.7 Voltios     |
| Consumo corriente TX | 170mA      |
| Consumo corriente RX   | 32mA     |
|  RX   | 32mA     |
| Consumo en modo Deep Sleep   | 2.5uA     |

## Descripcion de pines

| Pin| Descripcion                    |
| ------------- | ------------------------------ |
| G |  GND    |  
| Rx  |  Rx WSSFM11R4AT    | 
| Tx   |  Tx WSSFM11R4AT     |
| Rst   | Reset WSSFM11R4AT    |
| +3V   | VIN, Voltaje de entrada [2.7 - 3.6]Voltios    |
| G   | GND     |



# Probando módulo TINY  SIGFOX

- Necesitara tener un modulo USB a SERIAL como FTDI, CH340, CP201x, etc. Conecte los pines de manera adecuada a TINY DEVKIT SIGFOX (Rx con Tx y veceverza).
- Conecte su modulo USB a SERIAL a su PC, espere a que sea reconocido el driver.
- Use la aplicacion "SFM10R_AT_TEST_v14" .
`<link>` : <https://github.com/markoAntonio1692/TINY-DEVKIT-SIGFOX/tree/master/Software>
- Abra el executable.
- Ingrese el numero del puerto COM que fue detectado en su PC.
- Clic en "Connect".
- Ingrese el comando AT y click en "Send", su modulo habra respondio con "OK" .
- Para mas informacion y comando disponibles consulte esta documentacion:
`<link>` : <https://github.com/markoAntonio1692/TINY-DEVKIT-SIGFOX/blob/master/Manual/DS_WSSFM11R2DAT_REV05_180702.pdf>


![](https://github.com/markoAntonio1692/TINY-DEVKIT-SIGFOX/blob/master/imagenes/test.JPG)
