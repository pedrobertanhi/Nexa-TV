# Tutorial do Nexa TV 4.1.0

Este guia explica como instalar, configurar, atualizar e usar os recursos Free e
Pro do Nexa TV em televisores Android TV e Google TV.

## 1. Antes de instalar

- Confirme que a TV usa Android TV ou Google TV 8.0 ou superior.
- Baixe o APK somente no repositório oficial `pedrobertanhi/Nexa-TV`.
- Não desative nem remova a tela inicial original da TV.
- Se já usa o Nexa TV, exporte um backup antes de atualizar.

## 2. Instalação usando pendrive

1. Baixe `Nexa-TV-4.1.0-Free-Preview.apk` no computador ou celular.
2. Copie o APK para um pendrive.
3. Conecte o pendrive à televisão.
4. Abra um gerenciador de arquivos instalado na TV.
5. Selecione o APK do Nexa TV.
6. Quando o Android solicitar, permita **Instalar apps desconhecidos** somente
   para o gerenciador usado nessa instalação.
7. Confirme a instalação e abra **Nexa TV**.
8. Depois de instalar, você pode revogar a permissão de fontes desconhecidas.

O nome exato das opções muda conforme a marca e a versão do Android. Não é
necessário root, ADB ou serviço de acessibilidade para a instalação comum.

## 3. Primeiros passos

Ao abrir o aplicativo:

1. Use as setas do controle para navegar pelos cartões.
2. Pressione **OK** para abrir o aplicativo selecionado.
3. Abra a engrenagem e defina o nome mostrado no perfil.
4. Entre em **Organizar aplicativos** para ajustar a tela inicial.
5. Teste Netflix, YouTube, Play Store e outros aplicativos antes de definir o
   Nexa TV como tela inicial padrão.

## 4. Comandos do controle

| Comando | Função |
|---|---|
| Setas | Movem o foco entre menus e aplicativos |
| OK | Abre ou confirma a opção selecionada |
| Segurar OK | Inicia a movimentação de um cartão |
| Esquerda/direita durante o movimento | Altera a posição do aplicativo |
| OK durante o movimento | Salva a nova posição |
| Voltar durante o movimento | Cancela sem salvar |
| Menu | Abre o organizador de aplicativos |

## 5. Organizar aplicativos

1. Abra **Engrenagem → Organizar aplicativos**.
2. Selecione um aplicativo e pressione OK para ver as opções.
3. Use **Mostrar/Ocultar** para controlar o que aparece na tela inicial.
4. Escolha **Definir como destaque** para mudar o aplicativo principal.
5. Segure OK para mover um cartão diretamente.

A Play Store permanece no final. Aplicativos novos podem entrar automaticamente
na tela inicial; essa opção pode ser alterada em **Aparência e animações**.

## 6. Ativar o Nexa TV Pro

O pagamento é realizado fora do aplicativo diretamente com Pedro.

1. Escolha o plano mensal:
   - **Individual:** 1 TV por 30 dias;
   - **Família:** até 3 TVs por 30 dias.
2. Depois da confirmação do pagamento, receba sua chave Nexa TV.
3. Na televisão, abra **Engrenagem → Nexa TV Pro → Ativar meu Pro**.
4. Digite a chave completa e selecione **Liberar meu Pro**.
5. Aguarde a tela **Pro ativado**.
6. Selecione **Personalizar agora** para acessar os benefícios.

A chave é vinculada à identidade da TV. Não publique a chave nem a envie em
grupos. Para trocar de aparelho, solicite o desvinculamento antes de ativar na
nova televisão.

## 7. Benefícios Pro

- sete temas prontos;
- duas cores por gradiente;
- cores HEX personalizadas;
- papel de parede próprio;
- cartões compactos, padrões ou amplos;
- preferências visuais incluídas no backup.

Quando a assinatura vence, o aplicativo volta ao tema Free automaticamente. As
preferências Pro permanecem salvas e voltam depois da renovação.

## 8. Renovar a assinatura

1. Faça o novo pagamento mensal diretamente com Pedro.
2. A licença existente receberá mais 30 dias.
3. A TV verifica a renovação automaticamente quando estiver conectada.
4. Para consultar imediatamente, abra **Nexa TV Pro → Atualizar assinatura**.

Se a assinatura ainda possui dias restantes, eles são preservados. Se já venceu,
os 30 dias começam no momento da renovação.

## 9. Backup e atualização

Antes de instalar uma versão nova:

1. Abra **Configurações → Backup e restauração**.
2. Selecione **Exportar configuração** e escolha onde salvar o JSON.
3. Instale a nova versão por cima da atual.
4. Se houver conflito de assinatura, desinstale a antiga somente depois de
   confirmar que o backup foi salvo.
5. Na versão nova, selecione **Importar configuração**.

A licença não é transferida pelo backup. Ela continua ligada à identidade da
instalação original; em uma reinstalação completa pode ser necessário informar a
chave novamente ou solicitar o reset das TVs vinculadas.

## 10. Tela inicial padrão

Abra **Engrenagem → Tela inicial padrão**. Se o firmware oferecer a seleção,
escolha Nexa TV. Alguns televisores não permitem substituir o launcher; nesses
casos, abra o Nexa TV normalmente pela lista de aplicativos.

Para desfazer, escolha o launcher original nas configurações do Android ou
desinstale o Nexa TV. Nunca remova componentes do sistema por comandos ADB.

## 11. Solução de problemas

### O APK não instala

- confirme que a TV possui Android 8.0 ou superior;
- verifique se a instalação por fontes desconhecidas foi autorizada;
- se aparecer conflito de assinatura, exporte o backup e remova a versão antiga;
- baixe o arquivo novamente pelo GitHub oficial.

### A chave não ativa

- confira letras, números e hífens;
- verifique a conexão com a internet;
- confirme que a chave ainda não venceu;
- confira se o limite de TVs do plano foi atingido;
- versões de prévia não aceitam chaves comerciais.

### O Pro desapareceu

- confira a data de validade em **Configurações → Nexa TV Pro**;
- conecte a TV à internet e use **Atualizar assinatura**;
- confirme se o pagamento mensal foi renovado;
- se a TV foi trocada ou reinstalada, solicite suporte para desvinculação.

### O layout está cortado

- confirme que a resolução está em 16:9;
- desative zoom ou ampliação de tela no sistema da TV;
- teste com o tamanho de texto padrão;
- informe o modelo da TV e envie uma foto da tela para correção específica.

## 12. Segurança

Baixe o Nexa TV somente do repositório oficial. O aplicativo não solicita
contatos, microfone ou armazenamento amplo e não instala atualizações em
silêncio. Nunca compartilhe chaves de licença ou arquivos recebidos de perfis não
oficiais.
