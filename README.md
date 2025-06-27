# TecManage — Sistema de Gestão Técnica da TecSolutions

**TecManage** é uma plataforma completa de gestão técnica para empresas de suporte em TI. Desenvolvido sob medida para a TecSolutions, o sistema oferece controle total de clientes, contratos, inventário de hardware, tickets de atendimento, relatórios e agente de monitoramento.

---

## 🚀 Funcionalidades Principais

### 🔐 Autenticação

- Login com e-mail e senha
- Recuperação de senha
- Perfis de usuário:
  - Administrador (acesso completo)
  - Técnico (acesso limitado)

---

### 🧭 Dashboard

- Resumo geral dos tickets:
  - Em andamento
  - Concluídos
  - Em atraso
- Alertas de desempenho de equipamentos
- Logotipo personalizado da TecSolutions
- Gráficos de performance e alertas

---

### 👥 Gestão de Clientes

- Cadastro completo de clientes
- Histórico de atendimento
- Upload de contratos e documentos

---

### 📄 Contratos

- Contrato Avulso ou Mensal
- Campos: horas inclusas, valor, tipo de atendimento
- Alerta de franquia excedida
- Controle de renovação

---

### 🧾 Ordens de Serviço

- Criadas quando equipamento chega ao laboratório
- Status e histórico técnico
- Geração de PDF com assinatura digital

---

### 🖥️ Inventário de Hardware

- Coletado automaticamente via agente instalado
- Informações detalhadas: CPU, RAM, disco, temperatura, etc.
- Histórico de alterações
- Gestão de softwares instalados (instalar/desinstalar)

---

### 🎫 Tickets de Atendimento

- Abertura por técnico ou cliente
- Tipos: Presencial, Remoto, Laboratório
- Registro de início, término, pausa para almoço
- Descrição técnica do serviço
- Histórico automático ao encerrar
- Base para relatórios e faturamento

---

### 📆 Agenda

- Visualização por semana e mês
- Abertura automática de ticket ao agendar
- Filtro por técnico e cliente
- Impressão da agenda mensal

---

### 📈 Relatórios

- Filtros por cliente, técnico, período
- Total de atendimentos, horas gastas e tipos de serviço
- Cálculo automático de horas do contrato
- Exportação para PDF e Excel

---

### 📡 Agente Instalador (cliente)

- Instalação nos computadores dos clientes
- Coleta de inventário
- Abertura de tickets pelo cliente
- Chat com técnico
- Notificações por e-mail para cliente e diretoria

---

### 🖥️ Acesso Remoto

- Integração com apps externos (AnyDesk, Supremo, RustDesk)
- Registro de sessões no histórico

---

### 👨‍💻 Gestão de Usuários

- Cadastrar, editar e excluir usuários
- Administrador: acesso total
- Técnico: acesso restrito (tickets, OS, agenda)

---

## 📦 Tecnologias Utilizadas

- Backend: Node.js, Express
- Frontend: React.js + Tailwind CSS
- Banco de Dados: PostgreSQL
- Autenticação: JWT
- Armazenamento: AWS S3 (para documentos)
- Deploy: Render

---

## 📌 Roadmap Futuro

- 📱 Aplicativo mobile para técnicos
- 💬 Integração com WhatsApp
- 📜 Assinatura digital em ordens de serviço
- ⏱️ SLA e alertas de vencimento de contratos
- 🔒 Logs de atividade por usuário

---

## 📄 Licença

Sistema desenvolvido exclusivamente para uso interno da empresa **TecSolutions**.

---

## 🤝 Contato

Para dúvidas, suporte ou sugestões:  
📧 contato@tecsolutions.com.br  
🔗 https://www.tecsolutions.com.br
