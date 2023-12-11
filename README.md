# documentacao

Documentação de Teste


Plano de teste  - Nome do produto 

                                                                                                                                Versão 1,0

Histórico das alterações
Data 05/12/2023         	Versão 1.0           	Autor(a)Naiara Cristina 




1 - Introdução / Criar a introdução do plano de teste
Este documento descreve os requisitos a testar, os tipos de testes definidos para cada iteração, os recursos de hardware e software a serem empregados e o cronograma dos testes ao longo do projeto. As seções referentes aos requisitos, recursos e cronograma servem para permitir ao gerente do projeto acompanhar a evolução dos testes.


2 - Requisitos a Testar/ Incluir os requisitos para teste,segue exemplo abaixo
Os requisitos para testar que contempla os fluxo abaixo:

Fluxo de Primeiro Acesso:

Cadastro de Usuário:

Verificar se todos os campos obrigatórios estão presentes e são validados corretamente.
Testar a robustez do sistema ao inserir dados inválidos ou formatos incorretos.
Garantir que os requisitos  sejam seguidos e validados.




Considerações Gerais:
Segurança:
Avaliar a segurança em todas as etapas para garantir a proteção adequada dos dados do usuário.
Realizar testes de segurança, como injeção de SQL e testes de penetração.
Compatibilidade:
Testar em diferentes navegadores e dispositivos para garantir a compatibilidade.
Garantir a acessibilidade para usuários com necessidades especiais.
Desempenho:
Avaliar o desempenho do sistema sob carga, especialmente durante picos de tráfego.




3 - Casos de uso/ Inserir os casos de uso, segue exemplo
Fluxo de Primeiro Acesso:
Caso de Uso: UC1 - Registrar Novo Usuário
Ator: Novo usuário

Fluxo:
O usuário acessa a página de registro.
Preenche os campos obrigatórios (nome, e-mail, senha).
Clica em "Registrar".
Sistema valida os dados e envia um e-mail de confirmação.
O usuário confirma o registro clicando no link recebido por e-mail.


4 - Requisitos não-funcionais/ Inlcuir os requisitos não funcionais, segue exemplos abaixo.

Desempenho:
Tempo de Resposta: A aplicação deve responder aos comandos do usuário dentro de um limite de tempo aceitável.

Escalabilidade: A aplicação deve lidar com um aumento de carga (número de usuários, transações, etc.) sem degradação significativa no desempenho.

Segurança:
Criptografia: Os dados sensíveis, como informações do cartão de crédito, devem ser transmitidos e armazenados de forma segura usando protocolos de criptografia adequados.

Autenticação e Autorização: O sistema deve garantir que apenas usuários autorizados tenham acesso às funcionalidades específicas.

Confiabilidade:
Disponibilidade: A aplicação deve estar disponível para uso a maior parte do tempo, com um mínimo de tempo de inatividade planejado.
Recuperação de Falhas: Em caso de falha, o sistema deve ser capaz de se recuperar sem perda de dados significativa.
Usabilidade:
Acessibilidade: A aplicação deve ser projetada de forma a ser acessível para usuários com diferentes habilidades e necessidades especiais.
Facilidade de Uso: A interface do usuário deve ser intuitiva e fácil de usar.

Compatibilidade:
Compatibilidade do Navegador/Dispositivo: A aplicação deve ser compatível com uma variedade de navegadores e dispositivos para garantir uma ampla acessibilidade.

Manutenibilidade:
Facilidade de Atualização: A aplicação deve ser projetada para facilitar a incorporação de atualizações e correções sem interrupção significativa do serviço.

Conformidade:
Conformidade Legal: O sistema deve estar em conformidade com as leis e regulamentações aplicáveis, especialmente em relação à segurança e privacidade dos dados.

Eficiência:
Uso de Recursos: A aplicação deve utilizar eficientemente os recursos do sistema, como memória e largura de banda.

Monitoramento e Logging:
Registros de Auditoria: O sistema deve manter registros de auditoria para monitorar e rastrear atividades, especialmente aquelas relacionadas a transações financeiras.

Integração:
Integração com Sistemas Externos: Se a aplicação se integra a outros sistemas (por exemplo, serviços de pagamento), essa integração deve ser robusta e segura.


5 - Tipos de teste / Inserir os tipos de testes segue alguns exemplos

Teste de interface de usuário;
Teste de performance;
Teste de carga;
Teste de stress;
Teste de segurança;
Teste de regressão;
Teste de funcionalidade;



5.1 - Métodos da Classe
Desenvolver os testes de funcionalidade de maneira automatizada ( Esse processo está em desenvolvimento buscando melhores ferramentas e construção dos scripts)


Objetivo: Teste das funcionalidades aplicação Click to pay
Técnica:	(x) manual	               ( ) automática “em construção”
Estágio do teste: Integração ( )	Sistema ( )	Unidade ( )	Aceitação ( )
Abordagem do teste:	Caixa branca ( )	Caixa preta ( )
Responsável(is) Tester Naiara Programador(es) ou equipe de testes

5.2 - Persistência de Dados
Para teste de integridade de dados e do banco de dados verificar com equipe de desenvolvimento.


Objetivo	Verificar se dados são mantidos após súbito desligamento do programa .
Técnica:	( ) manual	( ) automática
Estágio do teste	Integração ( )	Sistema ( )	Unidade ( )	Aceitação ( )
Abordagem do teste	Caixa branca ( )	Caixa preta ( )
Responsável(is)	Programador(es) ou equipe de testes

5.3 - Integração dos Componentes
Para teste de funcionalidade. Aqui deve-se verificar se as classes e métodos conseguem fazer a integração entre elas para uma sequência de ações do programa. Em criação


Objetivo	Verificar a integração dos componentes
Técnica:	() manual	() automática
Estágio do teste	Integração ()	Sistema ( )	Unidade ( )	Aceitação ( )
Abordagem do teste	Caixa branca ()	Caixa preta ()
Responsável(is)	Programador(es) ou equipe de testes

5.4 - Tempo de Resposta
Para teste de funcionalidade. Aqui deve-se verificar se o tempo de respostas das ações do programa são consideradas aceitáveis.


Objetivo	Avaliar o tempo de resposta
Técnica:	( ) manual	( ) automática
Estágio do teste	Integração ( )	Sistema ( )	Unidade ( )	Aceitação ( )
Abordagem do teste	Caixa branca ( )	Caixa preta ( )
Responsável(is)	Programador(es) ou equipe de testes


6 - Ambiente de teste - Software e Hardware / Informar o endereço da aplicação versão 


6.1 - Ferramenta de teste / Inserir nome das ferramentas 
Manual: Testlink 

Automação: Cypress


 7 - Cronograma


Tipo de teste
Duração
Data de início
Data de término
Planejar teste


dd/mm/aaaa
dd/mm/aaaa
Projetar teste


dd/mm/aaaa
dd/mm/aaaa
Implementar teste


dd/mm/aaaa
dd/mm/aaaa
Executar teste


dd/mm/aaaa
dd/mm/aaaa
Avaliar teste


dd/mm/aaaa
