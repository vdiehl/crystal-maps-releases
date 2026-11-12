# Crystal Maps: versões

Este repositório só tem as versões do jogo **Crystal Maps** para o playtest (Windows e Linux). O código não está aqui.

- Cada [release](../../releases) é uma versão: a tag é o commit do jogo, e os arquivos são `CrystalMaps-windows.zip`,
  `CrystalMaps-linux.zip` e `versao.json`.
- **Para jogar:** baixe o zip do seu sistema na release mais nova e extraia numa pasta.
- **O jogo se atualiza sozinho** pela tela de título ("Versão nova: Atualizar"): ele baixa daqui a versão que o
  servidor usa, confere a assinatura do `versao.json` (ed25519) e o SHA-256 do zip e só então troca os arquivos.
