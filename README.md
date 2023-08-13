# SFM10R4 | SFM10R2D
# Manual SFM10R4
- `<link>` : <https://github.com/TECA-IOT/WisolModemDev/blob/master/DS_WSSFM10R4AT_REV07_20190901%20(3).pdf>

# Probando módulo SFM10R4 

- Necesitara tener un modulo USB a SERIAL como FTDI, CH340, CP201x, etc. Conecte los pines de manera adecuada a TINY DEVKIT SIGFOX (Rx con Tx y veceverza).
- Conecte su modulo USB a SERIAL a su PC, espere a que sea reconocido el driver.
- Use la aplicacion "SFM10R_AT_TEST_v14" .
`<link>` : <https://github.com/TECA-IOT/Tiny-sigfox/tree/master/WSSFM_TEST_AT>
- Abra el executable.
- Ingrese el numero del puerto COM que fue detectado en su PC.
- Clic en "Connect".
- Ingrese el comando AT y click en "Send", su modulo habra respondio con "OK" .
- Para mas informacion y comando disponibles consulte esta documentacion:
`<link>` : <https://github.com/markoAntonio1692/TINY-DEVKIT-SIGFOX/blob/master/Manual/DS_WSSFM11R2DAT_REV05_180702.pdf>


![](https://github.com/markoAntonio1692/TINY-DEVKIT-SIGFOX/blob/master/imagenes/test.JPG)


# CAMBIANDO DE REGION DE OPERACION MODULOS SF10R2D
![](https://github.com/TECA-IOT/WisolModemDev/blob/master/imagenes/187875906_338800030911268_5456874291727247399_n.png)

# DE RC2 A RC4
- AT$DR=922300000
- ATS400=<000001FF><F0000000><00000000>,63
- AT$WR
- AT$RC

# DE RC4 a RC2
- AT$DR=905200000
- ATS400=<000001FF><00000000><00000000>,1
- AT$WR
- AT$RC
