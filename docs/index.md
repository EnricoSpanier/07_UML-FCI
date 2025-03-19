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
 * Funcionais:
   
| ID | RF | Descrição |
|---|---|---|
| RF - 01 | Autenticação de Operadores | O sistema deve requisitar a autenticação via biometria e autenticação multifator(MFA)|
| RF - 02 | Controle de Frotas | O sistema deve ser capaz de controlar as frotas de forma autônoma e remoto| 
| RF - 03 | Interface de Comando e Controle | Interface gráfica com telemetria, status e capaz de receber comandos para os drones |
| RF - 04 | Navegação Autônoma | Os drones devem ser capazes de realizar missões sem intervenção humana, utilizando os sensores como LIDAR, GPS e visão computacional |
| RF - 05 | Comunicação Segura | A comunicação entre drones e entre drones e o sistema deve ser com criptografia ponta a ponta |
| RF - 06 | Registro de Missões | O sistema deve armazenar dados de cada missão incluindo **LOGS** detalhados |
| RF - 07 | Monitoramento em Tempo Real | Os drones devem enviar ao sistema dados de telemetria, status e eventos críticos continuamente ao sistema central |
| RF - 08 | Gerenciamento de Atualizações | O sistema deve transmitir atualizações de firewall dos drones remotamente garantindo segurança e conformidade operacional  |
| RF - 09 | Failober e Recuperação | Em caso de falhas o sistema deve redirecionar automaticamente as operações para um servidor de backup |
| RF - 10 | Auditoria de eventos | Todos os acessos e comandos devem ser armazenados em **LOGS** de auditoria imutáveis para fins de segurança e conformidades |
    
 * Não Funcionais:
    - Controle remoto e automato de drones

         - pre(Sensoriamento de ambiente via LIDAR, câmeras e GPS)
    - Dashboard em tempo real com telemetria
    - Protocos para comunicação segura e em tempo real com os drones

         - pre(Criptografia de ponta e assinaturas digitais)
    - Criptografia de ponta e assinaturas digitais 
    - Banco de dados noSQL distribuido para dados em tempo real
    - Logs de missão realizadas e eventos críticos
    - Detecção e evasão de ameaças em tempo real

         - pre(Sensoriamento de ambiente via LIDAR, câmeras e GPS)

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
