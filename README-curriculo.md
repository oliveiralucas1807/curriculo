# Curriculo - Lucas Oliveira da Silva

Arquivos criados:

- `curriculo-lucas-oliveira.html`
- `curriculo-lucas-oliveira.css`
- `README-curriculo.md`
- `assets/foto-lucas.jpg` deve ser adicionada por voce, se quiser usar foto.

## Como abrir

Abra o arquivo `curriculo-lucas-oliveira.html` no navegador. O layout foi preparado em A4 vertical para visualizacao e exportacao em PDF.

## Como trocar a foto

Coloque sua foto profissional neste caminho:

`assets/foto-lucas.jpg`

Se a imagem nao existir, o curriculo mostra um placeholder discreto com a palavra "Foto".

## Onde editar textos

Edite os textos diretamente no arquivo `curriculo-lucas-oliveira.html`.

As secoes principais estao separadas por blocos:

- Cabecalho e contatos
- Resumo
- Competencias
- Formacao
- Cursos
- Idiomas
- Experiencia profissional
- Rodape
A secao opcional de destaques profissionais ficou fora desta versao para priorizar uma pagina A4 mais limpa.

## Onde trocar o portfolio

Procure por:

`portfolio-lucas.com`

Troque pelo link real do seu portfolio quando tiver o link definitivo.

## Como salvar em PDF pelo navegador

1. Abra `curriculo-lucas-oliveira.html`.
2. Pressione `Ctrl + P`.
3. Escolha `Salvar como PDF`.
4. Em tamanho do papel, selecione `A4`.
5. Ative a opcao de imprimir graficos/cores de fundo, se o navegador mostrar essa opcao.
6. Salve como `curriculo-lucas-oliveira.pdf`.

## Como gerar PDF automaticamente

Se o computador tiver Google Chrome ou Microsoft Edge instalado, voce pode tentar gerar o PDF em modo automatico pelo terminal, dentro desta pasta:

```powershell
msedge --headless --disable-gpu --print-to-pdf="curriculo-lucas-oliveira.pdf" "curriculo-lucas-oliveira.html"
```

Ou, usando Chrome:

```powershell
chrome --headless --disable-gpu --print-to-pdf="curriculo-lucas-oliveira.pdf" "curriculo-lucas-oliveira.html"
```

## Se passar de uma pagina

Para reduzir sem perder qualidade:

- Remova a secao `Destaques profissionais`.
- Reduza um bullet das experiencias Inspira ou Teaga.
- Mantenha as experiencias principais: Inspira, Teaga, Revista Cenarium e Loja Adrenalina.
- Evite diminuir demais a fonte; e melhor cortar repeticoes do texto.
