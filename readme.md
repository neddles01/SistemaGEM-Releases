# neddlesSY — releases

Versão atual: **1.8.17** — intervalo mínimo de F2 de 8,5 segundos.

[Patchnotes e instaladores da 1.8.17](https://github.com/neddles01/SistemaGEM-Releases/releases/tag/1.8.17).

Use `Setup-neddlesSY-v1.8.17.exe` para instalar ou atualizar a edição principal,
sem desinstalar. `Setup-SistemaGEM-v1.8.17.exe` é o alias idêntico para
atualizadores antigos. Confira `SHA256SUMS.txt`.

F2 passa a aguardar no mínimo 8,5 segundos entre ciclos, contados da última
tentativa do par. As duas tentativas internas continuam separadas por 250 ms;
F1 continua entre os ciclos. Cooldowns configurados maiores continuam respeitados,
com a margem de 0,2 s. Preferências e calibração existentes são preservadas.

Mantém os HUDs padrão/Halloween, movimentos orgânicos e prioridade de poções,
buffs, bolha, reposição e morte/Cidade. A principal usa texturas normais dos
monstros e funciona na CPU sem exigir GPU dedicada. A Low tem canal próprio.

Feche o macro, atualize pelo atalho ou instalador como administrador e confira
1.8.17 no rodapé. Deixe o jogo visível na primeira calibração.
Testes automatizados de fonte e módulos compilados e auditoria do pacote aprovados.
Instalação e gameplay desta entrega ainda não foram executados nesta preparação.
Este repositório contém somente distribuição e metadados de atualização.
