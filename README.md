# PrintConnect

### Impressão rápida, silenciosa e confiável para Windows

O **PrintConnect** conecta o **FastMenu Pro** às impressoras do computador, permitindo realizar impressões diretamente pelo sistema, sem utilizar a janela de impressão do navegador.

---

## 📥 Download

### PrintConnect para Windows

**Versão atual: v0.5.1**

⬇️ **[BAIXAR PRINTCONNECT PARA WINDOWS](https://github.com/MarcosViniciusF/PrintConnect-Download/releases/latest)**

Compatível com **Windows 10 e Windows 11 — 64 bits**

> Para uma instalação nova, baixe o instalador `.exe` na página da Release.
>
> O PrintConnect verifica automaticamente novas versões e permite realizar atualizações diretamente pelo aplicativo.

---

## 🚀 Instalação

1. Clique no botão **BAIXAR PRINTCONNECT PARA WINDOWS** acima.
2. Na página da Release, baixe o arquivo:
   `PrintConnect-Setup-0.5.1.exe`
3. Execute o instalador.
4. Siga as instruções apresentadas na tela.
5. Após a instalação, o PrintConnect será configurado para iniciar automaticamente com o Windows.

### 🔄 Atualizações

Depois de instalado, não é necessário baixar manualmente cada nova versão.

O PrintConnect possui um sistema de atualização automática:

```text
Nova versão disponível
        ↓
Verificar atualização
        ↓
Atualizar agora
        ↓
Backup automático
        ↓
Atualização do sistema
        ↓
Validação da nova versão
        ↓
PrintConnect atualizado

🖨️ Como funciona
FastMenu Pro
      ↓
PrintConnect
      ↓
Impressora

O PrintConnect funciona localmente no Windows e realiza a comunicação entre o FastMenu Pro e as impressoras instaladas no computador.

O sistema permite realizar impressões sem depender da janela de impressão do navegador.

⚡ Recursos
🖨️ Impressão silenciosa
⚡ Impressão rápida
🔵 Suporte a impressoras Bluetooth
🖨️ Suporte a impressoras Windows
📄 Impressão de textos
🖼️ Impressão de imagens
📋 Fila persistente de impressão
🔄 Recuperação da fila após reinicialização
🔗 Integração com sistemas web
⚙️ Serviço Windows em segundo plano
🔄 Inicialização automática com o Windows
📡 API local para comunicação com sistemas web
🔍 Detecção de impressoras
🛠️ Diagnóstico Bluetooth
📊 Dashboard de monitoramento
🔄 Atualização automática
💾 Backup antes da atualização
↩️ Sistema de rollback
✅ Validação após atualização
🚀 Reabertura automática após atualização
🛡️ Atualização independente do FastMenu Pro
🔄 Sistema de atualização

O PrintConnect possui um sistema próprio de atualização independente do FastMenu Pro.

Quando uma nova versão é publicada, o aplicativo verifica automaticamente a disponibilidade da atualização.

Processo de atualização
PrintConnect
     ↓
Verifica nova versão
     ↓
Nova versão encontrada
     ↓
Usuário clica em "Atualizar agora"
     ↓
Dashboard é encerrado
     ↓
Serviço é interrompido
     ↓
Backup da instalação
     ↓
Agent atualizado
     ↓
Desktop atualizado
     ↓
Serviço reiniciado
     ↓
Versão validada
     ↓
Dashboard iniciado novamente

O processo possui mecanismos de segurança para evitar que uma atualização incompleta deixe o sistema indisponível.

💾 Persistência da fila

Os trabalhos de impressão são armazenados localmente.

Isso permite que a fila seja preservada mesmo após:

Reinicialização do computador
Reinicialização do serviço
Interrupção temporária da impressora

Quando o serviço volta a funcionar, os trabalhos pendentes podem ser processados novamente.

🔵 Impressoras Bluetooth

O PrintConnect possui suporte para impressoras térmicas Bluetooth compatíveis.

O sistema identifica as impressoras Bluetooth disponíveis e permite realizar a comunicação diretamente com o dispositivo.

Também possui uma ferramenta de:

Diagnóstico Bluetooth

para auxiliar na identificação de problemas de comunicação.

🖨️ Impressoras Windows

O PrintConnect também pode trabalhar com impressoras instaladas normalmente no Windows.

Isso permite utilizar diferentes tipos de impressoras de acordo com a configuração do estabelecimento.

📊 Dashboard

O PrintConnect possui um painel local para acompanhamento do serviço.

O Dashboard apresenta informações como:

Status do PrintConnect
Versão instalada
Quantidade de impressoras
Fila de impressão
Status dos trabalhos
Número de tentativas
Erros de impressão
Impressoras detectadas
Status do serviço
Verificação de atualizações
🔗 Integração com sistemas web

O PrintConnect possui uma API local para comunicação com sistemas web.

O sistema web pode enviar uma solicitação de impressão para o PrintConnect instalado no computador.

O PrintConnect recebe o trabalho e encaminha para a impressora configurada.

Arquitetura
Sistema Web
   │
   │ API local
   ▼
PrintConnect
   │
   ├── Impressora Windows
   │
   └── Impressora Bluetooth

O PrintConnect é executado localmente no computador do estabelecimento.

🔒 Segurança e funcionamento local

O PrintConnect foi desenvolvido para funcionar localmente no computador onde as impressoras estão instaladas.

A comunicação com as impressoras ocorre através do próprio computador.

O serviço utiliza uma API local para receber as solicitações de impressão.

🧰 Requisitos
Sistema operacional
Windows 10 — 64 bits
Windows 11 — 64 bits
Requisitos
Computador Windows
Impressora instalada ou conectada
Permissão de administrador para instalação
Conexão com a internet para verificar e baixar atualizações

Após instalado, o serviço do PrintConnect funciona localmente no computador.

📦 Estrutura das versões

Cada Release pode disponibilizar dois tipos de arquivos:

Instalação completa
PrintConnect-Setup-X.X.X.exe

Utilizada para novas instalações.

Atualização
PrintConnect-vX.X.X-Update.zip

Utilizada pelo sistema de atualização automática do PrintConnect.

🆕 Versão atual

PrintConnect v0.5.1

Principais melhorias
🚀 Sistema de atualização automática
💾 Backup automático antes da atualização
✅ Validação do pacote de atualização
🔎 Validação da versão após atualização
🔄 Reinicialização automática do serviço
📊 Abertura automática do Dashboard após atualização
🛡️ Correção do processo de atualização do Desktop
📊 Dashboard de monitoramento
🎨 Novo ícone do PrintConnect
📋 Melhorias na fila de impressão
🔵 Melhorias no suporte Bluetooth
📋 Histórico de versões
v0.5.1
🚀 Atualização automática pelo GitHub
🔄 Atualização segura do Agent e Desktop
💾 Backup automático
↩️ Rollback em caso de falha
✅ Validação pós-atualização
🔄 Reinicialização automática do serviço
📊 Dashboard atualizado
🔵 Melhorias no Bluetooth
🖨️ Melhorias na fila de impressão
🎨 Novo ícone do PrintConnect
🔄 Novas versões

Novas versões do PrintConnect serão disponibilizadas na seção Releases do GitHub.

⬇️ VER VERSÕES DISPONÍVEIS

Para instalações existentes, o próprio PrintConnect pode verificar a disponibilidade de novas versões.

🆘 Suporte

Está com problemas para instalar ou configurar o PrintConnect?

Entre em contato com o suporte do FastMenu Pro.

🍔 FastMenu Pro

O FastMenu Pro é um sistema de gestão e atendimento para estabelecimentos de alimentação.

O PrintConnect atua como o componente local responsável pela comunicação entre o sistema e as impressoras do estabelecimento.

📄 Licença

Este projeto é distribuído para utilização integrada ao ecossistema FastMenu Pro.

👨‍💻 Desenvolvido por

FastMenu Pro

© 2026 FastMenu Pro
