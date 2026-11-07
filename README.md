# RPG Local — versões

RPG de texto com um mestre de IA que roda **no seu próprio computador**, sem internet e sem conta. As regras são compatíveis com D&D 5e (SRD 5.2).

> ⚠️ **Versão Alpha.** O jogo ainda está em desenvolvimento, e bugs e erros podem acontecer. Se algo der errado, o botão **Ver log** do executor mostra o que aconteceu.

Este repositório guarda só os instaladores. Baixe a versão mais nova em **[Releases](../../releases/latest)**.

## Como instalar

1. Baixe `RPG-Local-Instalador-<versão>.exe` na página da última versão.
2. Abra o arquivo. Como o instalador não tem assinatura digital paga, o Windows pode mostrar "O Windows protegeu o computador": clique em **Mais informações** e depois em **Executar assim mesmo**.
3. Clique em **Instalar**. Se o Ollama (o motor da IA) não estiver instalado, o instalador baixa e abre a instalação dele.
4. Na primeira abertura, o assistente analisa o seu computador e baixa o modelo do mestre (alguns GB).

O jogo fica em `%LOCALAPPDATA%\Programs\RPG Local`, sem pedir administrador. Para remover, use **Configurações > Aplicativos > RPG Local > Desinstalar**.

## Jogar

Abra o **RPG Local** pelo Menu Iniciar ou pela Área de Trabalho. O executor liga o servidor do jogo e o mestre de IA e mostra quanto o jogo está usando da máquina: a VRAM da placa de vídeo (e quanto dela o modelo do mestre ocupa), o processamento e o uso da placa. A VRAM e o uso da placa aparecem só em placas NVIDIA.

Clique em **Abrir o jogo**: ele abre numa janela própria, como um programa, sem abas nem barra de endereço (pelo Edge ou pelo Chrome). Fechar o executor encerra o jogo.

## Atualizar

Abra o **RPG Local** e clique em **Buscar atualizações**. O executor baixa a versão nova deste repositório, confere o arquivo e reinicia sozinho. Suas campanhas não são apagadas.

## Requisitos

- Windows 10 ou 11, 64 bits.
- Placa de vídeo com 8 GB de memória ou mais é o recomendado. Dependendo do modelo de IA escolhido, o mestre pode usar bastante VRAM para narrar a história. Com menos, o assistente sugere um modelo menor, e o jogo fica mais lento.
- Cerca de 200 MB para o jogo e mais alguns GB para o modelo do mestre.

## Créditos e licenças

- Regras: System Reference Document 5.2, da Wizards of the Coast, sob CC-BY-4.0.
- História "Problemas nos Lagos Gêmeos": adaptação de *Trouble in Twin Lakes*, de Yochai Gal (Cairn), sob CC-BY-SA 4.0.
- Fontes Nunito, Crimson Pro, Cinzel e Alegreya: SIL Open Font License 1.1.
- A lista completa está no arquivo `CREDITOS.md`, dentro da pasta do jogo instalado.
