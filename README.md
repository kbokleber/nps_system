# Sistema NPS (Net Promoter Score)

Sistema desenvolvido em Django para gerenciamento de pesquisas NPS (Net Promoter Score).

## Funcionalidades

- Cadastro de clientes
- Cadastro de respondentes
- Envio automático de pesquisas por e-mail
- Dashboard com resultados
- Suporte a múltiplos idiomas (PT, EN, ES)
- Interface administrativa
- Gerenciamento de pesquisas em lote

## Requisitos

- Python 3.12+
- Django 5.0+
- PostgreSQL
- Outras dependências listadas em requirements.txt

## Instalação

1. Clone o repositório
```bash
git clone https://github.com/SEU_USUARIO/nps_system.git
cd nps_system
```

2. Crie um ambiente virtual
```bash
python -m venv django_venv
source django_venv/bin/activate  # Linux/Mac
django_venv\Scripts\activate     # Windows
```

3. Instale as dependências
```bash
pip install -r requirements.txt
```

4. Configure as variáveis de ambiente
- Crie os arquivos .env_config, .db_env e .email_config com as configurações necessárias

5. Execute as migrações
```bash
python manage.py migrate
```

6. Crie um superusuário
```bash
python manage.py createsuperuser
```

7. Execute o servidor
```bash
python manage.py runserver
```

## Configuração

O sistema requer três arquivos de configuração:

1. .env_config
