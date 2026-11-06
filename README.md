# RPG Local — versões

RPG de texto com um mestre de IA que roda **no seu próprio computador**, sem internet e sem conta. As regras são compatíveis com D&D 5e (SRD 5.2).

Este repositório guarda só os instaladores. Baixe a versão mais nova em **[Releases](../../releases/latest)**.

## Como instalar

1. Baixe `RPG-Local-Instalador-<versão>.exe` na página da última versão.
2. Abra o arquivo. Como o instalador não tem assinatura digital paga, o Windows pode mostrar "O Windows protegeu o computador": clique em **Mais informações** e depois em **Executar assim mesmo**.
3. Clique em **Instalar**. Se o Ollama (o motor da IA) não estiver instalado, o instalador baixa e abre a instalação dele.
4. Na primeira abertura, o assistente analisa o seu computador e baixa o modelo do mestre (alguns GB).

O jogo fica em `%LOCALAPPDATA%\Programs\RPG Local`, sem pedir administrador. Para remover, use **Configurações > Aplicativos > RPG Local > Desinstalar**.

## Atualizar

Abra o **RPG Local** e clique em **Buscar atualizações**. O executor baixa a versão nova deste repositório, confere o arquivo e reinicia sozinho. Suas campanhas não são apagadas.

## Requisitos

- Windows 10 ou 11, 64 bits.
- Placa de vídeo com 8 GB de memória ou mais é o recomendado. Com menos, o assistente sugere um modelo menor, e o jogo fica mais lento.
- Cerca de 200 MB para o jogo e mais alguns GB para o modelo do mestre.

## Créditos e licenças

- Regras: System Reference Document 5.2, da Wizards of the Coast, sob CC-BY-4.0.
- História "Problemas nos Lagos Gêmeos": adaptação de *Trouble in Twin Lakes*, de Yochai Gal (Cairn), sob CC-BY-SA 4.0.
- Fontes Nunito, Crimson Pro, Cinzel e Alegreya: SIL Open Font License 1.1.
- A lista completa está no arquivo `CREDITOS.md`, dentro da pasta do jogo instalado.
