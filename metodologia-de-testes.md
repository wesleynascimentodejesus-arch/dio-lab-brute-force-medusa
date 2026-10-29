# Metodologia de testes

## Regras de escopo
- Usar apenas VMs próprias e contas de teste fictícias.
- Manter os serviços vulneráveis em rede isolada.
- Interromper o teste se o alvo não corresponder ao laboratório.
- Não testar credenciais de terceiros.
- Não declarar acesso bem-sucedido sem evidência verificável.

## Cenário A — FTP
Objetivo: compreender os riscos de senhas fracas e controles limitados de tentativas.
1. Confirmar que o serviço pertence à VM de laboratório.
2. Registrar a configuração e os controles de autenticação.
3. Realizar somente testes previamente autorizados e limitados.
4. Conferir logs e registrar o comportamento observado.
5. Anotar resultado, evidência e recomendação.

## Cenário B — Formulário web DVWA
Objetivo: observar a resposta do formulário a autenticações inválidas e avaliar controles de proteção.
1. Confirmar que a URL é a instância local do DVWA.
2. Registrar o nível de segurança e as configurações relevantes.
3. Usar contas fictícias e uma quantidade pequena e controlada de tentativas.
4. Observar mensagens, atrasos, limitação e registros.
5. Não registrar cookies, tokens ou senhas reais nas capturas.

## Cenário C — SMB e password spraying
Objetivo: estudar o risco de testar uma senha comum em várias contas e os sinais de detecção.
1. Confirmar que SMB está no alvo de laboratório.
2. Usar apenas contas de teste fictícias criadas para este exercício.
3. Definir previamente limites baixos e interromper ao primeiro sinal de impacto.
4. Verificar logs e controles de bloqueio/alerta.
5. Documentar os resultados sem divulgar credenciais.

## Ficha de resultados (copie para cada cenário)
- Cenário:
- Data e horário:
- Máquina e serviço:
- Configuração:
- Procedimento executado:
- Resultado observado:
- Evidência (arquivo em `images/evidencias/`):
- Controle de segurança identificado:
- Recomendação:
- Limitações:
