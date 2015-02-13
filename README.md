# happy_ending

Descrição
---------
Sistema de agendamento e gerenciamento dos horários de massagens dos Locawebers.

Motivadores
-----------
Tornar mais justo, prático e fácil o agendamento de massagem para os Locawebers, através de um sistema que ajude a administração e controle do processo, garantindo uma maior eficácia do benefício. Assim, a iniciativa se torna acessível ao maior número possível de pessoas.

Escopo
------
- Permitir o agendamento e consultas de horários das massagens via web e mobile.
- Autenticação com usuário e senha de rede. (Sistema padrão de autenticação Locaweb).
- Gerenciamento da agenda dos massagistas.
- Travar o acesso fora da rede Locaweb.
- (Report) Ranking dos mais utilizados.
- Criação e controle de um sistema de "punição" para o não comparecimento em horários marcados.
- Gerenciamento (RH) do sistema:
  * Cadastro de massagistas.
  * Das punições.

Regras de punição
-----------------
- 1 ausência = 1 semana sem poder marcar a próxima massagem.
- 2 ausências consecutivas = 3 semanas sem poder marcar a próxima massagem.
- 3 ausências consecutivas = 1 mês sem poder marcar a próxima massagem.
- 4 ausências consecutivas = O usuário será bloqueado e não poderá marcar mais massagens.
- O RH poderá anular as ausências e/ou desbloquear o usuário a qualquer momento diante da solicitação do Locaweber.
- Caso a pessoa compareça ao próximo agendamento, a pontuação será zerada se não existirem 4 ausências consecutivas anteriormente em seu nome.

Regras de massagem
------------------
- Cada Locaweber poderá agendar uma massagem por semana. Isso deixará o benefício mais bem distribuído, igualando a oportunidade de todos em conseguir um horário.  
- O sistema permitirá marcar horário da semana corrente e da seguinte.
