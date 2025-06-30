# Implementando-Monitoramento-no-Azure

Etapas para configurar o monitoramento de VMs no Azure
- Criar uma Máquina Virtual (VM) Comece provisionando uma VM no portal do Azure. Pode ser Windows ou Linux, dependendo do seu cenário.
- Criar um Log Analytics Workspace Esse workspace será o repositório central onde logs e métricas serão armazenados e analisados.
- Instalar o Azure Monitor Agent (AMA) O agente coleta dados do sistema operacional convidado e envia para o Log Analytics. Ele substitui os agentes legados (MMA/OMS).
- Ativar o VM Insights Essa funcionalidade oferece dashboards prontos com métricas como CPU, memória, disco e rede em tempo real.
- Configurar Alertas com Action Groups Crie alertas para eventos críticos, como a exclusão de uma VM, e defina ações automáticas como envio de e-mail, execução de scripts ou chamadas para webhooks.
- Visualizar e Analisar os Dados Use o Log Analytics com KQL (Kusto Query Language) para consultas avançadas e diagnósticos detalhados.
- Automatizar Respostas com Azure Automation (opcional) Combine alertas com runbooks para respostas automáticas, como recriar uma VM excluída.
