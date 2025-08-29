# Bug: Seletor de tipo cliente invertido

## Problema
Quando clico em "individual", automaticamente seleciona "Business" em vez de individual.

## Como reproduzir
1. Abrir o formulário
2. Ir na seção "Client type"
3. Clicar na opção "individual"
4. Observar que a opção "Business" fica selecionada

## O que acontece
- Clico em "individual"
- Sistema seleciona "Business"  
- Não consigo selecionar "individual"
- Dados ficam errados

## O que deveria acontecer
- Clicar em "individual" deveria selecionar "individual"
- Clicar em "Business" deveria selecionar "Business"
- Cada opção deveria funcionar corretamente

## Gravidade
**Grave** - Usuários não conseguem selecionar o tipo correto, dados ficam incorretos

## Imagens do bug
![Seletor invertido](../Imagens/bug-cliente.mp4)
