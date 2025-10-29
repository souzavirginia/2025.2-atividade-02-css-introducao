# 2025.2-atividade-02-css-introducao
Avaliação prática sobre introdução a CSS

## Atividade: Formatação CSS do arquivo exemplo.html

Esta atividade tem como objetivo praticar a aplicação de CSS externo e tem como exemplo a estrutura proposta na atividade de [introdução a html](https://github.com/tads-webdesign/2025.2-atividade-01-html-introducao) e no arquivo `exemplo.html`.
Utilize os diferentes tipos de seletores e propriedades básicas do CSS.

### Instruções Gerais
- [x] Faça um fork desse repositório para o professor poder acompanhar;
- [x] No seu repositório da atividade, coloque o link do [vercel](https://vercel.com/) da sua atividade de [introdução a html](https://github.com/tads-webdesign/2025.2-atividade-01-html-introducao);
- [x] Crie um arquivo CSS externo chamado `pg-pessoal.css` no seu repositório da atividade de [introdução a html](https://github.com/tads-webdesign/2025.2-atividade-01-html-introducao);
- [x] Vincule o arquivo CSS `pg-pessoal.css` ao `index.html` usando a tag `<link>` no `<head>` no seu repositório da atividade de [introdução a html](https://github.com/tads-webdesign/2025.2-atividade-01-html-introducao);
- [x] Complete todas as tarefas abaixo aplicando os estilos especificados

---

## Checklist de Tarefas

### 1. Configuração Inicial
- [x] Criar o arquivo `pg-pessoal.css` na raiz do projeto
- [x] Adicionar a tag `<link rel="stylesheet" href="pg-pessoal.css">` no `<head>` do arquivo `index.html`

### 2. Seletor Universal
- [x] Aplicar o seletor universal (`*`) para resetar margens e paddings de todos os elementos
  - `margin: 0;`
  - `padding: 0;`
  - `box-sizing: border-box;`

### 3. Seletores de Elemento - Corpo da Página
- [x] Estilizar o elemento `body`:
  - `font-size: 16px;`
  - `color: #333333;`
  - `text-align: left;`

### 4. Seletores de Elemento - Títulos (h1 a h6)
- [x] Estilizar o elemento `h1`:
  - `font-size: 36px;`
  - `color: #1a1a1a;`
  - `text-align: center;`

- [x] Estilizar o elemento `h2`:
  - `font-size: 28px;`
  - `color: #2c3e50;`
  - `text-align: center;`

- [x] Estilizar o elemento `h3`:
  - `font-size: 24px;`
  - `color: #34495e;`
  - `text-align: left;`

- [ ] Estilizar o elemento `h4`:
  - `font-size: 20px;`
  - `color: #555555;`

- [ ] Estilizar o elemento `h5`:
  - `font-size: 18px;`
  - `color: #666666;`

- [ ] Estilizar o elemento `h6`:
  - `font-size: 16px;`
  - `color: #777777;`

### 5. Seletores de Elemento - Parágrafos e Divs
- [ ] Estilizar o elemento `p`:
  - `font-size: 14px;`
  - `color: #444444;`
  - `text-align: justify;`

- [ ] Estilizar o elemento `div`:
  - `text-align: left;`

- [ ] Estilizar o elemento `span`:
  - `color: #0066cc;`
  - `font-size: 14px;`

### 6. Seletores de Classe
- [ ] Adicionar a classe `destaque` a pelo menos 2 elementos `<p>` no HTML
- [ ] Criar o seletor `.destaque` no CSS com:
  - `color: #e74c3c;`
  - `font-size: 16px;`

- [ ] Adicionar a classe `secao` a todos os elementos `<div>` no HTML
- [ ] Criar o seletor `.secao` no CSS com:
  - `text-align: center;`

- [ ] Adicionar a classe `link-social` aos elementos `<span>` que contêm links (LinkedIn e GitHub)
- [ ] Criar o seletor `.link-social` no CSS com:
  - `color: #16a085;`
  - `font-size: 15px;`

- [ ] Adicionar a classe `tecnologia` aos elementos `<span>` que contêm nomes de tecnologias
- [ ] Criar o seletor `.tecnologia` no CSS com:
  - `color: #8e44ad;`
  - `font-size: 14px;`

### 7. Experimentação e Personalização
- [ ] Criar mais 2 classes personalizadas de sua escolha e aplicá-las em elementos do HTML, pode ser as tags `div`
- [ ] Utilizar pelo menos uma propriedade `text-align` diferente (por exemplo: `right`)
- [ ] Utilizar pelo menos 3 cores diferentes usando `color`
- [ ] Utilizar pelo menos 3 tamanhos diferentes usando `font-size`

### 8. Validação Final
- [ ] Verificar se o arquivo CSS está corretamente vinculado ao HTML
- [ ] Abrir o arquivo `index.html` no navegador e confirmar que todos os estilos foram aplicados
- [ ] Garantir que todas as propriedades CSS foram utilizadas: `color`, `font-size`, e `text-align`
- [ ] Garantir que todos os tipos de seletores foram utilizados: universal (`*`), de elemento, e de classe (`.`)
- [ ] Verificar se sua página no [vercel](https://vercel.com) foi atualizada.

---

## Propriedades CSS Utilizadas Nesta Atividade

- **color**: Define a cor do texto
- **font-size**: Define o tamanho da fonte
- **text-align**: Define o alinhamento do texto (left, center, right, justify)

## Tipos de Seletores Utilizados

- **Seletor Universal** (`*`): Seleciona todos os elementos
- **Seletor de Elemento** (ex: `h1`, `p`, `div`): Seleciona elementos específicos por sua tag HTML
- **Seletor de Classe** (`.nome-da-classe`): Seleciona elementos que possuem a classe especificada

---

## Desafios
- Modificar as bordas, principalmente da tag `div`
- Utilizar imagens e fazer formatos criar classes específicas com `ícones` e `avatar`
- Modificar a tipografia usando por exemplo a tag `font-family`
- Colocar o `div` com a sua identificação fixa no topo da página
- Se já conhece CSS, usar o [tailwindcss](https://tailwindcss.com/) no lugar do CSS puro