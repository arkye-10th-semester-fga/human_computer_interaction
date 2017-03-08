**Nome**: Jonathan Henrique Maia de Moraes
**Matrícula**: 12/0122553
**Disciplina**: Interação Humano Computador - 201316
**Professor**: André Barros de Sales
**Data**: 07/03/2017

# Exercício 1 - SWEBOK

## Questões

1. O que é SWEBOK? Por quem e para que ele foi escrito?
	* **R**: `SWEBOK` é um conjunto de práticas que consolidam informações de diversas áreas de conhecimento da Engenharia de _Software_ (pág. xxxi), sua abreviação significa: _Software Engineering Body of Knowledge_ - Corpo de Conhecimento de Engenharia de _Software_. Foi criado pelo quadro de atividades profissionais da IEEE (pág. xxxi) com os seguintes objetivos:
		1. Promover uma visão consistente da engenharia de _software_ mundialmente; (pág. xxxi)
		1. Especificar o escopo de, e clarificar o espaço da engenharia de _software_ em respeito às outras disciplinas como ciências da computação, gerenciamento de projetos, engenharia da computação e matemática; (pág. xxxi)
		1. Caracterizar os conteúdos da disciplinas de engenharia de _software_; (pág. xxxi)
		1. Prover uma fundação para o desenvolvimento curricular e para certificação individual, além de licenciamento de material. (pág. xxxi)
1. Baseado no SWEBOK v. 3.0, descreva o que é Projeto de Interface do Usuário (User Interface Design). Essa descrição deve conter:
	1. Qual área do conhecimento (KA) ele está contido;
		* **R**: Projeto de Interface do Usuário está contido na área de conhecimento **Projeto de Software*** (pág. 2-2).
	1. Os princípios gerais;
		* **R**: Consiste em:
			1. **Aprendizagem**: O _software_ deve ser de fácil aprendizado de forma que o usuário possa rapidamente iniciar o trabalho com o _software_ (pág. 2-6);
			1. **Familiaridade com o usuário**: A _interface_ deve usar termos e conceitos advindos de experiências de pessoas que usarão o _software_ (pág. 2-6);
			1. **Consistência**: A _interface_ deve ser consistente de forma que operações parecidas sejam ativadas da mesma maneira (pág. 2-6);
			1. **Surpresas mínimas**: O comportamento do _software_ não deve apanhar de surpresa o usuário (pág. 2-6);
			1. **Recuperabilidade**: A _interface_ deve prover mecanismos que permitam usuários se recuperarem de erros (pág. 2-6);
			1. **Direcionamento de Usuário**: A _interface_ deve prover _feedbacks_ significativos quando erros acontecerem e prover ajuda relacionada ao contexto para os usuários (pág. 2-6);
			1. **Diversidade de Usuário**: A _interface_ deve prover mecanismos de interação apropriados para diversos tipos de usuários e para usuários com diferentes capacidades (cegueira, visibilidade reduzida, mudez, daltonias, etc.) (pág. 2-6).
	1. Os problemas principais;
		* **R**: O projeto de _interface_ deve resolver dois principais problemas:
			1. Como o usuário deve interagir com o _software_? (pág. 2-6)
			1. Como deve ser apresentado informações do _software_ para o usuário? (pág. 2-6)
	1. As Modalidades;
		* **R**: Podem ser classificados de acordo com os seguintes estilos principais:
			1. **Pergunta-resposta**: A interação é essencialmente restrito na simples troca de pergunta-resposta entre o usuário e o _software_. O usuário entrega uma questão ao _software_ e o _software_ retorna a resposta para a questão (pág. 2-6);
			1. **Manipulação direta**: Usuários interagem com objetos na tela do computador. Manipulação direta geralmente incluí um dispositivo de apontamento (tais como um mouse ou _touch screens_) que manipulam um objeto e invocam ações que especificam o que é para ser feito com aquele objeto (pág. 2-6);
			1. **Seleção de menu**: O usuário seleciona um comando de uma lista de comandos (pág. 2-6);
			1. **Preenchimento de formulário**: O usuário preenche campos de um formulário (pág. 2-6);
			1. **Linguagem de commandos**: O usuário entrega um comando e provê paramêtros relacionados para direcionar o _software_ no que deve ser feito (pág. 2-6);
			1. **Linguagem natural**: O usuário entrega um comando em linguagem natural. Isto é, a linguagem natural é uma fachada para a linguagem de comando e é filtrada e traduzida em comandos de _software_ (pág. 2-6).
	1. A apresentação da informação;
		* **R**: Um bom _design_ mantém a apresentação de informações separados das próprias informações (pág. 2-6). A abordagem `MVC` (_Model-View-Controller_) é uma maneira efetiva de manter a apresentação das informações separadas das informações (pág. 2-6).  Também deve-se considerar o tempo de resposta e _feedback_ do _software_ durante o projeto de apresentação da informação (pág. 2-7). Visualizações abstratas podem ser utilizadas quando grande quantidade de informação estão para ser apresentadas (pág. 2-7). Além disso, projetistas também podem utilizar cores para aprimorar a _interface_ (pág. 2-7).
	1. Processo;
		* **R**: O projeto de _interface_ do usuário é um processo iterativo (pág. 2-7). Protótipos de _interface_ geralmente são utilizados para determinar funcionalidades, organização e estilo da _interface_ de usuário do _software_ (pág. 2-7). Tal processo inclui três atividades principais:
			1. **Análise do usuário**: Nesta fase o projetista analisa as tarefas do usuário, o ambiente de trabalho, outros _softwares_, e como os usuários interagem com as outras pessoas (pág. 2-7);
			1. **Prototipação de _software_**: Desenvolver protótipos de _software_ auxilia usuários a guiar a evolução da _interface_ (pág. 2-7);
			1. **Avaliação de _interface_**: Projetistas podem observar experiências de usuário com a _interface_ em evolução (pág. 2-7).
	1. Localização e Internacionalização;
		* **R**: O projeto de _interface_ do usuário geralmente precisa considerar a internacionalização e a localização, o que significa adaptar o _software_ para diferentes linguagens, para diferenças regionais e para requisitos técnicos de mercado-alvo (pág. 2-7). Localização e internacionalização devem considerar fatores como símbolos, números, moeda, hora, e unidades de medida (pág. 2-7).
	1. Modelos conceituais e metáforas;
		* **R**: Projetistas de _interface_ do usuário podem utilizar metáforas e modelos conceituais para configurar um mapeamento entre o _software_ e algum sistema de referência conhecido para os usuários do mundo real, o que pode ajudar o usuário a rapidamente aprender e utilizar a interface (pág. 2-7). Deve-se tomar cuidado em não utilizar mais de uma metáfora para cada conceito (pág. 2-7). Metáforas também apresentam potenciais problemas em relação a internacionalização, pois nem todas as metáforas são significativos ou aplicáveis da mesma maneira para todas as culturas (pág. 2-7).
1. Baseado no SWEBOK v. 3.0, descreva o que é Teste de Software. Essa descrição deve conter a definição e o objetivo dos Testes de Usabilidade e Interação Humano Computador.
	* **R**: Teste de _software_ consiste na verificação dinâmica de que o programa provê comportamentos esperados em um conjunto finito de casos de teste, convenientemente selecionado do usual domínio de execução infinita (pág. 4-1). A tarefa principal de testes de usabilidade e interação humano computador é avaliar o quão fácil são para os usuários finais aprender e utilizar o _software_ (pág. 4-7). De modo geral, pode envolver testar funções do _software_ que apoiam tarefas do usuário, documentações que apoiam os usuários e a habilidade do sistema de se recuperar de erros de usuário (pág. 4-7).

## Referência Bibliográfica

* _2014. Guide to the Software Engineering Body of Knowledge - SWEBOK. Pierre Bourque, Richard E. Fairley (Eds.). IEEE Press, Piscataway, NJ, USA._
