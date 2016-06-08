Instale el paquete que se encuentra en la pestaña de "Releases".

# oas-ci-agent

Agente de CI de la OAS.

Los agentes requieren un nombre (FQDN) que sea posible resolver y que sea igual que su `hostname -f`.

## Puertos

 - Para comunicación (encriptada con TLS) entre Swarm Manage y Docker (servicio systemd docker) TCP/2376

## Seguridad

 - Las reglas exactas para hacer funcionar con `selinux enforcing` se desconocen, si planea habilitar `selinux enforcing` realice un audit antes de hacerlo para otorgar los permisos que las aplicaciones necesitan.
