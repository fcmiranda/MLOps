# MLOps

## 📋 Descrição

Projeto de MLOps com exemplos de aulas e exercícios práticos.

## 🚀 Como Executar

### Pré-requisitos

- Python 3.13
- Git
- pip (gerenciador de pacotes do Python)

### Instalação

1. **Clone o repositório:**
   ```bash
   git clone <seu-repositório>
   cd mlops
   ```

2. **Crie um ambiente virtual:**
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

### Usando o Mise (Opcional)

Se você usa o [Mise](https://mise.jdx.dev/), pode ativar o ambiente configurado:

```bash
mise install
mise activate
```

### Executando os Notebooks

Os arquivos Jupyter estão organizados em pastas:

- **aula/** - Exemplos de aulas
- **exercicio1/** - Primeiro exercício
- **exercicio2/** - Segundo exercício

Para iniciar o Jupyter:

```bash
jupyter notebook
```

Ou com JupyterLab:

```bash
jupyter lab
```

### Usando MLflow

Para acompanhar experimentos com MLflow:

1. Inicie o servidor MLflow:
   ```bash
   mlflow ui
   ```

2. Acesse a interface em `http://localhost:5000`

## 📁 Estrutura do Projeto

```
mlops/
├── aula/              # Materiais de aula
│   ├── [Dados]_Aula_1_1.ipynb
│   └── *.csv          # Dados de exemplo
├── exercicio1/        # Primeiro exercício
│   └── [Dados]_Exercicio_1.ipynb
├── exercicio2/        # Segundo exercício
│   └── [Dados]_Exercicio_2.ipynb
├── README.md          # Este arquivo
├── mise.toml          # Configuração do Mise
└── .gitignore         # Arquivos ignorados pelo Git
```

## ✨ Features
- Exemplos práticos de MLOps
- Integração com MLflow para rastreamento de experimentos
- Jupyter Notebooks para análise interativa


- Os dados CSV estão inclusos nos diretórios respectivos
