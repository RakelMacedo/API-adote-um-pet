## 🐾 API-adote-um-pet

Projeto desenvolvido durante o Workshop Multi-Stack 3.0 da TreinaWeb.  

Com o objetivo de servir um aplicativo de Pets para adoção. Dentre as funcionalidades, pode-se cadastrar Adoções e Pets e listá-las, também enviamos um e-mail para o responsavél da adoção do pet confirmando a adoção e enviando algumas informações sobre o mesmo. 

#

### 📑 Versões das tecnologias usadas:

<table>
  <tr>
    <td>Python</td>
    <td>Django</td>    
    <td>Django REST framework</td>
  </tr>
  <tr>
    <td>3.*</td>
    <td>4.0.4</td>
    <td>3.13.1</td>
  </tr>
</table>

#

### 🔨 Instalando o projeto:

- Clone o repositório:
```
git clone https://github.com/RakelMacedo/API-adote-um-pet.git
```

- Crie seu ambiente virtual:
```
python3 -m venv .venv
```

- E ative seu ambiente virtual:
```
source .venv/bin/activate
```

#

### 📁 Acessando o projeto:

Após clonar o repositório e criar o venv, vá até a pasta raíz do projeto e abra-a com o
editor de texto/IDE da sua escolha.

#

### 🛠️ Abrir e rodar o projeto:

- Instale as depencências:
```
pip install -r requirements.txt
``` 
- Crie a estrutura no banco de dados:
``` 
python manage.py migrate
```  

- Inicie o servidor de desenvolvimento:
```
python manage.py runserver
```

#

### ✅ Prontinho! Você esta pronto para utilizar esta API! =)

- Você pode cadastrar os pets como no exemplo abaixo, através do navegador acessando: http://127.0.0.1:8000/api/pets

![navegador](https://user-images.githubusercontent.com/78339857/175320766-5bba1f05-ded1-4243-a520-2e6a0b286163.jpeg)

#

- Ou diretamente no banco de dados, apertando no + e preenchendo com os dados do pet. 

![banco_vscode](https://user-images.githubusercontent.com/78339857/175322557-9479440a-29d0-48b3-8fe9-efc01a609440.jpeg)

⚠️ Neste exemplo estou usando o *VsCode* junto da extensão *MySQL - Database manager for MySQL/MariaDB, PostgreSQL, SQLite, Redis and ElasticSearch. / Weijan Chen*.

Mas existem outros meios de interagir diretamente com o banco, assim como usar uma ferramenta propria voltada para API's como o Insomnia, por exemplo.

Sinta-se a vontade para fazer do jeito que achar melhor. :)
