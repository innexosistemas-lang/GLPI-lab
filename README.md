# glpi-lab

> Service desk com GLPI: abertura e triagem de chamados, SLA, inventário de ativos e base de conhecimento técnico. Projeto orientado pelo [Prof. Me. Isaías de Queiroz Ramos](https://www.linkedin.com/in/isa%C3%ADas-de-queiroz-ramos-a792a539/?isSelfProfile=false), professor e coordenador de cursos na Escola Politécnica da PUC-Campinas.

![Status](https://img.shields.io/badge/status-em%20constru%C3%A7%C3%A3o-yellow?style=flat-square) ![Foco](https://img.shields.io/badge/foco-Suporte%20N1%2FN2-0d1117?style=flat-square)

## Objetivo

Simular a rotina de um service desk: receber chamados, classificar, priorizar por SLA, resolver ou escalar, e documentar a solução.

## Ambiente

| Componente | Função |
|---|---|
| Ubuntu Server via maquina virtual | GLPI + Apache/PHP + MariaDB |
| GLPI Agent | Inventário automático das máquinas |
| Windows 11 / Linux (VMs) | Estações de usuários |

## Roteiro

- [ ] Instalar e configurar o GLPI
- [ ] Criar entidades, grupos, categorias e níveis (N1/N2)
- [ ] Definir SLA por prioridade
- [ ] Inventário com GLPI Agent
- [ ] Simular chamados reais (senha, impressora, rede, acesso)
- [ ] Escrever artigos na base de conhecimento

## Estrutura das Pastas

```
docs/        passo a passo e prints
chamados/    exemplos de chamados e resoluções
kb/          artigos da base de conhecimento
```

---
<sub>Laboratório em ambiente próprio e isolado.</sub>
