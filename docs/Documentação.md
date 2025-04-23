<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Nome do Projeto&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Enrico Minto Spanier
* Guilherme Vecchi Bonnotti Freitas Silveira


# Descrição do Projeto

*&lt;Introdução do projeto&gt;*

# Análise de Requisitos Funcionais e Não-Funcionais
*&lt;Descrição dos requisitos&gt;*
   
## Funcionais:
 
|  ID | RF | Descrição |
|---|---|---|
| **RF - 01** | Autenticação de Usuário | O sistema deve requisitar a autenticação via biometria e autenticação multifator(MFA)|
| **RF - 02** | Controle de Frotas | O sistema deve ser capaz de controlar as frotas de forma autônoma e remoto| 
| **RF - 03** | Interface de Comando e Controle | Interface gráfica com telemetria, status e capaz de receber comandos para os drones |
| **RF - 04** | Navegação Autônoma | Os drones devem ser capazes de realizar missões sem intervenção humana, utilizando os sensores como LIDAR, GPS e visão computacional |
| **RF - 05** | Comunicação Segura | A comunicação entre drones e entre drones e o sistema deve ser com criptografia ponta a ponta |
| **RF - 06** | Registro de Missões | O sistema deve armazenar dados de cada missão incluindo **LOGS** detalhados |
| **RF - 07** | Monitoramento em Tempo Real | Os drones devem enviar ao sistema dados de telemetria, status e eventos críticos continuamente ao sistema central |
| **RF - 08** | Gerenciamento de Atualizações | O sistema deve transmitir atualizações de firewall dos drones remotamente garantindo segurança e conformidade operacional  |
| **RF - 09** | Failober e Recuperação | Em caso de falhas o sistema deve redirecionar automaticamente as operações para um servidor de backup |
| **RF - 10** | Auditoria de eventos | Todos os acessos e comandos devem ser armazenados em **LOGS** de auditoria imutáveis para fins de segurança e conformidades |


## Não Funcionais:

| ID | RNF | Descrição |
|---|---|---|
| **RNF - 01** | Segurança | O sistema deve implementar criptografia AES-256 para armazenamento de dados e TLS para comunicação |
| **RNF - 02** | Desempenho | A latência da comunicação entre um drone e o sistema não pode ultrapassar 50ms em condições normais | 
| **RNF - 03** | Disponibilidade | O sistema deve estar disponível 24/7, com 99,9% de uptime, garantindo operação contínua em missões críticas |
| **RNF - 04** |  Escalabilidade | A arquitetura deve permitir a adição de novos drones e servidores sem comprometer a performance e segurança |
| **RNF - 05** | Armazenamento Distribuído | O banco de dados deve ser replicado geograficamente para garantir redundância e integridade dos dados |
| **RNF - 06** | Conformidade | O sistema deve atender a padrões de segurança como ISO 27001 e NIST 800-53 para segurança cibernética |
| **RNF - 07** | Resiliência | O sistema deve garantir recuperação automática de falhas em até 05 segundos sem perda de dados |
| **RNF - 08** | Tolerância a Falhas | A arquitetura deve suportar balanceamento de carga e replicação para evitar pontos únicos de falha |
| **RNF - 09** | Eficiência Energética | Os drones devem otimizar o consumo de bateria utilizando algoritmos de inteligência artificial para gestão de energia |
| **RNF - 10** |  Log e Auditoria | Os logs devem ser armazenados por no mínimo 05 anos e protegidos contra alteração ou exclusão |

# Diagrama de Atividades

![Drones](https://github.com/user-attachments/assets/f3f30f15-5f23-4336-a02e-41587ab17c2f)

# Diagrama de Casos de Uso

![CasosdeUso](https://github.com/user-attachments/assets/f8d16c8f-9793-48e0-b8a9-a1aac67ba923)

# Descrição dos Casos de Uso

| **Nome do Caso de Uso** | **Visualizar Log** |
|---|---|
| ***Ator Principal*** | Administrador |
| ***Ator Secundário*** | Banco de Dados |
| ***Resumo*** | Esse caso de uso descreve as etapas percorridas para o acesso do log no sistema Falcão sombrio |
| ***Pré-Condição*** | O usuário deve ter logado e autenticado seu acesso, alem de ter o nivel de acesso nescessário |
| ***Pós Condição*** | Cria um Log sobre a entrada e visualização do Log |
| **Fluxo Principal** | --- |
| ***Ações do Ator*** | ***Ações do Sistema*** |
| 1. Usuário entra no Falcão sombrio|  |
|  | 2. Sistema pede credenciais |
| 3. Usuário insere as credenciais |  |
|  | 4. Sistema valida e pede autenticação biométrica e multifatorial |
| 5. Usuário faz a biometria e insere o código multifatorial |  | 
|  | 6. Sistema valida a biometria e código e exibe menu de opções |
| 7. Usuário seleciona a opção de visualizar Logs |  |
|  |8. Sistema verifica valida nível de acesso e exibe todos os Logs |
| 9. Usuário seleciona o Log desejado |  |
|  | 10. Sistema exibe todos os detalhes e dados do Log acessado |
| 11. Usuário faz Logout ou volta ao menu de opções |  |
|  | 12. Sistema cria um log sobre o acesso e fecha ou reexibe o menu de opções|
| **Fluxo Alternativo** | --- |
|  | 2. Sistema pede credenciais |
| 3. Usuário insere as credenciais |  |
|  | 4. Sistema não reconhece |
| 5. Usuário reenvia credenciais |  |
|  | 6. Sistema não reconhece e solicita que chame o suporte |
|  | 7. Sistema cria um Log sobre a tentativa e fecha |
| **Fluxo de Exceção** | --- |
| 1. Usuário tenta acessar Logs |  |
|  | 2. Sistema confirma nível de acesso insuficiente e nega o acesso, informando o Usuário o motivo e gera um Log sobre a tentativa |
|  | 3. Sistema se mantem no menu de opções|
| **Restrições e Validações:** | 1. Usuário deve ter acesso ao Falcão Sombrio|
| |2. Usuário deve ter ao menos nível de acesso de Administrador ou ser um membro/empresa com acesso para auditoria |


| **Nome do Caso de Uso** | **Ver catalogo de drones** |
|---|---|
| ***Ator Principal*** | Usuario |
| ***Ator Secundário*** | Banco de Dados |
| ***Resumo*** | Esse caso de uso descreve as etapas percorridas para ver catalogo de drones podendo se conectar aos drones futuramente |
| ***Pré-Condição*** | O usuario deve ter logado e autenticado seu acesso |
| ***Pós Condição*** | Cria um log sobre a visualização e pode inicias o Conectar com drone(s) |
| **Fluxo Principal** | --- |
| ***Ações do Ator*** | ***Ações do Sistema*** |
| 1. Usuário entra no Falcão sombrio |    |
|  | 2. Sistema pede credenciais  |
| 3. Usuário insere as credenciais |    |
|  | 4. Sistema valida e pede autenticação biométrica e multifatorial |
| 5. Usuário faz a biometria e insere o código multifatorial |  |
|  | 6. Sistema valida a biometria e código e exibe menu de opções |
| 7. Usuário seleciona a opção de ver catalogo de drones |  |
|  | 8. Sistema verifica valida nível de acesso e exibe todos os drones |
| 9. Usuário seleciona o drone ou conjunto de drones desejado(s)  |  |
|  | 10.  Sistema exibe todos os detalhes e dados do(s) drone(s) acessado(s) |
| 11. Usuário faz Logout ou volta ao menu de opções |   |
|  | 12.  Sistema cria um log sobre o acesso e fecha ou reexibe o menu de opções |
| **Fluxo Alternativo** | --- |
| 11. Usuário se conecta com drone(s) selecionado(s) |   |
|  | 12.  Sistema cria log e inicia o caso de Conectar com drone(s) |
| **Fluxo de Exceção** | --- |
| 1. | |
|  | 2. |
| **Restrições e Validações:** | 1. Usuário deve ter acesso ao Falcão Sombrio |
|  | 2. Usuário deve ter nível de acesso operador ou superior |


| **Nome do Caso de Uso** | **Criar/Atualizar Missões** |
|---|---|
| ***Ator Principal*** | Usuário |
| ***Ator Secundário*** | Banco de Dados |
| ***Resumo*** | Esse caso de uso descreve as etapas percorridas para atualiar ou criar novas missões |
| ***Pré-Condição*** | Estar logado no sistema Falcão Sombrio |
| ***Pós Condição*** | Criar Log de qualquer alteração  |
| **Fluxo Principal** |  |
| ***Ações do Ator*** | ***Ações do Sistema*** |
| 1. Usuário entra no Falcão sombrio|  |
|  | 2. Sistema pede credenciais |
| 3. Usuário insere as credenciais |  |
|  | 4. Sistema valida e pede autenticação biométrica e multifatorial |
| 5. Usuário faz a biometria e insere o código multifatorial |  | 
|  | 6. Sistema valida a biometria e código e exibe menu de opções |
| 7. Usuário seleciona opção de criar/atualizar missão |
|  | 8. Sistema Mostra a lista de missões e a opção de criar nova missão |
| 9. Usuário seleciona criar nova |  |
|  | 10. Sistema exibe a tela de criação de missão na qual irá solicitar as informações da missão |
| 11. Usuário insere todas as informações nescessárias para a missão |  |
|  | 12. Sistema atualiza a lista de missões e volta para a tela da lista das missões |
| 13. Usuário faz Logout ou volta a tela de opções | |
|  | 14. Sistema cria o Log e volta exibe tela de opções ou fecha |
| **Fluxo Alternativo** | --- |
| 9. Usuário escolhe uma missão para atualizar |  |
|  | 10. Sistema exibe as informações sobre a missão selecionada e permite alterações  |
| 11. Usuário altera informações desejadas e salva essas | |
|  | 12. Sistema atualiza as informações e volta a lista de missões e cria um Log sobre as alterações |
| **Fluxo de Exceção** | --- |
| **Restrições e Validações:** | 1. Ter acesso ao sistema Falcão Sombrio  |
|  | 2. Ter nível de acesso de operador ou superior |


| **Nome do Caso de Uso** | **Executar missão** |
|---|---|
| ***Ator Principal*** | Drone |
| ***Ator Secundário*** | Banco de dados |
| ***Resumo*** | Esse caso de uso descreve as etapas percorridas para executar a(s) missão(ões) |
| ***Pré-Condição*** | Ter uma missão |
| ***Pós Condição*** | Cria um log sobre o percurso da(s) missão(ões) |
| **Fluxo Principal** | --- |
| ***Ações do Ator*** | ***Ações do Sistema*** |
|  | 1. Sistema envia o percurso da missão |
| 2. Drone envia os dados de sensores enquanto segue o percurso  |  |
|  | 3.Sistema muda o percurso de acordo com a necessidade analizada nos dados  |
| 4.Drone ao terminar o percuso retorna para a base |  |
|  | 5. Sistema deixa o drone em estado de espera |
|  | 4. Sistema cria um log sobre o percurso de ações tomas e fecha |
| **Fluxo Alternativo** | --- |
|  | 3. Sistema não recebe os dados e tenta reconexão |
| 4. Drone executa o percurso previo até nova atualização |  |
| **Fluxo de Exceção** | --- |
| 1. | |
| | 2. |
| **Restrições e Validações:** | 1. Drone(s) disponivel(ies) |
|  | 2.Ter missão valida | 
|  | 3. Usuário ter nível de acesso de operador ou superior |


| **Nome do Caso de Uso** | **Acessar Missões** |
|---|---|
| ***Ator Principal*** | Usuário |
| ***Ator Secundário*** | Banco de Dados |
| ***Resumo*** | Esse caso de uso descreve as etapas percorridas para acessar as missões salvas no sistema |
| ***Pré-Condição*** | Estar logado no sistema e ter ao menos uma missão criada |
| ***Pós Condição*** | Cria um Log sobre as ações tomadas |
| **Fluxo Principal** | --- |
| ***Ações do Ator*** | ***Ações do Sistema*** |
| 1. Usuário entra no Falcão sombrio|  |
|  | 2. Sistema pede credenciais |
| 3. Usuário insere as credenciais |  |
|  | 4. Sistema valida e pede autenticação biométrica e multifatorial |
| 5. Usuário faz a biometria e insere o código multifatorial |  | 
|  | 6. Sistema valida a biometria e código e exibe menu de opções |
| 7. Usuário seleciona opção de acessar missão |  |
|  | 8. Sistema exibe o catálogo de missões ao usuário |
| 9. Usuário seleciona missão que deseja acessar |  |
|  | 10. Sistema exibe as informações da missão selecionada |
| 11. Usuário seleciona que quer iniciar ela |  |
|  | 12. Sistema direciona o Usuário para a tela de executar missão |
|  | 13. Sistema salva os Logs
| **Fluxo Alternativo** | --- |
| 11. Usuário seleciona que quer voltar ao menu principal | |
|  | 12. Sistema Reexibe o menu principal  |
| **Fluxo de Exceção** | --- |
| **Restrições e Validações:** | 1. Usuário ter nível de acesso de operador ou superior |


# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
