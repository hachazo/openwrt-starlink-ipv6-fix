# Starlink OpenWrt IPv6 NAT66 Fix

Scripts de configuración de IPv6 para antenas Starlink operando en modo *Bypass* con routers OpenWrt.

## 📝 Descripción
Este repositorio contiene scripts y archivos de configuración utilizados para solucionar el problema de las interrupciones de Internet y las desconexiones frecuentes (que ocurren mayormente en  los teléfonos Android) al usar una conexión Starlink con un router OpenWrt.

La solución implementa **NAT66**, lo que significa que los dispositivos de la red local no recibirán una dirección IPv6 pública/global.
Estos script fueron probados en diferentes versiones de openwrt con diferentes antennas de Starlink (no probe con la ultima antena de Starlink) y funciona sin ningun problema, no recibi ninguna queja hasta ahora.
Cualquier mejora o cambio que se pueda realizar en los scrips se agradece.
