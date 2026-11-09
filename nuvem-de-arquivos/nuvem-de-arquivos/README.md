# ☁️ Nuvem de Arquivos

Sistema simples de arquivos em nuvem com login. Permite enviar, listar, visualizar e excluir **PDFs e imagens**.

## Recursos
- Tela de login
- Upload por arrastar e soltar ou seleção
- Busca e filtros (Todos / Imagens / PDFs)
- Visualização de imagens e PDFs
- Tema claro/escuro e layout responsivo

## Como usar
Abra o `index.html` no navegador ou publique com GitHub Pages.

Login de demonstração: `testedojp01` / senha `xapuri2026`

## Armazenamento
Os arquivos ficam no IndexedDB do navegador (modo local). Quando publicado como artefato do Claude, usa o armazenamento da plataforma.

## Aviso de segurança
A autenticação é feita no navegador (hash SHA-256 no código), serve apenas para demonstração. Para uso real, valide o login em um servidor.
