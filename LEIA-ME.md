# Controle da Lente (versão offline)

Os dados ficam salvos só no aparelho em que você usa o app. Nada vai para a nuvem.

## No notebook

Abra o `index.html` no navegador (Chrome, Safari ou Edge). Ele funciona sem internet.

## No iPhone (como app na tela de início)

O iPhone só instala um web app a partir de um endereço `https://`. Ele não instala a partir de um arquivo aberto no app Arquivos. Por isso, os arquivos do app precisam ficar num site estático uma vez:

1. Coloque esta pasta inteira num serviço gratuito de site estático, como o GitHub Pages ou o Netlify Drop. Só o app fica lá. Os seus dados nunca saem do celular.
2. No iPhone, abra o endereço no **Safari**, toque em **Compartilhar** e depois em **Adicionar à Tela de Início**.
3. Abra o app uma vez com internet. Depois disso, ele funciona offline.

## Login e senha

O app só abre com o e-mail e a senha cadastrados. Isso vale em qualquer aparelho, e não existe opção de criar outro acesso. O arquivo guarda apenas um resumo cifrado do login: o e-mail e a senha não aparecem nele.

Os dados de cada aparelho ficam cifrados com essa senha. O app trava sozinho depois de 5 minutos fora dele, e o botão de cadeado sai na hora. Depois de 5 tentativas erradas, ele espera 30 segundos.

Para trocar a senha, é preciso gerar uma nova versão do `index.html`.

## Levar os dados de um aparelho para o outro

1. No aparelho onde você fez as alterações, toque no botão de setas (Backup dos dados) e depois em **Exportar cópia**. No iPhone, escolha **Salvar em Arquivos** ou mande por AirDrop.
2. No outro aparelho, abra **Backup dos dados**, toque em **Importar arquivo** e escolha o arquivo `controle-lente-AAAA-MM-DD.html`.

Os backups também saem cifrados. Como todos os aparelhos usam o mesmo login, eles são importados sem pedir a senha de novo. O arquivo exportado também é o app completo: no notebook, dá para abri-lo direto e entrar com o login.

Dica: exporte uma cópia de vez em quando, como segurança.
