# roadmap-cyber
Roadmap de estudos em cibersegurança, SOC e infraestrutura segura — 58 semanas.
# Trilha de Cibersegurança em Português: do Zero a SOC e Infraestrutura

Roadmap de estudos de 58 semanas com foco em fundamentos de cibersegurança, redes, Linux, Windows, automação, SOC, Blue Team e infraestrutura segura.

O objetivo deste repositório é documentar minha evolução técnica por meio de estudos, anotações, laboratórios práticos, scripts, projetos e certificações.

## Sobre o projeto

- **Duração:** 58 semanas
- **Carga horária:** aproximadamente 9h30 por semana
- **Total estimado:** 551 horas de estudo e prática
- **Idioma principal:** português
- **Inglês complementar:** 15 minutos por dia, fora da carga horária principal
- **Método de organização:** GitHub Desktop, Git, branches e pull requests
- **Ambiente de laboratório:** VirtualBox, Linux, Windows, Packet Tracer e ferramentas de segurança
- **Objetivo profissional:** desenvolver conhecimentos para oportunidades em SOC, Blue Team, segurança de redes e infraestrutura segura.

Este roadmap prioriza cursos em português, materiais gratuitos e exercícios práticos. Quando o conteúdo estiver disponível apenas em inglês, utilizarei legendas traduzidas ou o tradutor do navegador.

## Programação semanal

| Dia | Tempo | Atividade |
|---|---|---|
| Segunda-feira | 1h15 | Curso ou leitura e exercícios |
| Terça-feira | 1h15 | Continuação do conteúdo e anotações |
| Quarta-feira | 1h15 | Estudo teórico e exercícios |
| Quinta-feira | 1h15 | Continuação do conteúdo e revisão |
| Sexta-feira | 1h15 | Revisão e questões |
| Sábado | 2h15 | Laboratório prático ou projeto |
| Domingo | 1h | Documentação, publicação no GitHub e planejamento |
| Inglês | 15 min/dia | Estudo complementar fora das 9h30 semanais |

Durante os dias úteis, a proposta é dedicar aproximadamente 50 minutos ao curso ou à leitura e 25 minutos a exercícios e anotações.

O sábado será destinado principalmente à prática. No domingo, vou registrar o que aprendi, organizar os arquivos e publicar as atualizações pelo GitHub Desktop.

### Regras para manter a consistência

- Se eu perder um dia, não tentarei compensar toda a carga horária de uma vez.
- Se perder a semana inteira, repetirei a etapa antes de avançar.
- Cada semana terá um objetivo claro e um critério de conclusão.
- O progresso será registrado conforme as atividades forem realmente concluídas.
- Certificados e projetos serão adicionados ao repositório à medida que forem obtidos.

## Visão geral do roadmap

O plano está dividido em 10 fases, começando pelo Git e pelos fundamentos da computação e avançando para análise de logs, segurança, SOC e infraestrutura.

| Fase | Semanas | Conteúdo principal | Entrega prevista |
|---|---|---|---|
| 0 | 1–2 | Git, GitHub e GitHub Desktop | Repositório e perfil organizados |
| 1 | 3–8 | Computação, internet e introdução à segurança | Anotações, glossário e certificados |
| 2 | 9–14 | Linux, terminal, permissões e Bash | Cheatsheet e script de análise de falhas SSH |
| 3 | 15–20 | Redes, switching, roteamento e fundamentos CCNA | Laboratórios no Packet Tracer |
| 4 | 21–24 | Windows Server, Active Directory e PowerShell | Laboratório de AD e script de auditoria |
| 5 | 25–28 | Python, SQL e automação de logs | Parser de logs e consultas SQL |
| 6 | 29–36 | Fundamentos de segurança e preparação para Security+ | Laboratórios de segurança e preparação para a prova |
| 7 | 37–48 | SOC, SIEM e Blue Team | Homelab SOC e projeto de investigação |
| 8 | 49–54 | Infraestrutura segura e cloud | Estudos de Fortinet e Microsoft Azure |
| 9 | 55–58 | Preparação para o mercado de trabalho | Currículo, portfólio e preparação para entrevistas |

## Fase 0 — Git e GitHub (semanas 1–2)

**Objetivo:** aprender a organizar e publicar projetos utilizando o GitHub Desktop, sem utilizar o terminal para operações Git.

Conteúdos:
- Git e GitHub.
- Repositórios, commits e branches.
- Markdown.
- Histórico de alterações.
- Pull requests e merge.
- Resolução de conflitos.
- Organização do perfil GitHub.

Entregas:
- Repositório `roadmap-cyber`.
- Repositório de treino `git-treino`.
- README do perfil.
- Primeiro pull request e primeiro merge.

## Fase 1 — Fundamentos de computação e internet (semanas 3–8)

**Objetivo:** compreender como computadores, sistemas operacionais e redes funcionam antes de avançar para os conceitos de segurança.

Conteúdos:
- Hardware e arquitetura de computadores.
- Sistemas binário, decimal e hexadecimal.
- Memória, processador e armazenamento.
- Sistemas operacionais.
- Internet, DNS, HTTP, HTTPS, TCP e endereçamento IP.
- Fundamentos de cibersegurança.
- Ameaças, vulnerabilidades, riscos e criptografia.

Entregas:
- Anotações sobre o funcionamento de um computador.
- Resumo sobre internet e protocolos.
- Glossário de cibersegurança.
- Primeiros certificados de cursos.

## Fase 2 — Linux do zero (semanas 9–14)

**Objetivo:** aprender a utilizar o terminal Linux e automatizar tarefas básicas de análise de logs.

Conteúdos:
- Estrutura de diretórios Linux.
- Manipulação de arquivos.
- Usuários, grupos e permissões.
- Processos, serviços e pacotes.
- Logs do sistema.
- SSH e análise de falhas de autenticação.
- Bash scripting.
- Comandos como `grep`, `awk`, `sed`, `chmod`, `chown` e `systemctl`.

Entregas:
- `linux-cheatsheet.md`.
- Laboratório de servidor web com Nginx.
- Análise de logs de autenticação.
- Script Bash para identificar IPs com falhas de login SSH.
- Anotações do OverTheWire Bandit, sem senhas ou soluções completas.

## Fase 3 — Redes com foco em CCNA (semanas 15–20)

**Objetivo:** aprofundar os conhecimentos de redes e aprender a montar, configurar e diagnosticar uma infraestrutura de pequeno porte.

Conteúdos:
- Modelo OSI e TCP/IP.
- IPv4, IPv6 e subnetting.
- Ethernet e switching.
- VLANs e trunk.
- STP e EtherChannel.
- Roteamento estático e OSPF.
- DHCP, ACL, NAT e PAT.
- Redes sem fio e segurança de portas.
- Análise de tráfego com Wireshark.

Entregas:
- Laboratórios no Cisco Packet Tracer.
- Análise de handshake TCP e consultas DNS.
- Laboratório de VLANs e roteamento.
- Projeto de rede de pequena empresa.
- Tabela de endereçamento IP e documentação da topologia.

## Fase 4 — Windows, Active Directory e PowerShell (semanas 21–24)

**Objetivo:** aprender conceitos de administração Windows e identificar eventos relevantes para segurança.

Conteúdos:
- Windows Server.
- Active Directory Domain Services.
- Domínios, usuários, grupos e unidades organizacionais.
- Group Policy Objects (GPO).
- DNS e DHCP.
- Auditoria de eventos do Windows.
- PowerShell e automação.

Entregas:
- Laboratório de Active Directory.
- Documentação de usuários, grupos e GPOs.
- Catálogo de eventos de segurança do Windows.
- Script PowerShell para listar falhas de autenticação.

## Fase 5 — Python, SQL e automação (semanas 25–28)

**Objetivo:** desenvolver habilidades de programação para automatizar tarefas e analisar conjuntos de logs.

Conteúdos:
- Fundamentos de Python.
- Variáveis, condicionais, laços e funções.
- Arquivos, expressões regulares, CSV e JSON.
- Análise de logs SSH e Apache.
- Fundamentos de SQL.
- Consultas, filtros, agregações e JOIN.

Entregas:
- Repositório de exercícios Python.
- Parser de logs.
- Relatórios em texto ou CSV.
- Consultas SQL utilizando dados fictícios.
- Portfólio organizado com os principais projetos.

## Fase 6 — Fundamentos de segurança (semanas 29–36)

**Objetivo:** estudar os fundamentos necessários para atuar em segurança da informação e preparar-se para a certificação CompTIA Security+.

Conteúdos:
- Hash e criptografia.
- Certificados digitais, PKI e TLS.
- Autenticação, MFA e controle de acesso.
- Governança e frameworks de segurança.
- NIST Cybersecurity Framework e CIS Controls.
- Malware, engenharia social e vulnerabilidades.
- MITRE ATT&CK.
- Firewalls, VPN, IDS, IPS e segmentação de redes.
- LGPD, gestão de riscos e resposta a incidentes.
- Simulados e revisão dos domínios da Security+.

Entregas:
- Laboratório de criptografia.
- Checklist de controles de segurança.
- Mapeamento de técnicas MITRE ATT&CK.
- Laboratório pfSense e Suricata.
- Análise de risco de um cenário fictício.
- Preparação para a prova Security+ SY0-701.

## Fase 7 — SOC e Blue Team (semanas 37–48)

**Objetivo:** desenvolver conhecimentos voltados ao monitoramento, à investigação e à resposta a eventos de segurança.

Tópicos previstos na trilha:
- Monitoramento e investigação de logs.
- Fundamentos de SIEM.
- Correlação de eventos.
- Detecção de atividades suspeitas.
- Análise de alertas e investigação de incidentes.
- Ferramentas como Wazuh, Splunk e Elastic.
- Prática em plataformas de treinamento, como TryHackMe e LetsDefend.

Entrega planejada:
- Homelab SOC documentado.
- Coleta e análise de logs.
- Exemplos de detecções.
- Relatórios de investigação.
- Projeto final de monitoramento e resposta.

**Observação:** o PDF utilizado como referência apresenta o detalhamento semanal até a semana 36. Os tópicos desta fase foram resumidos a partir da visão geral do próprio documento e deverão ser detalhados antes da execução de cada semana.

## Fase 8 — Infraestrutura segura e cloud (semanas 49–54)

**Objetivo:** ampliar os conhecimentos de segurança de infraestrutura, redes corporativas e serviços em nuvem.

Trilha prevista:
- Fundamentos de segurança de infraestrutura.
- Conceitos e ferramentas de segurança Fortinet.
- Fundamentos de cloud computing.
- Serviços e conceitos básicos do Microsoft Azure.
- Identidade, acesso e segurança em ambientes Microsoft.
- Preparação para AZ-900 e SC-900.

Entregas planejadas:
- Anotações de infraestrutura segura.
- Laboratórios e diagramas.
- Resumos de serviços cloud.
- Preparação para certificações de fundamentos.

**Observação:** o detalhamento semanal dessa fase não consta nas páginas disponibilizadas do PDF.

## Fase 9 — Preparação para o mercado de trabalho (semanas 55–58)

**Objetivo:** organizar os conhecimentos adquiridos e preparar um portfólio para oportunidades profissionais.

Atividades previstas:
- Revisar e documentar projetos.
- Organizar o perfil GitHub.
- Atualizar currículo e LinkedIn.
- Registrar certificados e treinamentos.
- Treinar entrevistas técnicas.
- Pesquisar vagas de SOC, Blue Team e infraestrutura segura.
- Identificar lacunas técnicas e planejar os próximos estudos.

Entregas:
- Currículo atualizado.
- Perfil GitHub organizado.
- Projetos documentados.
- Lista de certificações e cursos concluídos.
- Plano de continuidade dos estudos.

**Observação:** o PDF disponibilizado apresenta a visão geral dessa fase, mas não o cronograma detalhado de cada semana.

## Certificações e cursos previstos

A trilha inclui certificados de cursos gratuitos, badges de plataformas e certificações profissionais com exame. Eles serão registrados separadamente para não confundir conclusão de curso com aprovação em uma prova oficial.

### Cursos com certificado ou badge

| Curso ou credencial | Instituição | Previsão |
|---|---|---|
| Get Connected | Cisco Networking Academy | Semana 6 |
| Introduction to Cybersecurity | Cisco Networking Academy | Semana 8 |
| Linux Unhatched | Cisco Networking Academy | Semana 10 |
| Cybersecurity Essentials | Cisco Networking Academy | Semana 29 |
| Python Essentials 1 | Cisco Networking Academy | Semana 28 |
| Introdução a Redes de Computadores | Fundação Bradesco | Semana 16 |
| CCNA Introdução às Redes | NIC.br / NetAcad | Semana 16 |
| CCNA Switching, Routing and Wireless Essentials | NIC.br / NetAcad | Semana 20 |
| Python Básico | Fundação Bradesco | Semana 25 |
| LGPD | Escola Virtual.Gov / ENAP | Semana 34 |
| Splunk Fundamentals 1 | Splunk Education | Semana 41 |
| TryHackMe SOC Level 1 | TryHackMe | Semana 46 |
| Fortinet FCF e FCA | Fortinet Training Institute | Semana 50 |

A emissão, a gratuidade e os requisitos de cada curso ou badge serão confirmados na plataforma oficial antes da inscrição. Alguns cursos podem mudar de nome, conteúdo ou disponibilidade.

### Certificações profissionais e exames

| Certificação | Previsão no plano | Situação |
|---|---|---|
| ISC2 Certified in Cybersecurity (CC) | Semanas 29–30 | Verificar se há oferta gratuita do exame |
| CompTIA Security+ SY0-701 | Semana 36 | Exame pago |
| Microsoft AZ-900 | Semana 51 | Exame pago |
| Microsoft SC-900 | Semana 52 | Exame pago |
| CCNA 200-301 | Pós-plano, semanas 59–66 | Exame pago |
| CompTIA CySA+ ou Microsoft SC-200 | Pós-plano, semana 67 em diante | Certificação futura a avaliar |

As certificações profissionais acima são objetivos de estudo, não conquistas já obtidas. A aprovação depende do cumprimento dos requisitos e, quando aplicável, da aprovação no exame oficial.

Antes de agendar uma prova, vou conferir o conteúdo vigente, o idioma disponível, o preço e os requisitos no site da instituição responsável.

### Controle de progresso das certificações

- [ ] Get Connected — Cisco NetAcad
- [ ] Introduction to Cybersecurity — Cisco NetAcad
- [ ] Linux Unhatched — Cisco NetAcad
- [ ] Python Essentials 1 — Cisco NetAcad
- [ ] Cybersecurity Essentials — Cisco NetAcad
- [ ] Introdução a Redes — Fundação Bradesco
- [ ] CCNA Introdução às Redes — NIC.br / NetAcad
- [ ] Switching, Routing and Wireless Essentials — NIC.br / NetAcad
- [ ] Python Básico — Fundação Bradesco
- [ ] LGPD — Escola Virtual.Gov / ENAP
- [ ] ISC2 Certified in Cybersecurity (CC), se disponível
- [ ] CompTIA Security+ SY0-701
- [ ] Splunk Fundamentals 1
- [ ] TryHackMe SOC Level 1
- [ ] Fortinet FCF / FCA
- [ ] Microsoft AZ-900
- [ ] Microsoft SC-900
- [ ] CCNA 200-301 — pós-plano

Os itens serão marcados como concluídos somente depois da conclusão real do curso, da emissão do certificado ou da aprovação no exame correspondente.

## Organização dos arquivos

Estrutura planejada para o repositório:

```text
roadmap-cyber/
├── README.md
├── progresso.md
├── certificacoes.md
├── cronograma/
│   ├── fase-0-git-github.md
│   ├── fase-1-fundamentos.md
│   ├── fase-2-linux.md
│   ├── fase-3-redes.md
│   ├── fase-4-windows-ad.md
│   ├── fase-5-python-sql.md
│   ├── fase-6-seguranca.md
│   ├── fase-7-soc-blue-team.md
│   ├── fase-8-infraestrutura-cloud.md
│   └── fase-9-mercado.md
├── anotacoes/
│   ├── fundamentos/
│   ├── linux/
│   ├── redes/
│   ├── windows/
│   └── seguranca/
├── laboratorios/
│   ├── packet-tracer/
│   ├── wireshark/
│   ├── active-directory/
│   ├── pfsense-suricata/
│   └── soc/
├── scripts/
│   ├── bash/
│   ├── powershell/
│   └── python/
└── projetos/
    ├── log-parser/
    └── homelab-soc/
```

As pastas serão criadas progressivamente, conforme os estudos avançarem.

## Modelo de registro semanal

Cada semana poderá ser documentada com este modelo:

### Semana XX — Nome do conteúdo

**Objetivo:** descrever o que pretendo aprender.

**Conteúdos estudados:**
- Conceito 1.
- Conceito 2.
- Conceito 3.

**Prática realizada:**
- Descrever o laboratório.
- Registrar as configurações utilizadas.
- Apresentar os resultados dos testes.

**Principais aprendizados:**
- O que aprendi.
- O que consegui executar.
- O que ainda preciso revisar.

**Dificuldades encontradas:**
- Registrar erros, dúvidas e como foram investigados.

**Evidências:**
- Prints sem dados sensíveis.
- Diagramas.
- Arquivos de laboratório.
- Scripts e resultados fictícios.

**Critério de conclusão:** descrever o que preciso conseguir fazer para considerar a semana concluída.

**Status:** Não iniciado / Em andamento / Concluído.

## Ferramentas previstas

- GitHub e GitHub Desktop.
- Visual Studio Code.
- VirtualBox.
- Ubuntu Linux.
- Windows Server e PowerShell.
- Cisco Packet Tracer.
- Wireshark.
- Python e SQL.
- pfSense e Suricata.
- Wazuh, Splunk e Elastic.
- TryHackMe e LetsDefend.
- Microsoft Learn e Cisco Networking Academy.

A instalação e a utilização de cada ferramenta ocorrerão conforme a fase correspondente.

## Regras de segurança e boas práticas

- Realizar testes de segurança somente em laboratórios próprios, ambientes autorizados ou plataformas legais de treinamento.
- Nunca publicar senhas, tokens, chaves privadas, arquivos `.env` ou credenciais.
- Utilizar dados fictícios ou anonimizados nos exemplos de logs.
- Não publicar flags, senhas ou soluções completas de máquinas ativas de CTF.
- Não expor endereços, informações de clientes ou dados internos de ambientes profissionais.
- Revisar os arquivos na aba `Changes` do GitHub Desktop antes de cada commit.
- Manter o arquivo `.gitignore` configurado para o projeto.
- Documentar o aprendizado e o raciocínio, não apenas o resultado final.

## Fontes de estudo

- [Cisco Networking Academy](https://www.netacad.com/)
- [Cisco Skills for All](https://skillsforall.com/)
- [NIC.br — Cursos e eventos](https://cursoseventos.nic.br/)
- [Fundação Bradesco — Escola Virtual](https://www.ev.org.br/)
- [Microsoft Learn](https://learn.microsoft.com/pt-br/)
- [CERT.br — Cartilha de Segurança para Internet](https://cartilha.cert.br/)
- [Cloudflare Learning Center](https://www.cloudflare.com/pt-br/learning/)
- [OverTheWire](https://overthewire.org/wargames/)
- [TryHackMe](https://tryhackme.com/)
- [LetsDefend](https://letsdefend.io/)
- [Fortinet Training Institute](https://training.fortinet.com/)
- [CompTIA](https://www.comptia.org/)
- [ISC2](https://www.isc2.org/)
- [Splunk Education](https://www.splunk.com/en_us/training.html)
- [GitHub Skills](https://skills.github.com/)

A disponibilidade dos cursos e a validade dos links serão verificadas durante a execução do roadmap.

## Objetivo final

Ao concluir a trilha, espero ter construído uma base sólida em redes, Linux, Windows, programação e segurança da informação, além de um portfólio com laboratórios e projetos documentados.

O foco é transformar conhecimento teórico em prática demonstrável, desenvolver capacidade de investigação e troubleshooting e me preparar para oportunidades profissionais em SOC, Blue Team e infraestrutura segura.

**Este repositório será atualizado ao longo da jornada. Cada commit representará uma etapa documentada do meu aprendizado.**
