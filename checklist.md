### Checklist para Estilizar um Site

1. **Configurações Iniciais**
   - [ ] Crie um arquivo CSS separado (`styles.css`).
   - [ ] Conecte o arquivo CSS ao HTML usando a tag `<link>` no `<head>`.
     ```html
     <link rel="stylesheet" href="styles.css">
     ```
   - [ ] Defina margens e padding padrão (reset CSS ou `*` selector).
     ```css
     * {
       margin: 0;
       padding: 0;
       box-sizing: border-box;
     }
     ```

2. **Definir Tipografia**
   - [ ] Escolha e importe uma fonte do Google Fonts, se desejado.
   - [ ] Defina a fonte padrão do site no `body`.
     ```css
     body {
       font-family: 'Roboto', sans-serif;
       font-size: 16px;
       line-height: 1.6;
     }
     ```
   - [ ] Ajuste o tamanho, peso e estilo dos títulos e parágrafos (`h1`, `h2`, `p`, etc.).

3. **Cores**
   - [ ] Defina a cor de fundo do site.
   - [ ] Escolha cores para texto, links e botões que contrastem bem com o fundo.
     ```css
     body {
       background-color: #f9f9f9;
       color: #333;
     }
     a {
       color: #007BFF;
     }
     ```

4. **Layout Básico**
   - [ ] Crie uma barra de navegação básica com links.
   - [ ] Use Flexbox ou CSS Grid para alinhar elementos de layout.
     ```css
     .navbar {
       display: flex;
       justify-content: space-between;
       background-color: #333;
       padding: 10px;
     }
     ```

5. **Espaçamento (Padding e Margin)**
   - [ ] Aplique `margin` e `padding` para dar espaçamento adequado entre os elementos.
     ```css
     .container {
       padding: 20px;
       margin: 10px 0;
     }
     ```

6. **Imagens e Mídia**
   - [ ] Certifique-se de que as imagens são responsivas.
   - [ ] Ajuste o tamanho e o estilo das imagens conforme necessário.
     ```css
     img {
       max-width: 100%;
       height: auto;
     }
     ```

7. **Botões e Links**
   - [ ] Estilize os botões para torná-los mais chamativos.
   - [ ] Adicione efeitos de `hover` e `active` nos botões e links.
     ```css
     button {
       background-color: #007BFF;
       color: white;
       padding: 10px 20px;
       border-radius: 5px;
       transition: background-color 0.3s ease;
     }
     button:hover {
       background-color: #0056b3;
     }
     ```

8. **Estrutura de Seções**
   - [ ] Crie classes para as diferentes seções do site, como `.header`, `.about`, `.portfolio`, etc.
   - [ ] Aplique estilos distintos para cada seção (cor de fundo, espaçamento, alinhamento de texto).
     ```css
     .header {
       background-color: #333;
       color: white;
       padding: 50px;
       text-align: center;
     }
     ```

9. **Responsividade**
   - [ ] Use media queries para ajustar o layout em diferentes tamanhos de tela (celular, tablet, desktop).
     ```css
     @media (max-width: 768px) {
       body {
         font-size: 14px;
       }
       .navbar {
         flex-direction: column;
       }
     }
     ```

10. **Ajustes Finais**
    - [ ] Verifique se todas as cores e fontes estão consistentes no site.
    - [ ] Teste a responsividade em diferentes dispositivos.
    - [ ] Verifique os efeitos de transição e interatividade (hover, focus, etc.).

### Checklist Resumido:

- [ ] Conectar arquivo CSS ao HTML.
- [ ] Definir tipografia.
- [ ] Definir paleta de cores.
- [ ] Criar layout básico (navegação, rodapé, etc.).
- [ ] Adicionar espaçamento com `padding` e `margin`.
- [ ] Estilizar imagens e garantir que são responsivas.
- [ ] Estilizar botões e links (incluindo efeitos de hover).
- [ ] Aplicar estilos em diferentes seções do site.
- [ ] Tornar o site responsivo com media queries.
- [ ] Realizar ajustes finais e testes de responsividade.

Esse checklist ajuda a manter o processo organizado e cobre os principais aspectos da estilização com CSS.
