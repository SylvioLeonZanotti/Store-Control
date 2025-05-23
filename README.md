# Store Control – Sistema para Pequenos Negócios

![badge](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![badge](https://img.shields.io/badge/python-3.12-blue)
![badge](https://img.shields.io/badge/fastapi-uvicorn-green)
![badge](https://img.shields.io/badge/license-MIT-lightgrey)

## 📋 Descrição

**Store Control** é um sistema completo para pequenos comércios, desenvolvido para facilitar o gerenciamento do seu negócio. Com ele, você pode cadastrar clientes, fornecedores e produtos, controlar o estoque, registrar vendas, organizar as finanças e contar com automações que melhoram o relacionamento com o cliente e a gestão da loja.
![image](https://github.com/user-attachments/assets/ea5896e9-1776-4842-8760-a0c105e1d29c)

## 🚀 Funcionalidades

- Cadastro e gerenciamento de **clientes**
- Cadastro e controle de **fornecedores**
- Cadastro e controle de **produtos** (incluindo estoque mínimo e foto)
- **Controle de estoque** automático
- Registro e histórico de **vendas**
- **Pré-visualização de nota fiscal** durante o processo de compra
- **Envio de nota fiscal** via **WhatsApp** ou **e-mail** diretamente pelo sistema
- Notificação automática após um período sem o cliente visitar a loja
- **Lembrete de aniversário** para clientes, facilitando ações de marketing e fidelização
- Relatórios e dashboards para acompanhamento do negócio
- Gestão de usuários (multiusuário/admin)

## 🛠️ Tecnologias Utilizadas

- **Backend:** [FastAPI](https://fastapi.tiangolo.com/), [SQLModel](https://sqlmodel.tiangolo.com/)
- **Frontend:** HTML5, CSS3, JavaScript, [Jinja2](https://jinja.palletsprojects.com/)
- **Banco de Dados:** SQLite (padrão, mas adaptável para outros)
- **Outros:** Uvicorn, Python 3.12+

## 📦 Estrutura do Projeto
```
app/
├── main.py
├── models.py
├── database.py
├── routers/
│ ├── clientes.py
│ ├── fornecedores.py
│ ├── produtos.py
│ └── vendas.py
├── templates/
│ └── *.html
├── static/
│ ├── css/
│ └── js/
└── db/
```
## 🧑‍💻 Metodologia de Desenvolvimento

- **Desenvolvimento iterativo:** Foco em ciclos curtos, entregando funcionalidades principais e evoluindo conforme feedback.
- **Modularidade:** Cada parte do sistema é independente e organizada em módulos.
- **Automação de processos:** Integração de notificações e envios automáticos para maior produtividade e relacionamento com o cliente.
- **Facilidade de Deploy:** Estrutura pronta para deploy rápido em VPS ou cloud.
- **Código limpo e boas práticas:** Seguindo padrões REST e organização do código.

## 💼 Contato Comercial

Interessado em adquirir o sistema ou desenvolver soluções personalizadas para o seu negócio?  
Entre em contato para consultar preços, serviços e tirar dúvidas:

- 📧 **leonzanotti96@gmail.com**

Será um prazer ajudar você a transformar a gestão do seu comércio!

## 📝 Licença

Este projeto está sob a licença MIT.

