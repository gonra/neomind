# neomind
Avaliaçao neomind

O projeto foi montado na plataforma Netbeans usando Glassfish

##1.- Instalaç&atilde;o banco de dados no MySQL

Gerar banco de dados com a plantilha `dumpdevelop.sql`

```
mysql [-u root][-p] < dumpdevelop.sql
```

Gerar usuario `testuser`, com contrasenha `testpass` para acesso a banco de dados.

```
mysql [-u root][-p] < grantuser.sql
```

##2.- Implantar aplicativo no servidor Glassfish

Deploy dos arquivos 
- `Avaliacao/dist/Avaliacao.war`
- `TesteAvaliacao/dist/TesteAvaliacao.war`

 
