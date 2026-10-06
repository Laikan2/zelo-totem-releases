# ZELO Totem para Windows

Pacotes oficiais do emissor de senhas ZELO. Este repositório distribui somente documentação, pacotes e metadados assinados de atualização.

[Baixar a versão atual](https://github.com/Laikan2/zelo-totem-releases/releases/latest/download/zelo-totem-windows.zip) · [Notas das versões](https://github.com/Laikan2/zelo-totem-releases/releases)

## Configuração inicial

1. Extraia a pasta inteira em um local permanente. Mantenha todos os arquivos juntos.
2. Abra **ZELO Totem.exe**, entre na conta ZELO e escolha a unidade e o ponto autorizado.
3. Escolha a impressora térmica USB e o papel de 58 ou 80 mm. Use **Imprimir teste** e confira a saída do papel.
4. Marque a abertura junto com o Windows, se desejar, e clique em **Salvar e iniciar totem**.

O programa funciona pela internet, com o site ZELO configurado. Cada empresa usa sua própria conta e dispositivos. Não há emissão offline. F11 pede novo login para abrir a manutenção.

## Atualizações automáticas

A versão 2.4 habilita atualizações automáticas. Computadores com 2.3 ou anterior precisam receber o pacote completo 2.4 uma vez.

O programa consulta a versão estável um minuto após abrir e a cada seis horas. Na manutenção, após o login, **Verificar atualização** permite consultar na hora. Downloads são verificados por assinatura RSA-SHA256 e hashes dos arquivos; nenhuma senha do GitHub é necessária.

A atualização preparada entra na **próxima abertura normal**, sem interromper emissão ou impressão. O programa mantém a conta, o ponto, a impressora e o perfil de sessão. O atalho original continua funcionando. Se a nova versão não inicializar o WebView2, a versão anterior é restaurada.

No site, **Administração → Totens e impressão** mostra a versão e o estado recebidos dos equipamentos. Mudanças nas páginas e nos cadastros do site chegam online, sem atualizar o EXE.

## Requisitos

Windows 10/11 de 64 bits, .NET Framework 4.6.2 ou superior, Microsoft Edge WebView2 Runtime, internet e driver oficial da impressora. O envio ao driver não confirma a saída física do papel.

A assinatura dos pacotes é distinta de Authenticode. Os executáveis ainda não possuem certificado Authenticode.

Não envie código-fonte, banco, contas, senhas ou chaves privadas para este repositório.
