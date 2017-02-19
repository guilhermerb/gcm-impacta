Apache : 

27- Janeiro -2017 Alterações com o Apache 2.4.25

Alterações no Lounge do Apache:

   *) Atualizado OpenSSL para 1.0.2k de 1.0.2j (Changelog)

   *) Atualizado pcre para 8,40 a partir de 8,39 (Changelog)

   *) Atualizado zlib para 1.2.11 a partir de 1.2.8 (Changelog)

Alterações ASF:

    *) Mod_proxy_ {ajp, fcgi}: Corrigir uma possível falha ao reutilizar um sistema
       Backend, acontecendo com LogLevel trace2 ou superior configurado,
       Ou em qualquer nível de registo com compiladores não detectados como compatíveis com C99 (e.g.
       MSVC no Windows). [Yann Ylavic]
       
       
 NGINX : 
 
 Alterações com nginx 1.11.10 14 Feb 2017

    *) Alteração: o formato do cabeçalho do cache foi alterado, previamente armazenado em cache
       As respostas serão invalidadas.

    *) Recurso: suporte de "stale-while-revalidate" e "stale-if-error"
       Extensões na linha de cabeçalho de resposta do back-end "Cache-Control".

    *) Recurso: o "proxy_cache_background_update",
       "Fastcgi_cache_background_update", "scgi_cache_background_update",
       E "uwsgi_cache_background_update" diretivas.

    *) Recurso: nginx agora é capaz de cache respostas com o "Vary" cabeçalho
       Até 128 caracteres (em vez de 42 caracteres em caracteres
       Versões).

    *) Recurso: o parâmetro "build" da diretiva "server_tokens".
       Graças a Tom Thorogood.

    *) Bugfix: "[crit] SSL_write () falhou" mensagens podem aparecer em logs
       Ao tratar solicitações com o cabeçalho de solicitação "Expect: 100-continue"
       linha.

    *) Bugfix: o ngx_http_slice_module não funcionou em locais nomeados.

    *) Bugfix: uma falha de segmentação pode ocorrer em um processo de
       Usando AIO após um redirecionamento "X-Accel-Redirect".

    *) Bugfix: consumo reduzido de memória para pedidos de longa duração usando
       Gzipping
       
       
       
       WORD PRESS :
        4.7
        
       - Novo tema: Twenty Seventeen
       - Personalizar mais completo
       - Pré-visualizar CSS ao vivo no personalizador
       - Vídeo no cabeçalho
       - Controle de idioma para usuários
       - Melhorias no editor de texto
       - Fluidez na configuração de tema
       - Prévia de thumbnail para arquivos de PDF
       - Mudanças na biblioteca de multimidia
       - Tipos de conteúdo e conteúdo protegido
    
