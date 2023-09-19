
Quando criar uma nova pasta e for subir para o Git,
faça os seguintes passos básicos:

1)  Após criar o repositório no github e
	ter  certeza de estar dentro da pasta.
	
2)  No CMD digite os comandos:
	
	git status - para ver se ainda não é um repositório
	git init   - para iniciar o repositório
	git status - para ver se o repositório foi criado e que falta commitar
	git add .  - para adicionar tudo para ser copmitado
	git commit -am "Nome desse primeiro Commit" - cria o commit
	
3)  Depois pegue a linha de comando do Github do repositório criado
	
	git remote add origin https://github.com/sua_pasta/nome_do_repositorio.git
	git branch -M main      - para renomear a branch atual para `main``

4)  Agora é só enviar os arquivos do repositório local para o remoto
	git push -u origin main - para enviar os arquivos para o repositório remoto
	
	git log	- para ver o justórico dos commits feitos.
	
	
	

