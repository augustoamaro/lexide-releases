# Lexide

Editor de texto que ensina inglês enquanto você escreve: corrige, sugere e explica cada erro em português.

Este repositório guarda só os **instaladores** e o **feed de atualização** do app. O código não fica aqui.

## Instalar (Linux)

Baixe o arquivo do [release mais recente](https://github.com/augustoamaro/lexide-releases/releases/latest):

- **AppImage** (qualquer distribuição): `chmod +x Lexide_*.AppImage` e abra. Atualiza sozinho pelo app.
- **Debian e Ubuntu**: `sudo apt install ./Lexide_*_amd64.deb`
- **Fedora e openSUSE**: `sudo dnf install ./Lexide-*.x86_64.rpm`

macOS e Windows chegam em breve.

## Atualizações

Lexide só procura atualização quando você pede (Session → Updates → *Check for updates*) ou se você ligar *Check when Lexide opens*. Cada pacote é assinado; o app confere a assinatura antes de instalar.

Os instaladores ainda não têm assinatura de sistema (Apple, Microsoft). Por isso o sistema pode avisar na primeira vez que você abrir o app.

## Modelos locais

Os modelos opcionais que rodam no seu computador são baixados pelo próprio app, só quando você pede:

- corretor [proofbird/gector-bert-en](https://huggingface.co/proofbird/gector-bert-en) (Apache-2.0)
- [SmolLM2-135M](https://huggingface.co/HuggingFaceTB/SmolLM2-135M) (Apache-2.0)
- [ONNX Runtime](https://onnxruntime.ai) (MIT)
