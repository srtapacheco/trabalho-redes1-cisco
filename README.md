# Segundo trabalho da matéria de Redes de computadores 1
Este repositório contém o projeto prático para a disciplina de Redes 1. Na realização deste trabalho, os participantes serão desafiados a configurar dispositivos em uma rede mista IPv4/IPv6. As principais tarefas incluem a configuração de roteadores, atribuição de endereços IPv4 e IPv6 a hosts em três LANs distintas, bem como a ativação do gerenciamento remoto via Telnet nos switches.

## Tarefas a serem Realizadas
1. Projeto e Cálculo de Endereçamento IPv4
2. Configuração de Interfaces em Roteadores, Switches e PCs, com suporte para IPv4 e IPv6 quando necessário
3. Configuração da Interface de Gerenciamento nos Switches

## Requisitos por Dispositivo

### Roteador
Configuração de interfaces e endereços IPv4 e IPv6
Definição de rotas estáticas para as redes IPv4

### Switch
Ativação do gerenciamento remoto básico via Telnet

### Hosts (PCs e Servidor)
Atribuição de endereços IPv4 completos
Atribuição de endereços IPv6

## Configuração de Rede
### Rede IPv4

Atribuição das redes IPv4 para dispositivos finais:

Rede 1: 192.168.1.0/24

Rede 2: 192.168.2.0/24

Rede 3: 192.168.3.0/24

Subdivisão da rede 200.20.0.0/24 entre roteadores para minimizar o uso de endereços

Implementação de roteamento estático IPv4

### Rede IPv6

Configuração das Redes 2 e 3 com IPv6:

Roteador 2:

Interface da Rede 2: 2001:DB8:ACAD:A::1/64

Interface da Rede 3: 2001:DB8:ACAD:B::1/64

PCs nas Redes 2 e 3:

PC1 - Rede 2: 2001:DB8:ACAD:A::FF

PC2 - Rede 2: 2001:DB8:ACAD:A::15

PC1 - Rede 3: 2001:DB8:ACAD:B::FF

PC2 - Rede 3: 2001:DB8:ACAD:B::15

Switch sem gerenciamento via IPv6
