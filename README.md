# IO-Doctor · Membresías

Lista firmada de membresías de **IO-Doctor**, la app de soporte de IO Consulting. Los equipos la consultan
cada 6 horas para saber si su membresía está activa.

- `licencias.firmado.json`: la lista, firmada con la clave privada de IO Consulting (RSA 3072 + SHA-256).
  Los equipos verifican la firma con la clave pública que viaja en IO-Doctor: si alguien modifica o falsifica
  este archivo, la firma no coincide y se ignora.
- Es pública a propósito: así ningún equipo necesita un token para validar.

No se edita a mano: se genera con `node licencias/licencias.mjs firmar` en el repo de IO-Doctor, que copia el
archivo acá. Después, commit y push.

Contacto: contacto@ioconsulting.com.ar
