# 💰 Controle Financeiro Pessoal com Django

Este é um sistema completo de controle financeiro pessoal desenvolvido com Django. Ele permite:

✅ Cadastrar receitas e despesas
✅ Filtrar lançamentos por data e categoria
✅ Gerar gráficos dinâmicos (pizza e barras)
✅ Dashboard mensal com filtro por ano
✅ Exportação para CSV, Excel e PDF
✅ Interface simples com Bootstrap
✅ Autenticação de usuários

---

## 🔧 Tecnologias Utilizadas

* Python 3
* Django
* SQLite3
* Bootstrap 5
* Chart.js
* jsPDF

---

## 🚀 Como rodar o projeto localmente

```bash
git clone https://github.com/Matheusjuniorz/controle-financeiro-django.git
cd controle-financeiro-django
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Acesse o projeto em: `http://127.0.0.1:8000/`

---

## 👤 Acesso ao sistema

1. Crie um superusuário para acessar a interface admin:

```bash
python manage.py createsuperuser
```

2. Entre com seu usuário em: `http://127.0.0.1:8000/admin/`

---

## 📦 Funcionalidades

* Tela de login e autenticação
* Lânçamentos financeiros com tipo (Receita ou Despesa)
* Filtro por datas e categoria
* Gráficos com Chart.js
* Dashboard mensal com comparativo
* Exportação de dados (CSV, Excel e PDF)
* Menu de navegação rápido

---

## 📝 Licença

Este projeto é de uso livre para fins de estudo e aprendizado. Fique à vontade para usar e modificar.

---

Desenvolvido com 💻 por [Matheus Junior](https://github.com/Matheusjuniorz)
