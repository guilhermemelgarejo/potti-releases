# Potti — instaladores e atualizações

Instaladores oficiais do Potti para Windows 10 e 11 x64. O código-fonte é mantido em um repositório privado.

## Instalar

Acesse a [versão mais recente](https://github.com/guilhermemelgarejo/potti-releases/releases/latest) e baixe `Potti_<versão>_x64-setup.exe`.

A partir da versão 0.2.0, o aplicativo avisa quando existe uma nova versão e permite atualizar com sua confirmação. Quem usa 0.1.2 ou anterior precisa instalar a 0.2.0 manualmente uma vez; os dados são mantidos.

O instalador baixa o WebView2 automaticamente caso o componente esteja ausente. Após instalar, o Potti funciona sem internet.

## Dados

Sócios, mensalidades e livros ficam na máquina do usuário. Antes de instalar uma atualização pelo app, o Potti guarda uma cópia dos dados na pasta local de backups.

Você também pode exportar e restaurar backups em **Dados e backups**.

Os arquivos `.sig` e `latest.json` permitem ao aplicativo verificar a autenticidade das atualizações.
