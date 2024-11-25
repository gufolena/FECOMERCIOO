## FECOMERCIOO - Gerenciador de Eventos
Este é um sistema de gestão de eventos desenvolvido para atender às necessidades da FeComércio, garantindo conformidade com a LGPD (Lei Geral de Proteção de Dados) e facilitando o gerenciamento de inscrições e pagamentos. O sistema fornece uma interface intuitiva para organização de eventos, dashboards informativos e pagamentos seguros.

## Funcionalidades
Cadastro e gerenciamento de eventos.
Inscrições online com integração ao sistema de pagamentos.
Painéis administrativos com visualização de participantes e status dos pagamentos.
Área de administrador para gestão de usuários e configurações gerais.
Conformidade com a LGPD para proteção de dados dos usuários.

## Tecnologias Utilizadas
Backend: Python, Django
Banco de Dados: SQLite (padrão, pode ser configurado para outro SGBD)
Frontend: HTML, CSS, JavaScript
Gerenciamento de Pacotes: Pip
Versionamento: Git

## Pré-requisitos
Antes de começar, você precisará ter as seguintes ferramentas instaladas:

Python 3.9 ou superior
Git
Navegador web (para acessar o sistema)

## Como Rodar o Projeto

1. Clone o repositório:
   ```
   git clone https://github.com/gufolena/FECOMERCIOO

2. Acesse o diretório do projeto:

cd FECOMERCIOO

3. Crie um ambiente virtual:
   python -m venv env

4. Ative o ambiente virtual:
   Windows:
   env\Scripts\activate

  Linux/macOS:
    ```
    source env/bin/activate
    ```

5. Instale as dependências:
 
   pip install -r requirements.txt

6. Configure o banco de dados:

   python manage.py migrate

7. Crie um superusuário:
   python manage.py createsuperuser

8. Execute o servidor:

   python manage.py runserver

9. Acesse o sistema no navegador:

Página principal: http://127.0.0.1:8000/
Área de administrador: http://127.0.0.1:8000/admin

## Pré-visualização
![Preview](static/img/fecomercio.png)


## Contribuição
1. Contribuições são bem-vindas! Para contribuir Faça um fork do projeto.
2. Crie uma branch com sua feature (git checkout -b feature/nome-da-feature).
3. Commit suas alterações (git commit -m 'Adicionei uma nova funcionalidade').
4. Envie para o repositório remoto (git push origin feature/nome-da-feature).
5. Abra um Pull Request.

## Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais informações.




