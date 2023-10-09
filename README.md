# CrackSleeve4.9

CobaltStrike4.9 Sleeve解密文件, 仅作备份使用.

还需要修改TeamserverImage文件，暂不外放。

将cobaltstrike-client.jar和CrackSleeve.java放一起

编译( javac -encoding UTF-8 -classpath cobaltstrike-client.jar CrackSleeve.java)

解密文件( java -classpath cobaltstrike-client.jar;./ CrackSleeve decode)

无需输入Key,加密文件( java -classpath cobaltstrike-client.jar;./ CrackSleeve encode)

将解密后的sleeve文件夹替换jar包中的文件夹
