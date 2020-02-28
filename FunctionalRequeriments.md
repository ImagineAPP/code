## ARQUITETURA 

**CÓDIGO** <br>
  - Arquitetura em microserviços
  - Interação via API entre módulos e algoritmos 
  - Algoritmos 
  - Módulos 
    - Cadastro
    - Acesso
    - Atualizações
    - Visualizações
<br>

**BANCO DE DADOS**
  - Banco de dados não estruturado - MongoDB
  


<br>

## BANCO DE DADOS

**TABELA DE USUÁRIOS**
  - ID / Telefone
  - Status
  - Frequência atualização
<br>

**TABELA DE ROTAS**
  - Local início
  - Local fim
  - Transporte 
  - Frequência
  - Usuário



<br>

## CÓDIGO 

<br>

## MÓDULO DE CADASTRO (Inclusão / alteração)

**CONTA**
  - Nr telefone /ID 
  - **DETALHES**
    - . 
<br>

**ROTA** <br>
  - Rota no transporte público   
     - Local de início da rota
     - Local de fim da rota
     - Meio de transporte público
     - Frequência esperada de utilização semanal 
  - **DETALHES** 
     - Marcação do local (busca + PIN)
     - Opções de meio de transporte (ônibus/trem/metro)
     - Opções de frequência semanal (7, 6, 5, 4, 3, 2, 1)  
<br>

**ESTADO DE SAÚDE**  <br>
  - Estado de saúde atual frente ao COVID-19 
  - **DETALHES**
     - Opções de sintomas (Sem sintomas / Com sintomas, mas não confirmado / Confirmado)
<br>

**FREQUÊNCIA DE ATUALIZAÇÃO**
  - Frequência de recebimento via push
  - **DETALHES**
     - Opções de frequência de recebimento (Diária / Semanal / Mensal)
<br>

## MÓDULO DE NOTIFICAÇÕES

**ATUALIZAÇÃO DA UTILIZAÇÃO**
  - **MENU**
     - Notificação (push) para atualização da utilização das rotas.
  - **DETALHES**
     - Atualiza frequência real de utilização por rota cadastrada;
<br>

## MÓDULO DE VISUALIZAÇÕES 

**MAPAS DE CALOR (heat maps)**
  - **MENU**
     - Rotas cadastradas 
     - Todas a rotas
  - **DETALHES**
     - Distinção de cores por nível de evolução do potencial de transmissão. 
     - Mapa local alcance global (pesquisa por palavra chave)

<br>

**MAPAS PARA ESPECIALISTAS**
  - **MENU**
     - Histórico de evolução por rota
  - **DETALHES**
     - Gráfico com evolução do potencial de transmissão por rota. 
<br>

## MÓDULO DE ALGORITMOS

**Cálculo do potencial de transmissão da rota (TP)**
  - **DETALHES**
     - Versionamento do TP 

<br>



