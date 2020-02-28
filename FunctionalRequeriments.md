## ARQUITETURA 

**CÓDIGO** <br>
  - Arquitetura em microserviços
  - Interação via API 
  - Módulos 
    - Cadastro
    - Acesso
    - Atualizações
    - Visualizações
    - Algoritmos
<br>

**BANCO DE DADOS**
  - Banco de dados não estruturado - MongoDB
  
<br>

## BANCO DE DADOS

<br>
<br>

## CÓDIGO 

<br>


## MÓDULO DE CADASTRO (Inclusão / alteração)

**CONTA**
 - Nr telefone
 - Detalhes
   - . 

<br>

**ROTA** <br>
  - Rota no transporte público   
     - Local de entrada no sistema de transporte publico <br>
     - Local de saída do sistema de transporte público <br>
     - Meio de transporte público <br>
     - Frequência esperada de utilização semanal 
  - **Detalhes** 
     - Marcação do local (busca + PIN)
     - Opções de meio de transporte (ônibus/trem/metro)
     - Opções de frequência semanal (7, 6, 5, 4, 3, 2, 1)  
<br>

**ESTADO DE SAÚDE**  <br>
  - Estado de saúde atual frente ao COVID-19  <br>
  - Detalhes
     - Opções de sintomas (Sem sintomas / Com sintomas, mas não confirmado / Confirmado)
<br>

**FREQUÊNCIA DE ATUALIZAÇÃO**
  - Frequência de recebimento via push
  - Detalhes
     - Opções de frequência de recebimento (Diária / Semanal / Mensal)
<br>

## MODULO DE ATUALIZAÇÃO
  - Notificação (push) para atualização da utilização das rotas.
  - Detalhes
     - Atualiza frequência real de utilização por rota cadastrada;
<br>

## MÓDULO DE VISUALIZAÇÕES 

**MAPAS DE CALOR (heat maps)**
  - Rotas cadastradas 
  - Todas a rotas
  - **Detalhes**
     - Distinção de cores por nível de evolução do potencial de transmissão. 
     - Mapa local alcance global (pesquisa por palavra chave)

<br>

**MAPAS PARA ESPECIALISTAS**
  - Histórico de evolução por rota
  - Detalhes
     - Gráfico com evolução do potencial de transmissão por rota. 
<br>

## MÓDULO DE ALGORITMOS

**Cálculo do potencial de transmissão da rota (TP)**
  - Detalhes
     - Versionamento do TP 

<br>



