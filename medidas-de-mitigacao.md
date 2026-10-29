# Medidas de mitigação

## Senhas e contas
- Exigir senhas longas e exclusivas e impedir senhas conhecidas como comprometidas, quando possível.
- Evitar reutilização entre serviços.
- Remover contas padrão e desabilitar contas sem uso.
- Usar MFA para serviços compatíveis.

## Proteção contra tentativas repetidas
- Aplicar limitação de taxa, atrasos progressivos e bloqueios temporários com cuidado para evitar negação de serviço.
- Gerar alertas para falhas repetidas, tentativas distribuídas e password spraying.
- Monitorar autenticações por usuário, origem, serviço e período.
- Evitar mensagens de erro que indiquem se um nome de usuário existe.

## Serviços de rede
- Desabilitar FTP quando desnecessário; preferir SFTP/SSH ou FTPS conforme o caso.
- Restringir SMB a redes e hosts que realmente precisam dele.
- Bloquear portas desnecessárias no firewall.
- Desativar protocolos antigos e aplicar atualizações de segurança.
- Segmentar redes e revisar permissões de compartilhamentos.

## Aplicações web
- Aplicar rate limiting no login.
- Registrar eventos sem guardar senhas ou tokens.
- Usar cookies seguros, HTTPS e proteção de sessão adequada.
- Realizar testes periódicos em ambiente de homologação.

## Verificação pós-correção
Após aplicar as medidas, repetir testes limitados no laboratório e confirmar que os controles atuam conforme esperado. Guardar evidências antes/depois sem dados sensíveis.
