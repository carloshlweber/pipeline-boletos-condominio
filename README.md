# Pipeline-Boletos-Condominio
**Situação**
* A operação financeira atual exige o envio individual de centenas de boletos condominiais por mês.
* Cada envio consome em média 2 a 3 minutos de trabalho manual pois exige triagem e distribuição em três canais simultâneos (Whatsapp, E-mail e Impresso).
* A repetitividade do processo gera fadiga operacional, margem para erros humanos (envios trocados ou esquecimento), impactando o rendimento do setor.

**Tarefa**
* Construir um pipeline de dados e automação ponta a ponta, capaz de receber os arquivos PDF brutos (gerados via SAP), cruzar os dados extraídos com uma base de moradores atualizada e rotear os envios de forma 100% autônoma.
* O sistema deve possuir uma interface acessível para usuários não-técnicos, exigindo zero interação via terminal.

**Ação (Em Andamento)**
- Fase 1: Separação e leitura de PDFs nativos em memória.
- Fase 2: Higienização e cruzamentos de dados de contatos.
- Fase 3: Roteamento condicional (API WhatsApp, Servidor SMTP e lista de Impressão).
* Tecnologias definidas até o momento: Python (Core) e Git/GitHub (Versionamento).

**Resultado Esperado**
* Redução drástica do tempo operacional estimada em 80%.
* Eliminação completa de falhas de envio por distração.
* Geração de relatórios automáticos de auditoria (sucessos e falhas).
