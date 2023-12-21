<h1 align='center'>Trabalho 2 - Redes 2023.2</h1>

## Conteudos

- [Dependências](#dependencias)
- [Configurações Utilizadas](#configs)
- [Topologia da Rede](#topologia)
- [Integrantes](#integrantes)

## Dependências <a name='dependencias'></a>

Para poder visualizar de forma completa o trabalho é necessário:

- Cisco Packet Tracer - V8.2.1.0118 (https://skillsforall.com/resources/lab-downloads?courseLang=en-US)

## Configurações Utilizadas <a name='configs'></a>

- IPv4: A aplicação dos endereços foi feita de forma que temos: 192.168.1.0/24 (rede 1), 192.168.2.0/24 (rede 2) e 192.168.3.0/24 (rede 3), dentro disso destacamos o endereçamento 192.168.x.10 (pc 1) e 192.168.x.20 (pc 2) para as máquinas de cada sub-rede, o endereçamento 192.168.x.1 referente as Vlan's e o endereçamento 192.168.x.254 para as saídas de cada switch em uma respectiva sub-rede.

- IPv6: A implementação das redes 2 e 3 com IPv6, excluindo a Rede 1, os endereços atribuídos são os seguintes: 2001:DB8:ACAD:A::1/64 (rede 2) e 2001:DB8:ACAD:B::1/64 (rede 3)

- Link entre roteadores: Para o link entre roteadores foi implementada a divisão do endereço 200.20.0.0/24 em 200.20.0.0/30 de forma a não desperdiçar endereços IP, visto que este endereçamento foi utilizado apenas por dois roteadores presentes na rede.

- Telnet: A habilitação do gerenciamento remoto básico via Telnet exclusivamente para IPv4 foi estabelecida. Essa configuração permitiu o acesso remoto aos dispositivos utilizando o protocolo Telnet, porém restrito ao ambiente IPv4. Essa abordagem proporcionou uma maneira de gerenciar os dispositivos de forma remota, porém limitada.

## Topologia da Rede <a name='topologia'></a>

A topologia da rede se apresenta da seguinte forma:

![topologia!](./topologia.png)

## Integrantes <a name='integrantes'></a>

- Alice Pereira Ferreira Pinto

- Gustavo Oliveira Pessanha da Silva
