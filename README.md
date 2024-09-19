# Quantum Educacional

Este é o projeto **Quantum Educacional**, uma plataforma desenvolvida em Django para auxiliar no aprendizado e acompanhamento dos usuários no desenvolvimento de suas habilidades em inglês. O projeto inclui funcionalidades para anamnese linguística, rastreamento de progresso e muito mais.

## Tecnologias Utilizadas

- **Django**: Framework web utilizado para a construção da aplicação.
- **SQLite**: Banco de dados padrão usado durante o desenvolvimento.
- **Python**: Linguagem de programação utilizada para backend.
- **HTML/CSS**: Usado para a construção do front-end da aplicação.

## Funcionalidades

- **Anamnese Linguística**: Sistema para entender o nível de inglês dos usuários.
- **Gerenciamento de Conteúdo**: Adicionar, editar e remover materiais de estudo.
- **Rastreamento de Progresso**: Acompanhe o progresso dos usuários na plataforma.
- **Administração**: Sistema de administração completo com Django Admin.

## Como Rodar o Projeto

### Pré-requisitos

- Python 3.x instalado
- Virtualenv instalado (opcional, mas recomendado)

### Passos

1. Clone o repositório:

   ```bash
   git clone https://github.com/usuario/quantum_educacional.git
   cd quantum_educacional
   ```

2. Crie e ative um ambiente virtual:

   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Execute as migrações:

   ```bash
   python manage.py migrate
   ```

5. Execute o servidor de desenvolvimento:

   ```bash
   python manage.py runserver
   ```

6. Acesse a aplicação em [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Estrutura do Projeto

```plaintext
quantum_educacional/
│
├── anamnese/               # Aplicação principal da plataforma
│   ├── migrations/         # Migrações do banco de dados
│   ├── static/             # Arquivos estáticos (CSS, JS, imagens)
│   ├── templates/          # Templates HTML
│   └── views.py            # Lógica das views
│
├── quantum_educacional/    # Diretório do projeto principal
│   ├── settings.py         # Configurações do Django
│   ├── urls.py             # Rotas do projeto
│   └── wsgi.py             # Configuração WSGI
│
├── manage.py               # Script para gerenciar o projeto
└── README.md               # Documentação do projeto
```

## Próximas Funcionalidades

- Implementar sistema de login para usuários.
- Criar painel de acompanhamento de desempenho.
- Desenvolver API para integração com outras plataformas.

## Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto.
2. Crie uma branch (`git checkout -b minha-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Envie a branch (`git push origin minha-feature`).
5. Abra um Pull Request.

**Quantum Educacional** - Transformando o aprendizado de inglês!
