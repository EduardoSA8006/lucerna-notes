# Proposta do lucerna-notes

O `lucerna-notes` é um bloco de notas em Rust. Funciona sozinho, com uma TUI, e ganha um painel no Lucerna.

Segue a estrutura de apps do [ecossistema](https://github.com/EduardoSA8006/lucerna-sdk/blob/main/docs/ecossistema.md): núcleo, TUI, provedor e painel em QML.

## Painel e TUI

O painel serve para olhar e agir rápido. O trabalho completo fica na TUI.

**No painel:**

- captura rápida: digita, Enter, salvo;
- fixadas e recentes, com prévia de 2 linhas;
- busca no texto;
- abrir uma nota numa leitura simples, com as caixas de seleção marcáveis;
- um botão "editar" que abre a nota na TUI ou no editor.

**Só na TUI:**

- editar texto longo;
- organizar em pastas ou etiquetas;
- ligar notas entre si;
- importar e exportar.

## Em aberto

- O formato das notas (Markdown?).
- A organização.
- A busca.
- A sincronização.
