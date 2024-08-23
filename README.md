Comandos com escrita técnica - 
-Crie um novo repositório no github chamado "cltversion";
-Abra o terminal do seu código em html no vscode;
-Nesse terminal, digite o comando para inicializar o diretório como o repositório:
git init
-Após isso use esse comando para adiconar os arquivos do seu projeto:
git add .
-Agora faça um commit com uma mensagem opcional
git commit -m "first commit"
-E então digite mais esse comando:
git branch -M main
-Use mais esse comando para conectar seu repositório local ao repositório remoto no GitHub:
git remote add origin "URL do repositório"
-O ultimo comando enviará seu código ao github:
git push -u origin main
Com isso, os passos estarão concretizados com sucesso!

Modelo de trabalho (razão de cada branch) -
*Branch-css:
A branch-css, ficará responsável pelas mudanças e/ou melhorias no arquivo CSS;
Desenvolvendo uma maior qualidade do software para garantir uma boa experiência UX.
*Branch-bugfix:
Essa branch terá como função a correção de erros do código principal;
Qualquer bug deve ser corrigido sem falta aqui.
*Branch-js:
Responsável pela implementação de javascript ao código principal;
Deve criar funções específicas para um site mais limpo e profissional.
