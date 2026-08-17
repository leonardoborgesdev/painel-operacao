# Operação

Painel interno em tempo real para acompanhar os canais de conteúdo: views, engajamento, ranking ao vivo, fila de publicação e progresso de meta.

- **Visão geral** — KPIs do período, gráfico de views por dia, meta e monetização, ranking ao vivo
- **Canais** — tabela com bio, foto e top posts por canal
- **Posts** e **Comentários** — acompanhamento em tempo real, com notificações no canto da tela
- **Calendário** — fila de publicação e status das automações
- **Configuração** — cotas de publicação e automações ativas

Página única (HTML/CSS/JS, sem build), lê o estado publicado em um bucket do Supabase Storage e atualiza sozinha a cada minuto.

Uso interno — `noindex`, não é um produto público.
