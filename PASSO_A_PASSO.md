

> 1. Abra o **PowerShell como administrador**. Para fazer isso, clique com o botão direito do mouse no ícone do PowerShell e selecione *"Executar como administrador"*.
>
> 2. No PowerShell, digite o seguinte comando e pressione Enter:
>
> ```
> Get-ExecutionPolicy
> ```
>
> Isso exibirá a política de execução atualmente definida.
>
> 3. Se a política de execução estiver definida como *"Restricted"* (Restrita), isso significa que a execução de scripts está desabilitada. Para permitir a execução de scripts, digite o seguinte comando e pressione Enter:
>
> ```
> Set-ExecutionPolicy RemoteSigned
> ```
>
> Isso define a política de execução como *"RemoteSigned"* (Assinada remotamente), que permite a execução de scripts locais assinados digitalmente e scripts remotos não assinados.
>
> Quando solicitado a confirmar a alteração, pressione *"S"* para confirmar e pressione Enter.
>
> Agora você deve conseguir executar scripts.
>
> ---
> Leia o **[aviso!](README.md)**
