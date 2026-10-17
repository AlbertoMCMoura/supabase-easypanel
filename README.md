# Supabase (modelo Easypanel) — moveatuati

Cópia de `easypanel-io/compose` (pasta `supabase/code`, commit 405fd49, 21/05/2025)
com **uma única mudança**: o serviço `realtime` ganha o alias de rede
`realtime-dev.supabase-realtime`, nome que o Kong usa para encaminhar `/realtime/v1/`.

Sem esse alias o Kong responde 503 em todo o Realtime (websocket nunca conecta).

Nenhuma senha fica aqui: todas as variáveis continuam no Easypanel (Ambiente).
