# Controle da Lente (versão offline)

Os dados ficam salvos só no aparelho em que você usa o app. Nada vai para a nuvem.

## No notebook

Abra o `index.html` no navegador (Chrome, Safari ou Edge). Ele funciona sem internet.

## No iPhone (como app na tela de início)

O iPhone só instala um web app a partir de um endereço `https://`. Ele não instala a partir de um arquivo aberto no app Arquivos. Por isso, os arquivos do app precisam ficar num site estático uma vez:

1. Coloque esta pasta inteira num serviço gratuito de site estático, como o GitHub Pages ou o Netlify Drop. Só o app fica lá. Os seus dados nunca saem do celular.
2. No iPhone, abra o endereço no **Safari**, toque em **Compartilhar** e depois em **Adicionar à Tela de Início**.
3. Abra o app uma vez com internet. Depois disso, ele funciona offline.

## Levar os dados de um aparelho para o outro

1. No aparelho onde você fez as alterações, toque no botão de setas (Backup dos dados) e depois em **Exportar cópia**. No iPhone, escolha **Salvar em Arquivos** ou mande por AirDrop.
2. No outro aparelho, abra **Backup dos dados**, toque em **Importar arquivo** e escolha o arquivo `controle-lente-AAAA-MM-DD.html`.

O arquivo exportado também é o app completo. No notebook, dá para abrir direto e ele já mostra os dados que vieram nele.

Dica: exporte uma cópia de vez em quando, como segurança.
