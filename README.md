# happy_end

Descrição
---------
Sistema para agendamento de massagens.

Motivadores
-----------
Ter um sistema justo, prático e fácil para agendamento da massagem para os Locawebers. Provendo uma administração para o controle do processo, garantindo uma maior eficácia do benefício. 

Escopo
------
- Permitir o agendamento e consultas web e mobile das massagens.
- Autenticação com usuário e senha de rede. (Sistema padrão de autenticação Locaweb).
- Gerenciamento da agenda dos massagistas.
- Travar o acesso fora da rede Locaweb.
- (Report) Ranking dos mais utilizados.
- Controle de "punição" para ausência.
- Gerenciamento (RH) do sistema: 
  * Cadastro de massagistas.
  * Das punições. 

Regras de punição
-----------------
- 1 ausência = 1 semana sem marcar massagem.
- 2 ausências consecutivas = 3 semana sem marcar massagem.
- 3 ausências consecutivas = 1 mês sem marcar massagem.
- 4 ausências consecutivas = O usuário será bloqueado.
- O RH a qualquer momento poderá anular as ausências e/ou desbloquear o usuário.
- A pontuação irá zerar se na próxima consulta se a pessoa comparecer e se a mesma já não estiver com 4 ausências.

Regras de massagem
------------------
- Cada Locaweber poderá agendar uma massagem por semana. Isso fará com que mais pessoas tenham oportunidade para conseguir o agendamento.
- O sistema permitirá marcar a semana corrent e a próxima semana.
