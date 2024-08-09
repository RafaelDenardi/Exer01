### Exercicio01_CICD

Configuração inicial

![configini](https://github.com/user-attachments/assets/0b8700eb-eab3-46c0-8546-4781b00ad175)


a) No working dir, executar o comando:
echo 01 > arquivo.txt

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ ls
@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ echo 01 > arquivo.txt
@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ ls
![echo01](https://github.com/user-attachments/assets/6fb02a16-5f40-4a2b-953e-dfbe27cc4adb)

b) Adicionar o arquivo no staging e conferir o status

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git add .
@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git status
![staging](https://github.com/user-attachments/assets/0f32a611-dd2b-4f37-b1bc-81e105052aae)

c) Commitar o arquivo do staging com a descrição "git add example - arquivo.txt“

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git commit -m "git add example - arquivo.txt"
@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git status
![commit](https://github.com/user-attachments/assets/4bd047d5-579e-493d-bee1-bf163796e278)

d) Sobrescrever o conteúdo do arquivo.txt:
echo 02 > arquivo.txt

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ echo 02 > arquivo.txt
![echo02](https://github.com/user-attachments/assets/017aad37-2289-44aa-8654-1dc32a2dc0c8)

e) Verificar o diffing no arquivo

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git diff
![diff](https://github.com/user-attachments/assets/6f07626c-1bfe-4f02-b2cf-938153d82a19)

f) Adicionar novamente o arquivo no staging e conferir o status

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git add .
@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git status
![staging2](https://github.com/user-attachments/assets/94c35264-575a-472d-bd2e-1df29fed00eb)

g) Verificar o diffing no arquivo

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git diff
h) Sobrescrever o conteúdo do arquivo.txt:
echo 03 > arquivo.txt

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ echo 03 > arquivo.txt
![echo03](https://github.com/user-attachments/assets/c2065c2f-b0ff-4d26-b5d3-9768d4b13ede)

i) Verificar o diffing no arquivo

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git diff
![diff2](https://github.com/user-attachments/assets/c596c726-fd40-4dbc-b035-779289c91e87)

j) Fazer o restore do arquivo da área de staging e verificar o status

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git restore arquivo.txt
@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git status
![restore](https://github.com/user-attachments/assets/b145349a-2c33-4cac-a6b3-d0e94900b1f5)

k) Realizar o commit do arquivo e verificar o log

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git commit -m "commit arquivo.txt"
@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git log
![commit2](https://github.com/user-attachments/assets/815bfb8e-2c49-4c28-99b9-d17bdc582643)

l) Adicionar um arquivo gitignore com o seguinte conteúdo:
*.txt

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ vi .gitignore
@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ cat .gitignore
![gitignore](https://github.com/user-attachments/assets/bb272bcb-9300-4d32-9304-0ba4ba183a46)

m) Criar um arquivo novo.txt e verificar o status

@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ echo > novo.txt
@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ ls
@RafaelDenardi ➜ /workspaces/codespaces-blank/exer01 (main) $ git status
![novo](https://github.com/user-attachments/assets/b780cceb-ccba-4b5f-af39-abc2017eb162)

