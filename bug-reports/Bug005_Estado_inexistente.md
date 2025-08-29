# Bug: Estado inexistente disponível


## Problema
Ao ir para a área de seleção de estado de nascimento, existe um estado chamado "Montes Claros" que não existe, "Montes Claros" é na verdade uma cidade do estado de "Minas Gerais"

## Como reproduzir
1. Abrir o site
2. Ir até a área "State" do formulário
3. Selecionar os estados disponíveis para a escolha
4. Observar que existe a opção de selecionar um estado chamado "Montes Claros"

## O que acontece
- É possível selecionar um estado inexistente na hora de realizar o preenchimento do formulário

## O que deveria acontecer
- Apenas estados que possuem existência verificada deveriam ser possíveis de selecionar

## Gravidade
**Médio** - Não impede cadastro, mas deixa uma opção que não deveria existir disponível, podendo levar a confusão por parte do usuário
