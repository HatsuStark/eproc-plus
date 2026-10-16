# Eproc+

Extensão do Chrome com melhorias para o eproc do TJSP: pesquisa no localizador principal
e cópia de preferências de minuta (com o modelo) entre usuários.

**Versão atual: 1.1.1** (16/10/2026)

- Botões com nomes mais claros: 📋 Copiar Preferências (tela do processo), 📋 Copiar esta e 📥 Colar Preferências (Nova Minuta)
- Kit: 📦 Criar kit para enviar a um colega e 📂 Abrir kit recebido
- Painéis com explicação curta no topo e botões que mostram quantas preferências estão marcadas
- Verificar atualização avisa quando é preciso recarregar a extensão
- Correção: preferências de Carta AR agora copiam o modelo e os dados de AR (mão própria, cobrança e atos)
- Ao colar em outro sistema (ex.: eproc1g-ef), a conferência avisa que os códigos são diferentes
- O resultado da colagem também aparece no canto da tela

## Instalar

1. Baixe o [eproc-plus-1.1.1.zip](https://github.com/HatsuStark/eproc-plus/raw/main/eproc-plus-1.1.1.zip) e extraia numa pasta permanente
   (ex.: `Documentos\eproc-plus`).
2. Abra `chrome://extensions` e ative o **Modo do desenvolvedor**.
3. Clique em **Carregar sem compactação** e escolha a pasta `eproc-plus` (a que tem o `manifest.json`).

## Atualizar

Quando houver versão nova, o ícone do Eproc+ mostra o selo **novo**. Abra o popup, clique em **Baixar**,
extraia o zip **por cima da mesma pasta** e clique em ⟳ na extensão em `chrome://extensions`.
Suas preferências guardadas continuam lá (ficam no Chrome, não na pasta).

Histórico completo: `novidades.json` dentro da extensão, ou "Novidades" no popup.
