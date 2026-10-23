# Laboratorio 10 - VPC

Curso: Desarrollo de Soluciones en la Nube
Docente: Jaime Farfán

## Parte 01: Creación de VPC
- Región: América del Sur (São Paulo) sa-east-1
- Nombre: LAB10-solanch-vpc
- Bloque CIDR de la VPC: 192.168.0.0/22 (1024 IPs)
- Zonas de disponibilidad: 1
- Subred pública: 192.168.0.0/24
- Subred privada: 192.168.2.0/24
- Gateway NAT: Ninguna
- Punto de enlace: Gateway de S3

## Parte 02: Revisando la configuración de la VPC
### Entregable 02: Subredes
- Subred pública: 192.168.0.0/24 → 251 IPs utilizables
- Subred privada: 192.168.2.0/24 → 251 IPs utilizables
- AWS reserva 5 IPs por subred (.0, .1, .2, .3 y .255)

## Reto: Implementación de una VPC en AWS

## Conclusiones