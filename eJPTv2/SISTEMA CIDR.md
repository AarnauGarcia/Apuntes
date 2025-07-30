Ejemplos de rangos CIDR y redes intermedias
# /0 a /7 REDES EXCESIVAMENTE GRANDES PREVIAS A LA CLASE A

## CIDR /0
Direcciones posibles: 4.294.967.296
Máscara de subred: 0.0.0.0
Descripción: Todo el espacio IPv4. Se usa como ruta por defecto (0.0.0.0/0).
## CIDR /1
Direcciones posibles: 2.147.483.648
Máscara de subred: 128.0.0.0
Descripción: Mitad del espacio IPv4. Uso extremadamente raro.
## CIDR /2
Direcciones posibles: 1.073.741.824
Máscara de subred: 192.0.0.0
Descripción: Cuarto del espacio IPv4. Reservado para grandes bloques.
## CIDR /3
Direcciones posibles: 536.870.912
Máscara de subred: 224.0.0.0
Descripción: Octavo del espacio IPv4. No se usa en redes privadas.
## CIDR /4
Direcciones posibles: 268.435.456
Máscara de subred: 240.0.0.0
Descripción: Bloques enormes. Uso reservado.
## CIDR /5
Direcciones posibles: 134.217.728
Máscara de subred: 248.0.0.0
Descripción: Uso muy poco común.
## CIDR /6
Direcciones posibles: 67.108.864
Máscara de subred: 252.0.0.0
Descripción: Bloques grandes. No se usa en redes privadas.
## CIDR /7
Direcciones posibles: 33.554.432
Máscara de subred: 254.0.0.0
Descripción: Uso reservado para ISPs o grandes organizaciones.
# CIDR /8 (CLASE A)
Direcciones posibles: 16.777.216
Máscara de subred: 255.0.0.0
Clase: A
Descripción: Grandes redes. Ejemplo: 10.0.0.0/8 (privada).
/9 a /15 (REDES INTERMEDIAS ENTRE CLASE A Y CLASE B)
## CIDR /9
Direcciones posibles: 8.388.608
Máscara de subred: 255.128.0.0
Descripción: Mitad de una red clase A.
## CIDR /10
Direcciones posibles: 4.194.304
Máscara de subred: 255.192.0.0
Descripción: Subredes grandes.
## CIDR /11
Direcciones posibles: 2.097.152
Máscara de subred: 255.224.0.0
Descripción: Subredes de clase A.
## CIDR /12
Direcciones posibles: 1.048.576
Máscara de subred: 255.240.0.0
Descripción: Ejemplo: 172.16.0.0/12 (privada).
## CIDR /13
Direcciones posibles: 524.288
Máscara de subred: 255.248.0.0
Descripción: Subredes medianas.
## CIDR /14
Direcciones posibles: 262.144
Máscara de subred: 255.252.0.0
Descripción: Subredes medianas.
## CIDR /15
Direcciones posibles: 131.072
Máscara de subred: 255.254.0.0
Descripción: Subredes medianas.
# CIDR /16 (CLASE B)
Direcciones posibles: 65.536
Máscara de subred: 255.255.0.0
Clase: B
Descripción: Redes medianas. Ejemplo: 172.16.0.0/16.

# /17 a /23 (REDES INTERMEDIAS ENTRE CLASE B Y CLASE C)
## CIDR /17
Direcciones posibles: 32.768
Máscara de subred: 255.255.128.0
Descripción: Mitad de una red /16.
## CIDR /18
Direcciones posibles: 16.384
Máscara de subred: 255.255.192.0
Descripción: Subredes más pequeñas.
## CIDR /19
Direcciones posibles: 8.192
Máscara de subred: 255.255.224.0
Descripción: Subredes pequeñas.
## CIDR /20
Direcciones posibles: 4.096
Máscara de subred: 255.255.240.0
Descripción: Subredes pequeñas.
## CIDR /21
Direcciones posibles: 2.048
Máscara de subred: 255.255.248.0
Descripción: Subredes pequeñas.
## CIDR /22
Direcciones posibles: 1.024
Máscara de subred: 255.255.252.0
Descripción: Subredes pequeñas.
## CIDR /23
Direcciones posibles: 512
Máscara de subred: 255.255.254.0
Descripción: Subredes pequeñas.
# CIDR /24 (CLASE C)
Direcciones posibles: 256
Máscara de subred: 255.255.255.0
Clase: C
Descripción: Muy común en LANs. Ejemplo: 192.168.1.0/24.

# /25 a /30 (REDES INTERMEDIAS ENTRE CLASE C Y REDES AUN MAS PEQUEÑAS)
## CIDR /25
Direcciones posibles: 128
Máscara de subred: 255.255.255.128
Descripción: Divide una /24 en dos. 126 hosts utilizables.
## CIDR /26
Direcciones posibles: 64
Máscara de subred: 255.255.255.192
Descripción: 62 hosts utilizables.
## CIDR /27
Direcciones posibles: 32
Máscara de subred: 255.255.255.224
Descripción: 30 hosts utilizables.
## CIDR /28
Direcciones posibles: 16
Máscara de subred: 255.255.255.240
Descripción: 14 hosts utilizables.
## CIDR /29
Direcciones posibles: 8
Máscara de subred: 255.255.255.248
Descripción: 6 hosts utilizables.
## CIDR /30
Direcciones posibles: 4
Máscara de subred: 255.255.255.252
Descripción: 2 hosts utilizables. Enlaces punto a punto.
## CIDR /31
Direcciones posibles: 2
Máscara de subred: 255.255.255.254
Descripción: Ambos IPs utilizables. Enlaces modernos (RFC 3021).
## CIDR /32
Direcciones posibles: 1
Máscara de subred: 255.255.255.255
Descripción: Una única IP. Usado para identificar un host.