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
