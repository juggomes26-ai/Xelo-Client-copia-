# FKWÜ Client

Cliente Android para Minecraft Bedrock, baseado no projeto de código aberto [Xelo-Client](https://github.com/Xelo-Client/Xelo-Client). Esta versão personalizada usa uma identidade visual preta e amarela e está em desenvolvimento.

> **Estado do projeto:** em desenvolvimento. Os itens abaixo descrevem recursos presentes na base ou planejados; a presença de uma opção no launcher não garante que o recurso funcione em todas as versões do Minecraft Bedrock. As funções precisam ser verificadas em aparelho e jogo compatíveis.

## Identidade visual
- Tema FKWÜ preto e amarelo.
- Textos do launcher e descrições de módulos em português brasileiro.
- Desenvolvimento isolado na branch `fkwu-client`.

## Recursos da base em avaliação
- Launcher Android e gerenciamento de versões/configurações herdados da base.
- Temas e personalização visual.
- Suporte a pacotes de recursos/shaders conforme a compatibilidade da base.
- Módulos integrados: Zoom+, corrida automática, alternância de perspectiva, ocultar HUD, descarte rápido, slots da barra rápida, exibição de FPS/CPS e nome em terceira pessoa.
- Opções de renderização na configuração de módulos: brilho melhorado, sem neblina, redução de partículas/sombras e outras opções experimentais.
- Importação de imagem para mira personalizada.

## Recursos que ainda precisam de implementação ou validação
- Confirmar cada módulo no Minecraft Bedrock e remover/corrigir opções que não tenham efeito real.
- Revisar desempenho, estabilidade e compatibilidade com versões atuais do jogo.
- Investigar gravação e reprodução de partidas (Replay). Replay não é anunciado como funcional até existir implementação real e testes.

## Compilação de teste
O fluxo de GitHub Actions executa os testes unitários nas alterações. A criação e o envio do APK debug são reservados para execução manual do workflow, para evitar gerar um APK em cada commit.

1. Abra a aba [Actions](https://github.com/juggomes26-ai/Xelo-Client-copia-/actions).
2. Selecione **Build Debug APK**.
3. Use **Run workflow** e escolha a branch `fkwu-client`.
4. Quando a execução terminar com sucesso, abra a execução e baixe o artefato `origin-debug-apk-...`.

Um build bem-sucedido confirma a compilação, não o funcionamento dentro do jogo. Teste no Android e no Minecraft Bedrock antes de considerar uma função pronta.

## Créditos e licença
Este projeto deriva do [Xelo-Client](https://github.com/Xelo-Client/Xelo-Client). Consulte a licença e os avisos de direitos autorais mantidos no repositório e preserve os créditos da base original.
