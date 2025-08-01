# 🚀 Projeto: Alura Apache Spark

Este projeto foi desenvolvido como parte dos estudos do curso de Apache Spark da Alura. O objetivo é aplicar conceitos de processamento distribuído de dados utilizando o Apache Spark com Python, integrando também acesso a arquivos no Google Drive via API.

---

## 📁 Estrutura do Projeto

| Estrutura              | Descrição                                     |
| ---------------------- | --------------------------------------------- |
| `data/`                | Pasta para armazenar dados locais e extraídos |
| `projeto_spark.ipynb`  | Notebook principal com os estudos             |
| `service_account.json` | Chave da conta de serviço (não versionada)    |
| `settings.yaml`        | Configurações para bibliotecas como PyDrive   |
| `.env`                 | Variáveis de ambiente (não versionado)        |
| `requirements.txt`     | Lista de dependências do projeto              |
| `.gitignore`           | Arquivos ignorados no versionamento           |

---

## ⚙️ Requisitos

- Python 3.11+
- Apache Spark instalado (preferencialmente via WSL)
- Conta de serviço configurada no Google Cloud
- Bibliotecas Python listadas em `requirements.txt`

Para instalar as dependências:

```bash
pip install -r requirements.txt
```

## 🔐 Segurança

Os arquivos service_account.json e .env não devem ser versionados. Eles contêm credenciais sensíveis e estão protegidos via .gitignore.

## 🚀 Como executar

1. Instale as dependências com pip install -r requirements.txt
2. Configure o caminho da chave da conta de serviço no .env ou config.json
3. Execute o notebook projeto_spark.ipynb para iniciar os estudos

## 📌 Observações

- Os dados utilizados são armazenados na pasta data/
- O acesso ao Google Drive é feito via API com autenticação por conta de serviço
- O projeto está em desenvolvimento contínuo conforme avanço no curso
