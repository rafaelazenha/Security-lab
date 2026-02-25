# Visão Geral

Este projeto consiste na criação de um laboratório de segurança, onde aplicarei meus conhecimentos em redes. A infraestrutura incluirá a implementação de máquinas de servidor, cliente e firewall, todas configuradas para demonstrar o funcionamento e a segurança de uma rede. O objetivo é explorar e evidenciar práticas de segurança, além de entender melhor a interação entre os diferentes componentes dentro de um ambiente de rede protegido.

## Posicionamento das Máquinas

Para melhor entendimento de como será a estrutura do laboratório, a configuração das máquinas estará organizada da seguinte forma:

### Máquina do Cliente:
O cliente será uma máquina rodando uma distribuição Linux, servindo como um ambiente para demonstrações de práticas de segurança.
Embora a máquina cliente tenha uma configuração inicial em Linux, ela poderá ser substituída ou complementada por uma máquina Windows, oferecendo flexibilidade para testes e experiências variadas.

### Firewall:
O firewall utilizado será pfSense, rodando em uma máquina com sistema operacional FreeBSD.
A máquina do firewall atuará como um ponto de controle entre o cliente e o servidor, filtrando o tráfego e garantindo a segurança da comunicação.
A configuração permitirá a implementação de regras específicas para controlar o acesso à rede e monitorar as interações entre as máquinas.

### Servidor:
O servidor será uma máquina com a distribuição Debian, equipada com serviços web para demonstrar a configuração e a segurança adequada de um ambiente de servidor.
Ele estará conectado diretamente ao firewall, permitindo a passagem controlada de dados entre o cliente e os serviços oferecidos.
