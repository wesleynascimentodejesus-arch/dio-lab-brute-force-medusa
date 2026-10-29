# Laboratório de Auditoria de Autenticação com Kali Linux e Medusa

> Projeto educacional para a DIO. Os resultados devem ser preenchidos somente após testes reais em laboratório próprio e isolado.

## Objetivo
Estudar riscos de autenticação relacionados a senhas fracas, tentativas repetidas e password spraying, documentando evidências e medidas de mitigação.

## Escopo e autorização
Os procedimentos destinam-se exclusivamente a máquinas virtuais e aplicações intencionalmente vulneráveis sob controle do estudante. Não use estas instruções contra sistemas públicos ou contas de terceiros. Mantenha a rede do laboratório isolada.

## Ambiente planejado
- Kali Linux: estação de auditoria.
- Metasploitable 2: alvo de treinamento para serviços vulneráveis.
- DVWA: aplicação web vulnerável para estudo de autenticação.
- VirtualBox: virtualização.
- Medusa: auditoria de autenticação.
- Nmap: identificação de serviços.
- Rede: Host-only, com endereços privados.

> O DVWA pode exigir uma VM/instalação separada. Não exponha DVWA ou Metasploitable à internet.

## Estrutura do repositório
- `docs/configuracao-laboratorio.md`: preparação e isolamento.
- `docs/metodologia-de-testes.md`: plano de testes e registro de resultados.
- `docs/medidas-de-mitigacao.md`: recomendações.
- `wordlists/`: exemplos fictícios, sem credenciais reais.
- `images/evidencias/`: adicione capturas de tela próprias, sem dados sensíveis.

## Metodologia
1. Preparar e isolar as máquinas virtuais.
2. Confirmar conectividade e registrar os serviços disponíveis.
3. Analisar o FTP de laboratório, sem sair do escopo autorizado.
4. Avaliar a resposta do formulário de login do DVWA.
5. Estudar o risco de password spraying em SMB usando apenas contas fictícias.
6. Registrar evidências, limitações e recomendações.

## Registro dos resultados
**Preencha esta tabela somente após realizar cada teste. Não declare sucesso sem evidência.**

| Cenário | Data | Configuração | Resultado observado | Evidência | Mitigação |
|---|---|---|---|---|---|
| FTP | Pendente | Pendente | Não executado | Pendente | Restringir acesso; preferir SFTP/SSH |
| DVWA | Pendente | Pendente | Não executado | Pendente | Limitar tentativas; monitorar eventos |
| SMB | Pendente | Pendente | Não executado | Pendente | Restringir portas; revisar contas e políticas |

## Recomendações de segurança
- Adotar senhas fortes e exclusivas e evitar reutilização.
- Aplicar limitação de tentativas e atrasos progressivos, conforme o risco.
- Habilitar MFA quando disponível.
- Restringir FTP/SMB por firewall e segmentação.
- Desativar serviços desnecessários e manter sistemas atualizados.
- Monitorar falhas de autenticação e investigar padrões anormais.
- Evitar mensagens de erro que revelem se um usuário existe.

## Conclusão
O laboratório demonstra como políticas de senha frágeis e controles insuficientes de autenticação podem aumentar o risco de acesso indevido. A conclusão final deve ser atualizada com base nos resultados realmente observados, incluindo limitações do ambiente.

## Referências
- Kali Linux: https://www.kali.org/
- Medusa: http://www.foofus.net/jmk/medusa/medusa.html
- DVWA: https://github.com/digininja/DVWA
- Nmap: https://nmap.org/book/
- GitHub Docs: https://docs.github.com/
- Sintaxe Markdown: https://docs.github.com/pt/get-started/writing-and-formatting-on-github/basic-writing-and-formatting-syntax

## Uso responsável
Conteúdo para fins educacionais e defensivos. Execute testes somente em ambientes próprios ou com autorização expressa. Não inclua senhas reais, tokens, endereços públicos ou informações pessoais no repositório.
