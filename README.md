# Eproc+

Extensão do Chrome com melhorias para o eproc do TJSP: pesquisa no localizador principal
e cópia de preferências de minuta (com o modelo) entre usuários.

**Versão atual: 1.2.0** (23/10/2026)

- Relatório Geral de Processos: "Frase exata" no Conteúdo do Lembrete (ou texto entre aspas) traz só os processos com as palavras juntas, nessa ordem
- O eproc busca "qualquer das palavras"; a Eproc+ confere os lembretes completos e põe o resultado em "Lista de processos"
- Popup: Abrir kit abre o explorador de arquivos direto

## Instalar

1. Baixe o [eproc-plus-1.2.0.zip](https://github.com/HatsuStark/eproc-plus/raw/main/eproc-plus-1.2.0.zip) e extraia numa pasta permanente
   (ex.: `Documentos\eproc-plus`).
2. Abra `chrome://extensions` e ative o **Modo do desenvolvedor**.
3. Clique em **Carregar sem compactação** e escolha a pasta `eproc-plus` (a que tem o `manifest.json`).

## Atualizar

Quando houver versão nova, o ícone do Eproc+ mostra o selo **novo**. Abra o popup, clique em **Baixar**,
extraia o zip **por cima da mesma pasta** e clique em ⟳ na extensão em `chrome://extensions`.
Suas preferências guardadas continuam lá (ficam no Chrome, não na pasta).

Histórico completo: `novidades.json` dentro da extensão, ou "Novidades" no popup.
