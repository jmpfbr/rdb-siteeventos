# 🎫 Sistema de Reservas de Ingressos

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092e20.svg?style=for-the-badge&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-green?style=for-the-badge)

Site fictício desenvolvido para gerenciamento e reserva de ingressos, com foco em persistência de dados e integração com banco de dados relacional.

---

## ⚠️ Requisitos do Sistema

Para rodar este projeto, você precisará ter instalado:

* **PostgreSQL** (Banco de Dados)
* **pgAdmin** (Interface de gerenciamento)
* **Python 3.x**

### 🗄️ Configuração do Banco de Dados
* **Nome do Banco:** `rdb`
* **Senha padrão:** `6921`

---

## 🚀 Tecnologias Utilizadas

- **Linguagem:** Python
- **Framework Web:** Django
- **Banco de Dados:** PostgreSQL
- **Ferramentas:** pgAdmin, pip

---

## 📂 Estrutura do Repositório

```text
.
├── aplic/               # Core do aplicativo (Views e Models)
├── rdb/                 # Configurações do projeto e Banco de Dados
├── media/event_images/  # Armazenamento de imagens dos eventos
├── manage.py            # Script de gerenciamento do Django
├── get-pip.py           # Script auxiliar de instalação
└── README.md            # Documentação
```

⚙️ Como Executar
Clone o repositório:

```text
git clone [https://github.com/jmpfbr/seu-repositorio.git](https://github.com/jmpfbr/seu-repositorio.git)
```

Configure o Banco de Dados:
Crie um banco de dados no PostgreSQL chamado rdb com a senha 6921.

Instale as dependências:

```text
pip install -r requirements.txt
```
(Caso não tenha o arquivo requirements, instale o Django manualmente: pip install django psycopg2)

Rode as migrações:

```text
python manage.py migrate
```

Inicie o servidor:

```text
python manage.py runserver
```

---

🔗 Links Úteis 

Download PostgreSQL

Download pgAdmin

---

👨‍💻 Autor

João Marcos Fierro e Grupo

---

📄 Licença

Fierro Softwares

Este projeto é de uso exclusivamente acadêmico e livre para fins de estudo e consulta.
