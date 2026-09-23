# Construção de Página Web com HTML e CSS

## Aluna

Nome: KÉLEN CAMARGO DOS SANTOS  
Matrícula: 1102339  

Trabalho desenvolvido para a disciplina de Front-End.

---

## Página de referência

Página inicial de pesquisa do Google.
https://www.google.com/

O objetivo do projeto foi reproduzir visualmente a página inicial de pesquisa do Google utilizando HTML semântico e CSS, sem copiar o código-fonte da página original.

---

# Checklist dos requisitos

## 1.1 Estrutura HTML semântica e acessível

- [x] Uso de HTML semântico
- [x] Imagem com atributo `alt`
- [x] Formulário funcional
- [x] Campo do formulário associado a um `label`

### Implementação

A página foi estruturada utilizando elementos semânticos como:

- `header`
- `nav`
- `main`
- `section`
- `footer`

O cabeçalho possui uma área de navegação com os links superiores da página.

A área principal foi criada utilizando a tag `main`, contendo uma `section` responsável pela área de pesquisa.

O rodapé utiliza a tag `footer` e contém uma navegação própria.

A imagem da logo possui o atributo:
`alt="Logo do Google"`

O formulário de pesquisa possui um `label` associado ao campo através dos atributos:
`for="pesquisa"` e `id="pesquisa"`

O label foi mantido no HTML por questões de acessibilidade, mas foi ocultado visualmente através do CSS.

O formulário é funcional e envia o termo pesquisado para a busca do Google utilizando:`action="https://www.google.com/search"`e o campo possui:`name="q"`

---

## 1.2 Fidelidade visual à referência

- [x] Organização semelhante à página original
- [x] Cores semelhantes
- [x] Tipografia semelhante
- [x] Espaçamentos e proporções aproximados
- [x] Cabeçalho, conteúdo principal e rodapé reproduzidos

### Análise da página original

A página inicial do Google possui uma estrutura visual simples composta por três grandes regiões:

1. cabeçalho com links de navegação;
2. área principal com logo e formulário de pesquisa;
3. rodapé com país e links institucionais.

Essa estrutura foi reproduzida utilizando elementos semânticos equivalentes no HTML.

Foi utilizada a fonte Arial como aproximação da tipografia apresentada na referência.

As cores, dimensões da caixa de pesquisa, botões, espaçamentos e organização dos elementos foram reproduzidos visualmente com CSS.

Pequenas diferenças visuais podem existir devido à implementação acadêmica e à necessidade de utilizar apenas os conhecimentos abordados na disciplina.

---

## 1.3 CSS: seletores, box model e variáveis

- [x] Variáveis CSS
- [x] Seletor de elemento
- [x] Seletor de classe
- [x] Seletor descendente
- [x] Pseudo-classe
- [x] Aplicação de box model

### Variáveis CSS

Foram utilizadas variáveis no seletor `:root` para armazenar cores e outras propriedades reutilizadas no projeto.

Exemplos:

```css
--cor-texto: #202124;
--cor-borda: #dfe1e5;
--cor-fundo: #ffffff;
--cor-login: #0b57d0;

### Tipos de seletores utilizados

- Seletor de elemento:

body {
}

- Seletor de classe:

.campo-pesquisa {
}

- Seletor descendente:

.acoes-pesquisa button {
}

- Pseudo-classe:

.campo-pesquisa:hover {
}

.campo-pesquisa:focus {
}

### Box model

O projeto utiliza propriedades como:

- margin
- padding
- border
- width
- height

---

## 1.4 Responsividade: Flexbox, Grid e Mobile First

 - CSS desenvolvido em Mobile First - ok

 - Uso de Flexbox - ok

 - Uso de media query com min-width - ok

 - Funcionamento em celular - ok

 - Funcionamento em desktop - ok

 ### Implementação

O CSS principal foi desenvolvido inicialmente para telas menores,
seguindo a abordagem Mobile First.

Foi utilizado Flexbox para organizar o cabeçalho, a área principal,
o formulário, os botões e o rodapé.

Para telas maiores foi utilizada a seguinte media query:

@media (min-width: 768px) {
}

No celular, os elementos são organizados para ocupar melhor o espaço
disponível. Em telas maiores, alguns elementos passam a ser organizados
horizontalmente.

---

## 1.5 Personalização e originalidade

- Personalização própria adicionada - ok

Foi adicionada ao rodapé uma identificação informando que a página é
um clone acadêmico desenvolvido para a disciplina de Front-End.

Esse elemento não existe na página original e foi incluído especificamente
para atender ao requisito de personalização do trabalho.

### Comparação visual

Página original


Página desenvolvida


## Histórico de desenvolvimento

- Criação da estrutura inicial do projeto

- Desenvolvimento da estrutura HTML semântica

- Ajustes de acessibilidade

- Criação dos estilos base

- Desenvolvimento em abordagem Mobile First

- Implementação da responsividade para telas maiores

- Ajustes de fidelidade visual

- Inclusão da personalização do projeto