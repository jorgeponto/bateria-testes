# Formulários

- [H44: Utilização de elementos label para associar etiquetas de texto aos controlos de formulário](#h44-utilização-de-elementos-label-para-associar-etiquetas-de-texto-aos-controlos-de-formulário)

## H44: Utilização de elementos label para associar etiquetas de texto aos controlos de formulário

## Procedimento a efetuar

- For all input elements of type text, file or password, for all textareas and for all select elements in the Web page:
  1) Check that there is a label element that identifies the purpose of the control before the input, textarea, or select element
  2) Check that the for attribute of the label element matches the id of the input, textarea, or select element
  3) Check that the label element is visible.
- For all input elements of type checkbox or radio in the Web page:
  1) Check that there is a label element that identifies the purpose of the control after the input element
  2) Check that the for attribute of the label element matches the id of the input element
  3) Check that the label element is visible.
- Resultados esperados
  - Verifique que #1 e #2 são verdadeiros (CS 1.1.1 (A), CS 1.3.1 (A)). Para o CS 3.3.2 (A), verifique se o #3 também é verdadeiro.
