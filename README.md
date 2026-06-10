# REVESTU — Relatório de Imersão (Grupo 02) · ODS 12

Documento LaTeX estruturado no seu template, com os **textos dos alunos mantidos intactos**.

## Como compilar
- **Overleaf / Colab:** subir `main.tex` + a pasta `imgs/` e compilar com **XeLaTeX** ou **pdfLaTeX**. (O `previa.pdf` foi gerado aqui só pra conferência visual.)
- O `main.tex` usa `\usepackage[portuguese]{babel}` e `lmodern` — funciona direto no seu ambiente.

## Estrutura visual
- **Capa** estilo Dundee (Imagem 1) — bloco de cor sólida + título grande.
- **Folha de rosto** estilo EPFL (Imagem 2) — autores + metadados.
- **Aberturas de seção** com número gigante (Imagem 3).
- Paleta tirada da **persona Flademir** (verde-oliva + amarelo).

## Pendências (placeholders no documento)
1. **Logo da escola** — está como texto "ETE CÍCERO DIAS" (capa, folha de rosto e cabeçalho). Para trocar pela imagem, descomente as linhas no topo do `main.tex` (procure por `\logoEscolaClara` / `\logoEscolaEscura`) e coloque o arquivo em `imgs/`.
2. **Figura 7 (Atacama)** — é imagem de terceiros (BBC/AFP), então deixei uma **moldura com legenda e fonte**. Basta inserir a imagem em `imgs/` e trocar o placeholder por `\includegraphics`.

## Cores (fáceis de trocar)
Todas as cores estão definidas no topo do `main.tex` (oliveDeep, olive, oliveSoft, accentYellow, cream, etc.).
