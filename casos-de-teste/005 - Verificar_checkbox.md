# Casos de Teste - CT005: Verificar a checkbox de aceite de termos do formulário

**Objetivo:** Testar se ao marcar a opção "I agree to the Terms and Conditions" o checkbox é marcado corretamente para prosseguir com o envio do formulário

**Pré-condições:**
- Acessar o site: [Formulário](https://qa-training.sbx.devsquad.app/).

**Passos:**
1. Abrir o site informado
2. Preencher todos os campos obrigatórios
3. Marcar a checkbox “I agree to the Terms and Conditions”
4. Clicar no botão de Submit


**Resultado esperado:**  A checkbox deve aparecer como marcada e o sistema deve aceitar o envio e criar a conta, caso a checkbox não for marcada o envio não deve ser permitido.


**Resultado obtido:** A checkbox não é marcada corretamente mas o sistema aceita o envio para a criação do formulário.

**Status:** Falhou
