# trabalho_SO

@ECHO OFF

echo ==================================================================================

echo Este programa cria pastas listas elas e informa sobre o hardware deste computador

echo ==================================================================================

pause 

echo =====================================================

echo	Aperte Enter para continuar e criar uma pasta

echo ====================================================

mkdir Pasta_Arquivos

cd Pasta_Arquivos

mkdir Fotos

mkdir Planilha_de_gastos

mkdir Informacoes_Academicas

mkdir Documentos1

echo =================================

echo As seguintes pastas foram criadas:

dir C:\Users\1144004239\Desktop\Pasta_Arquivos

pause

echo ===========================================

echo A pasta Documentos1 sera excluida

echo ===========================================

del Documentos1

echo ==========================================

echo A pasta Documentos1 foi excluida

echo ===================================================

echo Estes sao os arquivos atuais da pasta Pasta_Arquivos

dir C:\Users\1144004239\Desktop\Pasta_Arquivos


pause

echo =========================================

echo Essas sao as informacoes do seu computador

echo =========================================

systeminfo

pause


echo =========================================

echo O seu computador passara por um verificacao de possiveis erros 

echo =========================================

sfc /scannow

pause


echo ========================================

echo Esses sao os processos em execucao no momento 

echo ========================================

tasklist

pause

echo =============================

echo Sera verificado o seu ping 

ping ww.google.com

pause

echo =============================

echo Alguns comandos uteis 

help

pause 

echo ===============================

echo A lista de comandos chegou ao fim 

echo ===============================
