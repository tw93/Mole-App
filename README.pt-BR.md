# Mole App

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · [Italiano](README.it.md) · Português (Brasil)

Documentação oficial e suporte da comunidade para o **Mole for Mac** e o **Mole for Windows**.

Os apps para Mac e Windows são apps nativos pagos, e a compra das licenças ajuda a financiar o desenvolvimento e as atualizações. Este repositório é para documentação, dúvidas e feedback e não contém o código-fonte dos apps. O [Mole CLI](https://github.com/tw93/Mole) continua gratuito e de código aberto.

## Baixar o Mole

| App | Requisitos | Download | Guia do usuário |
| --- | --- | --- | --- |
| Mole for Mac | macOS 14 ou posterior, Apple Silicon ou Intel | [Site do Mac](https://mole.fit/pt-br/?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Ajuda do Mac](https://mole.fit/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Mole for Windows | Windows 10 22H2 ou Windows 11, x64 ou ARM64 | [Site do Windows](https://mole.fit/pt-br/windows?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Ajuda do Windows](https://mole.fit/pt-br/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

Os dois apps reúnem limpeza, gerenciamento de apps, manutenção, análise de disco e status do sistema em tempo real em uma única interface.

### Mole for Mac

O Mole for Mac é um app nativo em SwiftUI criado e mantido por [Tw93](https://github.com/tw93), com ferramentas rápidas na barra de menus.

![Tela de limpeza do Mole for Mac](https://mole.fit/img/pt-br/clean.jpg)

| Ferramenta | O que você pode fazer | Guia |
| --- | --- | --- |
| Limpar | Revise caches de apps e navegadores, logs e arquivos de build de desenvolvimento antes de escolher o que remover | [Limpeza do Mac](https://mole.fit/mac-cleaner?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Apps | Desinstale apps, revise os resíduos, procure atualizações e gerencie itens de início | [Gerenciamento de apps](https://mole.fit/mac-app-uninstaller?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Otimizar | Execute a manutenção do macOS, use Limpar tela ou Manter tela ligada | [Manutenção do Mac](https://mole.fit/mac-optimizer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Analisar | Encontre arquivos e pastas grandes em um treemap do disco, mostre-os no Finder ou mova os itens selecionados para o Lixo | [Análise de disco](https://mole.fit/mac-disk-analyzer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Status | Veja CPU, memória, armazenamento, rede e temperatura, com métricas selecionadas na barra de menus | [Monitor do sistema](https://mole.fit/mac-system-monitor?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

#### Limpeza de IA · Beta

A versão Beta adiciona a Limpeza e Cuidado de IA dentro de Limpar. Ela revisa caches, versões antigas, sessões antigas, worktrees que podem ser limpos e ferramentas de linha de comando ociosas do Claude Code, Codex, Cursor e de outras ferramentas de IA. Os caches já vêm selecionados, enquanto sessões e ferramentas precisam da sua revisão. Memórias, planos e skills ficam de fora. Para modelos locais, só aparecem os modelos do Ollama sem uso há um mês, para você selecionar e remover pelo Ollama. Veja o [guia de limpeza de IA](https://mole.fit/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#docs-ai) para mais detalhes.

### Primeiros passos no Mac

1. Baixe o DMG no site do Mac acima, arraste o Mole para Aplicativos e abra-o. Se você já usa o Homebrew, `brew install --cask mole-app` instala o app para Mac.
2. Faça uma busca e revise os resultados antes de remover qualquer coisa. Se o Mole avisar que falta o Acesso ao disco, siga o guia de permissões abaixo e abra o app de novo.
3. Depois da compra, abra o painel de licença com `Cmd + Shift + L`, cole a chave do e-mail da Dodo Payments e clique em Ativar.

[Artigos do Mac](https://mole.fit/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Notas de versão do Mac](https://mole.fit/pt-br/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

### Guias selecionados para Mac

- [Mole CLI vs app para Mac](https://mole.fit/blog/mole-cli-vs-mac-app?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): como a ferramenta gratuita de terminal e o app nativo pago se diferenciam.
- [O Mole é seguro para Mac?](https://mole.fit/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): o que vai para o Lixo, o que é removido permanentemente e o que fica protegido.
- [O que são os Dados do Sistema no Mac?](https://mole.fit/blog/what-is-system-data-on-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): descubra o que ocupa espaço antes de apagar qualquer coisa.
- [Revise os resíduos de desinstalação no Mac](https://mole.fit/blog/mac-uninstall-leftovers-review-before-delete?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): confira a propriedade dos arquivos e os dados compartilhados antes de remover.
- [Apague modelos do Ollama e do LM Studio](https://mole.fit/blog/how-to-remove-ai-tool-leftovers-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): separe modelos baixados, caches e dados pessoais.
- [Testando apps do Mac para o Mole](https://mole.fit/blog/testing-mac-apps-one-by-one?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): o que instalações reais e testes de desinstalação revelam.

### Mole for Windows

O app para Windows melhora a cada versão.

![Tela de limpeza do Mole for Windows](https://mole.fit/img/windows-pt-br/clean.jpg)

[Artigos do Windows](https://mole.fit/windows/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Notas de versão do Windows](https://mole.fit/windows/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

## Feedback

- [Relatar um bug do app para Mac](https://github.com/tw93/Mole-App/issues/new?template=mac_bug.yml)
- [Relatar um bug do app para Windows](https://github.com/tw93/Mole-App/issues/new?template=windows_bug.yml)
- [Sugerir um recurso](https://github.com/tw93/Mole-App/issues/new?template=feature_request.yml)
- [Fazer uma pergunta ou participar de uma discussão](https://github.com/tw93/Mole-App/discussions)

Issues e discussões são públicas. Para dúvidas sobre compra, ativação ou reembolso, escreva para [hi@mole.fit](mailto:hi@mole.fit). Envie relatos de segurança pelo [canal privado de denúncia](.github/SECURITY.md).

Para diagnóstico no Mac, abra o menu do logo do Mole e escolha Executar diagnóstico. Envie o relatório em particular para [hi@mole.fit](mailto:hi@mole.fit), junto com a versão do app e o que aconteceu.

Para bugs e sugestões do CLI, use [tw93/Mole](https://github.com/tw93/Mole/issues).

## FAQ

### Um repositório público no GitHub significa que os apps são de código aberto?

Este repositório contém documentação e feedback da comunidade. O código-fonte dos apps para Mac e Windows é privado. O [Mole CLI](https://github.com/tw93/Mole) é gratuito e de código aberto.

### Preciso instalar o CLI para usar os apps?

Não. O Mole for Mac e o Mole for Windows são apps de desktop independentes. Instalar o CLI não instala nenhum dos dois apps.

### Os apps são gratuitos?

Os apps usam licenças de pagamento único. O Mole for Mac custa **$19 USD para dois Macs**, sem assinatura e com atualizações gratuitas, incluindo versões principais. A [página oficial de preços](https://mole.fit/pricing.md?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) traz as condições atuais. O preço e a disponibilidade do Windows estão no site do produto. O CLI de código aberto é gratuito.

### Posso testar o app para Mac antes de comprar?

A busca é gratuita, e cada ferramenta paga tem duas execuções de teste. Você pode ver a análise de disco e o status do sistema sem licença. A [central de ajuda do Mac](https://mole.fit/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explica como baixar, testar e ativar o app.

### Posso mover minha licença do Mac para um computador novo?

No Mac antigo, abra o painel de licença com `Cmd + Shift + L`, desative a licença e ative a mesma chave no Mac novo. Se o Mac antigo não estiver disponível, entre no [Portal do Cliente da Dodo Payments](https://customer.dodopayments.com/) com o e-mail da compra e desative a licença por lá. O limite de dispositivos depende da licença que você comprou. A edição atual cobre dois Macs.

### Onde estão minha chave de licença e minha nota fiscal?

Procure por Dodo Payments na caixa de entrada e no spam, ou entre no [Portal do Cliente da Dodo Payments](https://customer.dodopayments.com/) com o e-mail usado na compra para encontrar a chave, o pedido e a fatura. Se ainda precisar de ajuda, escreva para [hi@mole.fit](mailto:hi@mole.fit) com o e-mail da compra ou o Payment ID. Não publique esses dados em issues públicas.

### E se o app para Mac não for o ideal para mim?

Escreva para [hi@mole.fit](mailto:hi@mole.fit) em até 14 dias após a compra, com o Payment ID ou o e-mail da compra. A [política de reembolso](https://mole.fit/refund?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) traz as condições completas.

### O app para Mac envia meus arquivos ou resultados de busca?

A busca e a limpeza acontecem localmente no seu Mac. O Mole não envia o conteúdo nem os nomes dos arquivos, nem os resultados da busca, e o registro local de operações não é enviado automaticamente. A [política de privacidade](https://mole.fit/privacy?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explica a ativação da licença, as atualizações e outros recursos que acessam serviços online.

### Por que o Mole pede Acesso ao disco?

O macOS restringe o acesso a alguns dados de apps. O Acesso ao disco permite que o Mole inspecione esses locais. Os caminhos protegidos e a sua lista de proteção continuam valendo, então liberar o acesso não transforma todo arquivo em candidato à limpeza. Veja o [guia de permissões](https://mole.fit/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#doctor-permission-fda).

### Posso restaurar arquivos depois da limpeza no Mac?

Os apps desinstalados e os arquivos residuais selecionados vão para o Lixo e podem ser restaurados enquanto estiverem lá. A limpeza de caches é permanente por padrão, com uma opção de usar o Lixo nos Ajustes. Algumas ações de manutenção removem dados diretamente e não podem ser desfeitas. O [guia de segurança](https://mole.fit/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explica cada operação.

### Como funcionam as atualizações do Mac e os recursos em Beta?

O Mole tem um atualizador integrado, e as [notas de versão oficiais](https://mole.fit/pt-br/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) descrevem cada versão. Os recursos marcados como Beta na documentação exigem a versão Beta até chegarem a uma versão estável.

### Posso usar o Mole com o teclado ou o VoiceOver?

O Mole oferece navegação pelo teclado e suporte ao VoiceOver. O treemap é visual, e você pode percorrer os mesmos arquivos na lista Maiores arquivos pelo teclado ou com o VoiceOver. Veja o [guia de acessibilidade](https://mole.fit/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) para detalhes e limitações atuais.

### Qual site é o oficial?

**mole.fit** é o site oficial dos apps. Use os links de download acima para obter os pacotes atuais. O CLI gratuito fica em [tw93/Mole](https://github.com/tw93/Mole).

### Onde encontro instruções detalhadas?

A [documentação do Mac](https://mole.fit/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explica as ferramentas e suas regras de segurança. O [catálogo de apps testados](https://mole.fit/pt-br/tested-apps?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) traz notas de instalação, desinstalação e resíduos de cada app. Para configuração, ativação ou solução de problemas, consulte a [central de ajuda do Mac](https://mole.fit/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) ou a [central de ajuda do Windows](https://mole.fit/pt-br/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme). Os termos da licença estão nos [termos de serviço](https://mole.fit/terms?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme).
