# IEC-Fatec

# Fluxo de Trabalho Git Realizado

1. Criação da branch development a partir da main:
	- Comando: `git checkout -b development`
	- Cria uma nova branch chamada development baseada na main.

2. Envio da branch development para o repositório remoto:
	- Comando: `git push --set-upstream origin development`
	- Publica a branch development no GitHub e define o rastreamento remoto.

3. Criação de uma branch de feature a partir da development:
	- Comando: `git checkout -b feature/exemplo`
	- Cria uma nova branch para implementar uma nova funcionalidade ou alteração.

4. Realização de alterações no projeto (ex: edição do index.html).

5. Commit das alterações na branch de feature:
	- Comando: `git add .` seguido de `git commit -m "feat(exemplo) texto mudado em index.html"`
	- Adiciona e registra as alterações realizadas.

6. Envio da branch de feature para o repositório remoto:
	- Comando: `git push --set-upstream origin feature/exemplo`
	- Publica a branch de feature no GitHub.

7. Merge da branch de feature na development:
	- Comando: `git checkout development` seguido de `git merge feature/exemplo`
	- Integra as alterações da feature na branch de desenvolvimento.

8. Envio da branch development atualizada para o repositório remoto:
	- Comando: `git push`
	- Atualiza a branch development no GitHub com as novas alterações.

Esse fluxo segue boas práticas de versionamento, facilitando o controle de alterações e a colaboração em equipe.