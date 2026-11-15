# Segurança e isolamento

O experimento foi executado em uma VM Ubuntu separada do ambiente principal. O acesso ao gateway local passou por túnel SSH e a interface exigiu autenticação do gateway.

As permissões foram tratadas por agente. Ferramentas externas só deveriam ser usadas quando autorizadas, com atenção a autenticação, política, custo e dados acessados. Testes bloqueados ficaram registrados como bloqueados.

Este repositório descreve o desenho de segurança, mas não inclui a configuração privada do gateway nem credenciais.
