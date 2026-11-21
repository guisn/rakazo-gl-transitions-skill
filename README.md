# gl-transitions — plugin de skill para Rakazo

Este repositório empacota a skill oficial `gl-transitions` no formato de plugin skills-only aceito pelo Rakazo. Inclui apenas Markdown e o manifesto `plugin.json`: não inclui MCP, executáveis, dependências, `package.json`, scripts de instalação ou código dos shaders.

## Importar no Rakazo

1. Abra **Integrations** → **+** → **From GitHub**.
2. Informe `https://github.com/guisn/rakazo-gl-transitions-skill` e escolha **Preview**.
3. Confira se o preview lista somente a skill `gl-transitions` e escolha **Add**.
4. Teste a skill com um pedido de transição, por exemplo: “Sugira três transições GLSL para revelar esta cena”.

## Origem e versionamento

- `skills/gl-transitions/SKILL.md`, referências WebGL/Skia/vídeo/nativas e `LICENSE`: snapshot do projeto upstream [`gl-transitions`](https://github.com/gl-transitions/gl-transitions), commit `5f3c71ce53891167ae94ce7a060fb7c13d8c0794`.
- `skills/gl-transitions/references/catalog.md`: índice estático curado da publicação `gl-transitions@2.5.0`; a referência completa e atual dos 193 shaders está vinculada no próprio arquivo.
- Os arquivos de referência foram comparados com as URLs oficiais correspondentes antes da publicação. Não há atualização automática; revise o upstream antes de atualizar o snapshot.

A skill contém exemplos que mencionam instalação de bibliotecas para projetos, mas a importação deste plugin só adiciona instruções ao Rakazo. Ela não executa `npm`, `npx` ou qualquer instalador, não baixa shaders para um projeto e não altera nenhum repositório de trabalho. Verifique a licença de cada shader individual antes de redistribuí-lo ou usá-lo em uma entrega.

## Licença

A licença MIT upstream está incluída em `LICENSE`. Alguns shaders individuais podem ter avisos/licenças próprios; confira o arquivo específico antes de redistribuição.
