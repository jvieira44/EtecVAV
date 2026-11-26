# 📓Atividade – WAI-ARIA (Web Accessibility Initiative – Accessible Rich Internet Applications)

## Questão 1 – O que é o WAI-ARIA e sua principal função no desenvolvimento de páginas na web?
**R: WAI-ARIA** (*Web Accessibility Initiative – Accessible Rich Internet Applications*) é um conjunto de atributos que torna o uso de páginas web por pessoas com deficiência mais acessível, fornecendo informações para que tecnologias assistivas como leitores de tela, digitação por voz, navegação por teclado e entre outros recursos de acessibilidade, possam interpretar os elementos da página, assim tornando a navegação mais facilitada para os usuários destinados a esta utilidade (normalmente deficientes físicos, visuais e outras limitações).

---
## Questão 2 – Analisando um trecho de código

#### a) Qual é a função do atributo `aria-controls`?

**R:** **aria-controls** identifica qual o elemento da página é controlado pelo botão, neste caso, o menu com id "menuPrincipal".

#### b) O que informa o atributo `aria-expanded`?

**R:** **aria-expanded** informa se o elemento controlado está expandido, aberto ou fechado. No codigo por exemplo, o menu está fechado.

#### c) Qual é a importância do atributo `aria-label` para usuários que utilizam leitores de tela?

**R:** **aria-label** fornece uma descrição acessível do botão para leitores de tela, ajudando usuários com deficiência visual a entender sua função.

---
## Questão 3 – Explique por que o WAI-ARIA não substitui o HTML semântico (e uma situação que seu uso melhora a acessibilidade de uma página web)

**R:** O HTML semântico por padrão dá significado aos elementos, compatibilidade com navegação por teclado e suporte para tecnologias assistivas. O **WAI-ARIA** deve ser utilizado apenas para complementar esses recursos quando o HTML não servir as necessidades, principalmente em interfaces e interações mais complexas.
Um exemplo é uma janela que pede a confirmação para apagar um arquivo, o **WAI-ARIA** avisa o leitor de tela que essa janela foi aberta e que existem os botões de confirmar e cancelar, assim a pessoa consegue usar a página com mais facilidade.
