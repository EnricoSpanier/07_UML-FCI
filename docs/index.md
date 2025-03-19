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
| **RF - 01** | Autenticação de Operadores | O sistema deve requisitar a autenticação via biometria e autenticação multifator(MFA)|
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

*&lt;Diagrama para visualizer as pessoas das áreas de negócios e de desenvolvimento de uma organização para entender o processo e comportamento.&gt;*

# Diagrama de Casos de Uso

*&lt;Diagrama para visualizar o comportamento dos atores&gt;*

# Descrição dos Casos de Uso

*&lt;Descrição do comportamento entre os atores/resquisitos&gt;*

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
