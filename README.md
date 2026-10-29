Método 1 — PowerShell

O PowerShell permite executar comandos administrativos no Windows. O projeto MAS documenta uma opção de inicialização por meio de um script remoto.

Passo a passo

Abra o menu Iniciar do Windows.

Pesquise por PowerShell e abra o aplicativo.

Antes de executar qualquer comando remoto, verifique a origem e examine o conteúdo do script.

Endereço oficial informado pelo projeto:

https://get.activated.win

O comando abaixo combina irm (para obter conteúdo remoto) com iex (para executá-lo):

irm https://get.activated.win | iex

Atenção: esse comando executa código baixado da internet diretamente no PowerShell. Para uma análise segura, prefira baixar o script, inspecionar seu conteúdo e verificar sua procedência antes de executá-lo.

Alternativa de conexão

O projeto também documenta uma alternativa que utiliza curl.exe com DNS sobre HTTPS (DoH). A disponibilidade depende da versão do Windows e das ferramentas instaladas.

Consulte a documentação oficial antes de utilizar métodos alternativos:

https://massgrave.dev/

Próximos passos

Se o script abrir um menu interativo, leia as opções e as respectivas descrições antes de selecionar qualquer método. Verifique também se a opção é compatível com a edição do Windows ou Office instalada e com a licença disponível.

Se ocorrer algum erro, consulte:

https://massgrave.dev/troubleshoot

Compatibilidade

A compatibilidade varia conforme a versão do Windows, a edição do produto e o método utilizado. Consulte as fontes oficiais para obter os requisitos atualizados.


Como ativar o Windows / Office / Atualizações de Segurança Estendidas (ESU)?
Método 1 - PowerShell ❤️
Clique no Menu Iniciar , digite PowerShelle abra-o.

Copie e cole o código abaixo e pressione Enter.

Para Windows 8.1, 10 e 11 :

irm https://get.activated.win | iex

Se o link acima estiver bloqueado (pelo seu provedor de internet/DNS), tente isto (requer Windows 10 ou 11 atualizado):

iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)

O script não está sendo executado? Use o Método 2 listado abaixo.

No menu que aparece, digite o número correspondente a uma das opções em verde .

Método 2 - Tradicional (Windows Vista e posterior)

Baixe o roteiro:

MAS_AIO.cmd (Script direto)

MAS_AIO.zip (Caso o script direto esteja bloqueado pelo seu navegador)
Execute o MAS_AIO.cmdarquivo.

No menu que aparece, digite o número correspondente a uma das opções em verde .
