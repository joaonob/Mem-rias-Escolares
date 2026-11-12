# Minha Jornada — Projeto Final de Programação Web

Site pessoal responsivo com HTML, CSS e JavaScript, contendo linha do tempo escolar e portfólio interativo de 15 redações.

## Estrutura
- `index.html` — página principal
- `css/style.css` — estilos e responsividade
- `js/script.js` — dados e interatividade
- `assets/` — fotos e outras mídias

## Personalização obrigatória
1. Em `index.html`, troque **Seu Nome Aqui** e a apresentação por seus dados.
2. Em `js/script.js`, substitua os seis relatos do array `memorias` pelas suas experiências verdadeiras.
3. Substitua os quinze campos `texto` no array `temas` pelas suas **15 redações completas produzidas em aula**; os textos atuais são somente exemplos ilustrativos.
4. Adicione suas fotos à pasta `assets/`. Para exibi-las, substitua cada bloco `.moment-img` pela tag `<img src="assets/nome-da-foto.jpg" alt="Descrição da foto">` e adicione no CSS `.moment-img img{width:100%;height:100%;object-fit:cover;border-radius:12px}` ou adapte a renderização JS para cada memória.

## Como executar
Abra `index.html` no navegador ou utilize a extensão Live Server no VS Code.

## Como publicar no GitHub Pages
1. Crie um repositório público no GitHub.
2. Envie `index.html`, `css/`, `js/` e `assets/`, mantendo a estrutura.
3. Acesse **Settings > Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**, branch `main`, pasta `/(root)` e clique **Save**.
5. Aguarde a publicação e confira o link `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.
6. Entregue o link do repositório, verificando antes se o site publicado funciona.

Observação: o repositório e a publicação devem ser feitos na sua própria conta GitHub.

## Portfólio atualizado
As 15 redações corrigidas estão em `js/script.js`, com notas originais quando fornecidas. A redação 8 está com conclusão incompleta e identificada como tal; substitua o trecho marcado assim que tiver o texto completo.
