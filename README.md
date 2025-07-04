# 💰 Controle Financeiro Pessoal com Django

Um sistema completo para organizar suas finanças, com gráficos interativos, exportação de dados e autenticação de usuários.

## 🚀 Funcionalidades

- Cadastro de lançamentos: receitas e despesas
- Filtros por data e categoria
- Cartões resumo com total de receitas, despesas e saldo
- Exportação para CSV e Excel
- Gráficos (pizza e barras) com Chart.js
- Dashboard mensal com filtro por ano
- Exportar gráficos em PNG ou PDF
- Login e logout de usuários

## 🛠️ Tecnologias utilizadas

- Django 4.x
- SQLite (padrão)
- Bootstrap 5
- Chart.js
- jsPDF
- HTML5 & CSS3

## ▶️ Como executar o projeto

```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/controle-financeiro.git
cd controle-financeiro

# Crie o ambiente virtual e ative
python -m venv venv
venv\Scripts\activate   # no Windows
source venv/bin/activate  # no Linux/macOS

# Instale as dependências
pip install -r requirements.txt

# Execute as migrações e crie um superusuário
python manage.py migrate
python manage.py createsuperuser

# Inicie o servidor
python manage.py runserver


Acesse em: http://127.0.0.1:8000/

📁 Estrutura do Projeto
cpp
Copiar
Editar
controle_financeiro/
├── contas/
│   ├── templates/
│   ├── static/
│   └── views.py, models.py, forms.py, etc.
├── controle_financeiro/
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md
🙋‍♂️ Autor
Desenvolvido com 💻 por Matheus Junior