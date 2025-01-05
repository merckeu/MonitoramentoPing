    Substituído envio de e-mail por tool fetch:
        O script usa requisições HTTP para notificar eventos
            Host fora de alcance: /host_fora
            Latência OK: /latencia_ok
            Latência alta: /latencia_alta

    Mensagens no Log
        Log de erro ou aviso para cada caso com detalhes do evento.

    URLs de Notificação:
        Personalize as URLs para o sistema de notificação que você utiliza

    Controle de Status
        Evita notificações duplicadas ao verificar se o status atual é igual ao anterior ($oldstatus)

Configuração no Agendador

Para executar o script regularmente, adicione-o ao agendador:

/system scheduler add name="MonitorPing" interval=1m on-event="nome_do_script"...

Substitua nome_do_script pelo nome que você salvou.
