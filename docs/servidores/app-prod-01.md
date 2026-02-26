# APP-PROD-01

## 1. Informações Gerais
- Ambiente: Produção
- Status: Ativo
- Responsável: Infra TI
- Data de criação: 15/01/2024

## 2. Sistema Operacional
- Sistema: Windows Server
- Versão: 2022
- Atualizações: Automáticas
- Timezone: GMT-3

## 3. Hardware / Recursos
- CPU: 4 vCPU
- Memória RAM: 16 GB
- Disco:
  - C: 100 GB
  - D: 300 GB
- Tipo: VM
- Hypervisor / Cloud: VMware

## 4. Rede
- IP: 10.10.1.20
- Gateway: 10.10.1.1
- DNS: 10.10.1.5
- VLAN: 20
- Firewall: Liberado para APP

## 5. Função do Servidor
- Papel principal: Aplicação interna
- Serviços instalados: IIS
- Aplicações: Sistema Interno X

## 6. Segurança
- Antivírus: Defender
- Backup configurado: Sim
- Criptografia: Não
- Última auditoria: 01/12/2024

## 7. Backup
- Tipo: Incremental
- Frequência: Diário
- Retenção: 15 dias
- Ferramenta: Veeam

## 8. Monitoramento
- Ferramenta: Zabbix
- Alertas configurados: CPU / Disco
- Responsável: NOC

## 9. Acessos
- Tipo de acesso: RDP
- Grupo AD: TI-Infra
- Observações: Acesso restrito

## 10. Observações Gerais
- Servidor crítico para operação
