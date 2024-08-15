# PROJETO INTEGRADOR: GERENCIAMENTO DE UMA LOCADORA DE VEICULOS 

  

Professor: [Marco André Mendes](github.com/marcoandre)

  

EQUIPE/ALUNOS: 

  
  [RIAN SCHMETCKA](github.com/Rian-2INFO3)

- MATHEUS RAFAEL 

- DAVI SILVEIRA DA CUNHA 

  

# <h1 align="center">SITUAÇÃO PROBLEMA</h1> 

  

    A locadora recebe atualmente veículos de Belo Horizonte onde esse fornecedor é essencial para seu funcionamento, conta alguns com funcionários, incluindo o gerente, quatro atendentes ficarão no pátio, esperando os clientes já os recepcionistas estarão nas mesas para a verificação dos clientes caso queiram alugar um veículo ou verificar qualquer ato pendente  durante todo o período são alugados vários carros para as pessoas somente maiores de dezoito anos contudo, há um grande problema de gestão de locar esses veículos bom por não possuir um sistema capaz de guardar essas informações e gerenciar toda movimentação de alugar os veículos e sua devolução no sistema. 

  

O gerente por sua vez mantém o controle dos veículos alugados e Disponíveis, na planilha de alocação, poderia incluir em um futuro software fórmulas que calculam automaticamente o número de carros alocados e para alugação verificando o número de veículos disponíveis no acervo, com base nos registros disponíveis. 

Veículo danificado durante o aluguel: Um cliente devolve um veículo com danos significativos que não estavam presentes antes do aluguel. Como lidar com a situação e determinar a responsabilidade 

  

Por fim, a locadora poderia criar relatórios simples em uma planilha, como um relatório de veículos em aberto e um relatório de veículos mais alugados, que poderia ajudar na tomada de decisões sobre quais carros adquirir para aumentar o acervo. Essa solução é simples, fácil de implementar e não requer investimentos adicionais em equipamentos ou software. No entanto, é importante lembrar que, como se trata de um sistema baseado em planilhas eletrônicas, a sua capacidade de gerenciamento pode ser limitada quando o acervo e o número de usuários aumentarem. 

  

# <h1 align="center">DESCRIÇÃO DA PROPOSTA</h1> 

  

<h1> Proposta de Solução:</h1>  

  

A fim de resolver os problemas de gestão enfrentados pela locadora de veículos, proponho a implementação de um sistema de gerenciamento informatizado que irá automatizar e otimizar os processos de locação e devolução de veículos. Este sistema terá os seguintes componentes principais: 

  

Sistema de Gerenciamento de Locação e Devolução de Veículos:Desenvolvimento de um software personalizado que permitirá o registro de todos os veículos disponíveis para locação, detalhes dos clientes, datas de locação e devolução, além de registros de danos e condições dos veículos no momento da devolução. 

  

Integração com Planilhas de Controle Atuais: Integração do sistema de gerenciamento com as planilhas de alocação atualmente utilizadas pelo gerente, permitindo uma transição suave para o novo sistema e garantindo que as informações essenciais sejam preservadas. 

  

Automatização de Cálculos de Disponibilidade de Veículos: Implementação de fórmulas automatizadas no software que calcularão automaticamente o número de veículos disponíveis para locação com base nos registros disponíveis, fornecendo ao gerente uma visão em tempo real da disponibilidade da frota. 

  

Registro e Acompanhamento de Danos aos Veículos: Incorporação de funcionalidades no sistema para registrar e acompanhar quaisquer danos aos veículos durante o período de locação, facilitando a determinação da responsabilidade e o processo de reparo ou substituição. 

  

Geração de Relatórios Gerenciais: Desenvolvimento de recursos de geração de relatórios no sistema, incluindo relatórios de veículos em aberto, veículos mais alugados e análises de desempenho da frota. Esses relatórios fornecerão insights valiosos para a tomada de decisões estratégicas sobre aquisição e gestão da frota. 
  

Esta proposta visa resolver os problemas de gestão enfrentados pela locadora, melhorar a eficiência operacional e proporcionar uma experiência aprimorada tanto para os clientes quanto para os funcionários. Além disso, a integração com as planilhas existentes e a simplicidade de implementação garantem uma transição suave para o novo sistema, sem a necessidade de investimentos adicionais em equipamentos ou software complexo. 

  

<h1 align="center">REGRAS DE NEGÓCIO</h1> 

  

- **RN01:** Para alugar qualquer carro na locadora o usuário deverá estar registrado. 

- **RN02:** O atendente deverá realizar o cadastro de usuário. 

- **RN03:** Os carros no acervo serão cadastrados pela locadora. 

- **RN04:** Cada usuário poderá alugar por diária ou mensal. 

- **RN05:** Cada carro poderá ficar por mensal a diária depende o que usuário escolher. 

- **RN06:** Usuários com deposito em atraso não poderão fazer novos pedidos para alugar. 

- **RN07:** Cada usuário que quiser fazer uma RENOVAÇÃO de um veículo deverá ser consultado para ver se não há pendencia. 

- **RN08:** Alocação de carros em atraso na devolução não poderá ser renovados. 

- **RN09:** Cada usuário que atrasar a parcela ou o dia da entrega será multado/punido+. 

- **RN10:** O atendente fará renovação dos carros alugados para o mesmo período da loção anterior. 

- **RN11:** O atendente irá verificar se o carro está disponível no sistema. 

- **RN12:** O atendente fará reserva dos carros solicitados que não estão alugados no momento. 

- **RN13:** O atendente fará registro de indicações de carros que não constam no acervo, para serem adquiridos. 

- **RN14:**O atendente fará o relatório dos veículos mais alugados, os usuários com carros em atraso de entrega, os usuários que fizeram renovações para alugar, as reservas realizadas e carros para serem adicionados ao acervo. 

- **RN15:** Quando extravio do veículo a locadora deverá ser assinada junto ao proprietário que alugou o veículo. 

  

- # <h1 align="center">REQUISITOS FUNCIONAIS</h1> 

  

## ENTRADA 

  

- **RF001: Registro de Usuário:** O sistema deve permitir o cadastro de usuários no sistema. 

  - **Dados Necessários:** Nome, Email, Telefone, CPF, Endereço 

  - **Usuários:** Atendente. 

- **RF002: Cadastro de funcionário:** O sistema deve permitir o cadastro de funcionários no sistema 

  - **Dados Necessários:** Nome, Email, Telefone, CPF e senha. 

  - **Usuários:** Administrador 

- **RF003: Cadastro de Carros:** O sistema deve permitir verificar se há pendências para a validação de alugar ou devoluções de veículos. 

  - **Dados Necessários:** Nome, Email, telefone, CPF, Endereço 

  - **Usuários:** Atendente 

  

## PROCESSAMENTO 

  

RF004 - Autenticação de usuário: tem como propósito autenticar o acesso ao sistema, verificando se o usuário pode acessá-lo e, caso possa, o direcionando para a página principal de seu perfil de acesso. 

Dados necessários: login, senha, nível de permissão. 

Usuários: todos os níveis de usuário. 

  

RF005 - Login: O sistema deve permitir a autenticação de Dados Necessários: Email, Senha, Usuários: Administrador/Atendente/ 

  

RF006:Empréstimo: O sistema deve permitir verificar se há pendências para a validação de Locação ou devoluções, Dados Necessários: Nome, Email, telefone, CPF, Endereço Usuários: Administrador/Atendente 

RF007:Devolução: O sistema deve permitir verificar se há pendências para a validação de Locação ou devoluções, Dados Necessários: Nome, Email, telefone, CPF, Endereço Usuários: Administrador/Atendente 

  

RF008: Multa: O sistema deve permitir verificar se há pendências para a validação de Locação ou devoluções, Dados Necessários: Nome, Email, telefone, CPF, Endereço Usuários: Administrador/Atendente 

  

## SAÍDA 

  

RF009: Relatório de Empréstimo: O sistema deve emitir relatórios de Locação de veículos e quantidade alugada. Dados Necessários: data inicial e data final. Usuários: Administrador/Atendente 

  

RF010: Relatório de atrasados: O sistema deve permitir emitir os relatórios de empréstimos de carros atrasados e quantidade alugada, Dados Necessários: data inicial, data final Usuários: Administrador/Atendente 

  

RF011: Relatório de Clientes: O sistema deve permitir emitir os relatórios de clientes fazendo a verificação de pendências para a validação de locação ou devoluções, e Muitas Dados Necessários: CPF Usuários: Administrador/Atendente 

 
