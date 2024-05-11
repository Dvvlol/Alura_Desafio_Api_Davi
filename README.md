# Alura_Desafio_Api_Davi


Criei um código  (autoexplicado) para um chatboot chamado AlertaRS para que um usuário vítima de inundações possa receber instruções de como proceder diante de alagamentos e inundações.
Fiz as instalações necessárias !pip para o sistema rodar no Colab perfeitamente e sem bugs.
Em todo o sistema fiz a implementação inteligente, caso haja uma digitação errada, ou alguma palavra ou número errado ou alucinado que alerte o usuário para que ele corrija a informação imediatamente.
Coloquei as configurações de api-code onde só faltava colocar o código api do desenvolvedor.
Identificação: "Olá, eu sou o AlertRS e estou aqui para te ajudar. "
Determinei as gravidades da inundação diante de algumas perguntas para o usuário, onde a gravidade da resposta for: 
0.10m de inundação a resposta = Grau 1 é pouca gravidade água na canela;
0.50m  a resposta = Grau 3 atenção à água no joelho procure um lugar mais alto imediatamente;
0.80m a resposta = grau 5 água na cintura procure abrigo imediatamente e ligue para a emergência;
1.60m a resposta = grau 7 com agua na altura no peito (estado de emergência, ligar imediatamente para a emergência);
1.80m grau 10 a resposta = Água acima de 2 metros de altura é Extremante grave  onde você  se encontra, procurar imediatamente comunicação com as forças de emergência para ser retirado.

Em algumas respostas o usuário deverá utilizar Sim ou Não, quando for o caso números inteiros ou fracionados com ponto. Defini Considerar igualmente a informação válida se ele usar vírgula.
Perguntas:
Pergunte se o usuário possui animais domésticos;
Pergunte a quantidade de animais;
Pergunte se tem outas pessoas juntas ele;
Pergunte se em volta da casa já tem algum desabamento ou algo atípico que ele queira relatar. 
Pergunte se pelo que ele vê, ele já se considera desabrigado. Caso resposta positiva indique os serviços sociais e de ajuda mais próximos de acordo com o google maps, e diga que essa informação vai servir para a Defesa Civil se preparar antecipadamente.

Defini: 
- Ia para Indicar para o usuário os telefones de Emergência dos Bombeiros e Defesa Civil. 

- Entrar também em contato com o sistema dos Bombeiros e Defesa Civil. Enviar o mapa por e-mail indicando a localização com endereço da ocorrência com o Aviso: Emergência nesta localização, (endereço) favor prestar socorro imediatamente! Por favor imprimir!

- Mostre pra o usuário um botão com o link com o google maps que ao clicar  o maps indicará rotas de saída da inundação. 

- Mostre para o usuário um outro botão com um link para ele acompanhar a previsão do tempo do google e caso haja alguma intempérie Grave vindo dê um alerta antes de começar, sendo o alerta visual e sonoro (Alerta de Perigo!) no aparelho indicando a gravidade da situação.
 

- Em todo o sistema deve ter implementação inteligente, caso haja uma digitação errada, ou alguma palavra errada ou número errado ou alucinado alerte o usuário para que ele corrija a informação.
