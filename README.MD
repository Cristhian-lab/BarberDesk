==============================================================
  BarberDesk - Sistema de gestão para barbearia (versão 2.0)
==============================================================

O que a atividade pede e onde está cada item nesta pasta:

1) NOME DO SOFTWARE E LOGOTIPO NAS TELAS
   Nome: BarberDesk
   Logotipo: pasta "3 - Logotipo" (logo.png e logoBarberDesk.ico).
   A logo aparece na tela de abertura, no login, no menu lateral,
   na barra de título das janelas e na barra de tarefas do Windows.
   Prints: pasta "5 - Telas do sistema (com a logo)".

2) ARQUIVO EXECUTÁVEL DO PROJETO (.jar)
   Pasta "1 - Executavel JAR" -> BarberDesk.jar
   Para rodar: java -jar BarberDesk.jar
   (precisa do Java 17 ou mais novo e do MySQL/XAMPP ligado na porta 3306.
   Se não conectar, o sistema abre uma tela para configurar o banco.)

3) EXECUTÁVEL .EXE COM A LOGO COMO ÍCONE (versão portátil)
   Pasta "2 - Executavel EXE (portatil)\BarberDesk" -> BarberDesk.exe
   Dê dois cliques no BarberDesk.exe. Ele já vem com Java e banco de
   dados (MariaDB) embutidos, então não precisa instalar nada.
   IMPORTANTE: para levar a outro computador, copie a pasta "BarberDesk"
   inteira, não só o .exe (o Java e o banco ficam ao lado dele).

4) CÓDIGO-FONTE COMPLETO (para o repositório público no GitHub)
   Pasta "4 - Codigo-fonte (projeto)\BarberDesk"
   - src\main\java\br\com\barberdesk\   código-fonte Java
   - src\main\resources\               logo, script SQL e configuração
   - database\barberdesk.sql           banco de dados
   - build.bat                         gera o BarberDesk.jar
   - empacotar.bat                     gera o BarberDesk.exe com a logo
   - executavel\                       .jar e .exe prontos
   - README.md                         página de apresentação do GitHub
   A pasta já é um repositório git pronto. Para publicar pelo
   GitHub Desktop: File > Add local repository > escolha esta pasta >
   Publish repository (desmarque "Keep this code private").

ACESSO INICIAL AO SISTEMA
   Login: henrique@barbearia.com
   Senha: 123456

Equipe: Projeto de Extensão (4º período), UniRios.
