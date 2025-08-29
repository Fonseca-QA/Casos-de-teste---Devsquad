# Casos de Teste - CT003: Formulário de cadastro com dados faltando

**Objetivo:** Testar se o sistema permite cadastro sem preencher campos importantes

**Pré-condições:**
- Acessar o site: [text](https://qa-training.sbx.devsquad.app/).

**Passos:**
1. Abrir o site informado
2. Não preencher "Full Name": "      "
3. Preencher "Email Address: "joaoteste@hotmail.com"  
4. Preencher DDI + "Phone Number": "55", "22999888777"
5. Escolher "Date of birth": "24/09/1998"
6. Preencher "Address": "Rua dos testes, 123"
7. Escolher "Country of Residence": "Brazil"
8. Escolher "State": "Rio de Janeiro"
9. Escolher "Client type": "individual"
10. Preencher "Annual Income": "100000"
11. Marcar os termos em "I Agree to the Terms and Conditions
12. Clicar em "Submit"

**Resultado esperado:** Formulário não é enviado e aparece uma mensagem de erro "The name field is required."

**Resultado obtido:** Mesmo que o esperado

**Status:** Passou

## Imagens do teste
![CT](../Imagens/erro-nome.png)
