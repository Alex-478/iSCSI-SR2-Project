# iSCSI Lab Report

Este repositório contém um relatório de laboratório sobre o protocolo iSCSI (Internet Small Computer System Interface), explorando a sua implementação, arquitetura e análise prática.

## Conteúdo

- **Introdução:** Visão geral do iSCSI e sua relevância no armazenamento em rede.
- **Arquitetura iSCSI:** Explicação dos componentes do iSCSI, incluindo initiators e targets.
- **Implementação:** Detalhes da configuração do iSCSI num ambiente de laboratório.
- **Análise Prática:** Resultados da análise do tráfego iSCSI usando o Wireshark.

## Configuração do Laboratório

O ambiente de laboratório foi configurado usando máquinas virtuais VMware ESXi, com o Windows Server 2022 a servir como target iSCSI. O initiator iSCSI foi configurado em outra máquina virtual Windows Server 2022 e também testado em máquinas pessoais com Windows 10.

## Análise do Wireshark

As capturas do Wireshark revelaram o processo de login do iSCSI, operações de leitura e escrita e o mecanismo NOP-IN e NOP-OUT usado para manter as ligações ativas.

## Conclusão

O laboratório forneceu informações valiosas sobre o funcionamento do protocolo iSCSI, desde a sua configuração até à análise prática do seu tráfego. Apesar dos desafios iniciais, o projeto foi concluído com sucesso, aprimorando a nossa compreensão do iSCSI e das técnicas de análise de rede.
