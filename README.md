diff --git a/README.md b/README.md
index 6292026fe009eddcc4f90aa9c1244b77f71b8f39..f5e4a66d3ab4401a6968c164c1561bbe08faa8e3 100644
--- a/README.md
+++ b/README.md
@@ -1,20 +1,20 @@
 # GPTPROJECT
 
-This project provides scripts to automate creating a macOS recovery USB drive. It is intended for older Macs that lack a built‑in Recovery HD.
+Este projeto disponibiliza scripts para criar um pendrive de recuperação do macOS. É últil para Macs antigos que não possuem a partição Recovery HD.
 
-## Prerequisites
-- macOS with command line tools
-- [Homebrew](https://brew.sh) for automatic dependency installation
-- An 8GB (or larger) USB drive
+## Pré-requisitos
+- macOS com ferramentas de linha de comando
+- [Homebrew](https://brew.sh) para instalação automática de dependências
+- Pendrive de pelo menos 8 GB
 
-## Usage
-1. Open Terminal and clone this repository.
-2. Run `./scripts/create-recovery.sh`.
-3. The script lists available removable disks and prompts you to choose the target by number.
-4. It downloads a recovery image, erases the selected disk and writes the image.
-5. After completion, boot your Mac while holding `Option` and select the USB drive.
+## Como usar
+1. Abra o Terminal e clone este repositório.
+2. Execute `./scripts/create-recovery.sh`.
+3. O script lista os discos removíveis disponíveis e solicita que você escolha o alvo pelo número.
+4. Ele baixa a imagem de recuperação, apaga o pendrive escolhido e grava a imagem.
+5. Ao finalizar, reinicie o Mac segurando `Option` e escolha o pendrive para inicializar.
 
-The script verifies that required tools (`curl`, `hdiutil`, `diskutil`, `bless`) are installed and attempts to install them via Homebrew if missing.
+O script verifica se as ferramentas necessárias (`curl`, `hdiutil`, `diskutil`, `bless`) estão instaladas e tenta obtê-las via Homebrew caso não estejam.
 
-## License
-This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
+## Licença
+Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
