# Configuração do laboratório

## Topologia
- VM 1: Kali Linux.
- VM 2: Metasploitable 2.
- DVWA: instalação separada ou VM adicional, conforme a configuração escolhida.
- VirtualBox: rede Host-only para o laboratório.

## Preparação segura
1. Desligue as VMs antes de alterar a rede.
2. Configure os adaptadores das VMs de laboratório para a mesma rede Host-only.
3. Evite adaptadores em modo Bridge para as máquinas vulneráveis.
4. Se precisar baixar atualizações, use uma conexão temporária controlada e depois restaure o isolamento.
5. Inicie as VMs e anote seus endereços privados.
6. Confirme que a comunicação ocorre apenas dentro do laboratório.
7. Faça snapshots antes de modificar serviços ou configurações.

## Registro
- Data:
- Versões das VMs:
- Rede Host-only:
- IP privado do Kali:
- IP privado do alvo:
- DVWA instalado em:
- Observações:

Não publique endereços públicos, credenciais ou dados sensíveis nas evidências.
