# TE06 - Introducción a las redes de computadoras I
#info_basica 

---

---

## Índice:

1. Conexión de dos equipos
2. Conexión de N equipos
3. Conexión de dos equipos

---

## Conexión de dos equipos:

- Cable cruzado
- Gracias a los OS

Si usamos un cable normal en vez de número cruzado, la tarjeta de red se dará cuenta y lo cruzará automáticamente. 

- Cada tarjeta de red tiene un identificador único
- Dirección MAC

**La dirección MAC**, es un identificador de 48 bits que corresponde de forma única a una tarjeta o dispositivo de red. Se conoce como dirección física, es única para cada dispositivo. Se configura por el IEEE (primeros 24 bits) y el fabricante (últimos 24 bits) usando el organizationally unique identifier. 

### Vídeo de clase

- NIC: Tarjeta de interfaz de red
- Imposible encontrar dos MAC idénticas.
- 12 dígitos hexadecimales / 4 bits cada dígito
- IEEE: Asigna las direcciones MC para llevar un control estricto.
    - Asigna los números MAC para el dispositivo que queremos hacer

Para que se puedan comunicar hace falta asignar una IP a cada dispositivo

## Conexión de dos equipos:

Software:

- SO
- API de comunicación
- Programa

## Conexión de N equipos:

Necesario: un hub / concentrador

Los ordenadores se conectan al hub con un cable normal (*no cruzado*) 

![Untitled](Info_Basica/TE06%20-%20Introducción%20a%20las%20redes%20de%20computadoras/Untitled.png)

¿Cómo sabe un equipo que es para él?

- Un equipo no conoce las MAC de los otros.
- ¿Cómo sabe un equipo las direcciones MAC de los otros equipos?

Creación de una red local

- Cada dispositivo tiene una IP y MAC únicas.
- La MAC la determina el fabricante y es única.
- La IP se determina el administrador de la red y única dentro de su red.
- Pueden existir varios dispositivos con la misma IP.

Tipos de red:

- Tipo A: 3.—.—
- Tipo B: 150.30.—.—
- Tipo C: 192.168.3—.—

### Crear red local

Hay que configurar la dirección IP y la máscara de subred:

| PC | IP | Máscara |
| --- | --- | --- |
| 1 | 192.168.1.1 | 255.255.255.0 |
| 2 | 192.168.1.2 | 255.255.255.0 |
| 3 | 192.168.1.3 | 255.255.255.0 |
| 4 | 192.168.1.4 | 255.255.255.0 |

P**rotocolo ARP**

- Cada dispositivo tiene la tabla ARP con los pares IP - MAC
- Cuando se quiere enviar un dato a una IP, se mira la tabla ARP si tiene la MAC.
- Si se tienen se añade la MAC al paquete de datos.
- Si no se tiene, se envía un paquete a todos los dispositivos.
- El dispositivo IP responde con la MAC.
- Se añade la correspondencia a la tabla ARP y ya se puede enviar el paquete.