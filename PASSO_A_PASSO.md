
>1º Abra o ```PowerShell como administrador```. Para fazer isso, clique com o botão direito do mouse no ícone do PowerShell e selecione ```"Executar como administrador"```.<br>
<br>2º No PowerShell, digite o seguinte comando e pressione Enter:
><br><br>```
Get-ExecutionPolicy```<br>
<br>Isso exibirá a política de execução atualmente definida.
<br><br>
> 3º Se a política de execução for definida como ```"Restricted" (Restrita)```, isso significa que a execução de scripts está desabilitada. Para permitir a execução de scripts, digite o seguinte comando e pressione Enter:<br>
> <br>```Set-ExecutionPolicy RemoteSigned```<br><br>
> Isso define a política de execução como "RemoteSigned" (Assinada remotamente), que permite a execução de scripts locais assinados digitalmente e scripts remotos não assinados.<br><br>
> Quando solicitado a confirmar a alteração, pressione ```"S"``` para confirmar e pressione Enter.<br><br>
Agora você deve conseguir executar scripts<br>
> 
> ---
> Leia o 
>**_[aviso !](README.md)_**