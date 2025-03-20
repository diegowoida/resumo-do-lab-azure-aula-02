Entre no [portal do Azure](https://portal.azure.com/).

# Criar máquina virtual  
1) Digite _máquinas virtuais_ na pesquisa.

2) Em **Serviços**, selecione **Máquinas virtuais**.

3) Na página **Máquinas virtuais**, clique em **Criar** e selecione **Máquina virtual do Azure**. A página **Criar uma máquina virtual** é aberta.

4) Em **Detalhes da instância**, insira o **nome da máquina virtual** e escolha o _a versão do Sistema Operacional_ desejado. Deixe os outros padrões.

5) Em **Conta de administrador**, forneça um nome de usuário, como azureuser e uma senha. A senha deve ter no mínimo 12 caracteres e atender a [requisitos de complexidade definidos](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/faq#what-are-the-password-requirements-when-creating-a-vm-).
6) Em **Regras de porta de entrada**, escolha **ermitir portas selecionadas** e, em seguida, selecione **RDP (3389)** e **HTTP (80)** na lista suspensa.
7) Deixe os padrões restantes e, em seguida, selecione o botão **Examinar + criar** na parte inferior da página.
8) Após a execução da validação, selecione o botão **Criar** na parte inferior da página.
9) Após a conclusão da implantação, selecione **Ir para o recurso**.  


# Conectar-se à máquina virtual
Inicie uma conexão da área de trabalho remota para a máquina virtual. Estas instruções ensinam a se conectar aàsua VM de um computador com Windows.

1) Selecione **Conectar>RDP** na página de visão geral de sua máquina virtual.

2) Na guia **Conectar-se ao RDP**, mantenha as opções padrão para se conectar por endereço IP pela porta 3389 e clique em **Baixar arquivo RDP**.

3) Abra o arquivo RDP baixado e clique em **Conectar** quando solicitado.

4) Na janela **Segurança do Windows**, selecione **Mais opções** e **Usar uma conta diferente**. Digite o nome de usuário como localhost\\_nome de usuário_, insira a senha que você criou para a máquina virtual e clique em **OK**.

6) Você pode receber um aviso do certificado durante o processo de logon. Clique em **Sim** ou em **Continuar** para criar a conexão.
