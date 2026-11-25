# Guia passo a passo

1. Planeje uma VM Linux compatível com a versão atual do Wazuh e confira requisitos oficiais de CPU, RAM e disco.
2. Instale o ambiente all-in-one seguindo o Quickstart oficial da versão escolhida.
3. Guarde as credenciais fora do repositório e acesse o Dashboard pela rede privada do laboratório.
4. Instale um agente Windows ou Linux compatível e registre-o no servidor.
5. Confirme que o agente aparece ativo no Dashboard.
6. Gere eventos benignos em conta/VM de teste e localize-os no painel.
7. Investigue um evento: horário, endpoint, usuário, regra, contexto e possível falso positivo.
8. Documente conclusão, limitações e recomendações sem afirmar detecção que não ocorreu.

## Critério de conclusão
Marque o laboratório como executado somente quando conseguir reproduzir as etapas e guardar evidências verificáveis.
