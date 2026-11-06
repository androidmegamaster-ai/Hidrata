# 💧 Hidrata

Aplicativo web (PWA) de **lembrete e monitoramento de hidratação**, feito para o iPhone. Funciona como um app nativo quando adicionado à Tela de Início.

**Acesse:** https://androidmegamaster-ai.github.io/Hidrata/

## ✨ Recursos

- **Meta personalizada:** calculada pelo seu peso (35 ml por kg) ou definida manualmente.
- **Registro rápido:** botões grandes com tamanhos de copo editáveis e anel de progresso animado.
- **Tipos de bebida:** água, chá, café e suco, cada um com seu fator de hidratação.
- **Lembretes:** horários calculados entre o momento em que você acorda e dorme, com aviso quando você está atrasado na meta.
- **Histórico:** gráficos de 7 e 30 dias, comparação semanal, calendário do mês, sequência de dias e medalhas.
- **Edição de registros:** corrija ou apague qualquer registro dos últimos dias.
- **Treino e calor:** aumente a meta do dia com um toque.
- **Backup:** exporte e importe seus dados.
- **Atalho com a Siri:** registre água por voz com o app Atalhos.
- **Aparência:** modo claro, escuro ou automático, com quatro cores de destaque.

## 📱 Como instalar no iPhone

1. Abra o endereço acima no **Safari**.
2. Toque em **Compartilhar** e depois em **Adicionar à Tela de Início**.
3. Abra o app pelo ícone novo e ative os lembretes em **Ajustes**.

> As notificações exigem iOS 16.4 ou superior e o app instalado na Tela de Início.

## 🛠️ Tecnologias

React, Tailwind CSS, Service Worker e `localStorage`, tudo em um único `index.html`, sem etapa de build.

## 🔒 Privacidade

Todos os dados ficam salvos apenas no seu aparelho. Nada é enviado para servidores.

## ⚠️ Limitações

Os lembretes são verificados enquanto o app está aberto ou ao voltar para ele. O iOS não permite alertas com o app totalmente fechado sem um servidor de Web Push.

