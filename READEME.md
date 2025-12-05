# 🐍 Atividade Prática 1 - Python

Este repositório contém as soluções para a **Atividade Prática 01** do módulo de **Inteligência Artificial** da **Escola da Nuvem**. São 4 programas em Python que demonstram conceitos fundamentais de programação.

## 📚 Atividades Desenvolvidas

### 1. **Prática 01** (`pratica01.py`)
- Imprime a mensagem "Olá, mundo!"
- Primeiro contato com a função `print()`

### 2. **Calculadora de Soma** (`calculadoraSoma.py`)
- Soma dois números predefinidos (12 e 14)
- Demonstra operações aritméticas básicas

### 3. **Calculadora de Volume** (`calculadoraVolume.py`)
- Calcula o volume de uma caixa retangular
- Usa as dimensões: 12cm × 14cm × 20cm
- Mostra cálculo com unidades (cm³)

### 4. **Calculadora de Preço Total** (`calculadoraPrecoTotal.py`)
- Calcula o preço total de uma compra
- Produto: "Cadeira Infantil" a R$ 12.40
- Quantidade: 3 unidades
- Formata valores monetários

## 🚀 Como Executar os Programas

### **No Windows (com Python instalado via Microsoft Store):**

1. **Abra o Terminal:**
   - Pressione `Windows + X`
   - Selecione "Terminal" ou "Windows PowerShell"

2. **Navegue até a pasta dos arquivos:**
   ```powershell
   cd "C:\caminho\para\AtividadePratica1"

# Execute cada programa:

## powershell || cmd 

* python pratica01.py
* python calculadoraSoma.py
* python calculadoraVolume.py
* python calculadoraPrecoTotal.py

💻 Instalação do Python
Para Windows (Método usado - Microsoft Store):
Abra a Microsoft Store no Windows 11

Pesquise por "Python"

Selecione a versão mais recente (ex: Python 3.12)

Clique em "Instalar"

✅ Pronto! Python já estará configurado automaticamente

Verificação da Instalação:
powershell
# No Terminal do Windows 11:
python --version
# Saída esperada: Python 3.x.x

python -c "print('Python instalado com sucesso!')"
# Saída: Python instalado com sucesso!
Alternativa: Instalador Oficial (Windows)
Acesse python.org/downloads

Baixe o instalador para Windows

IMPORTANTE: Marque a opção "Add Python to PATH"

Siga as instruções do instalador

Para Linux (Ubuntu/Debian):
bash
# Atualize os pacotes
sudo apt update

# Instale Python 3
sudo apt install python3 python3-pip

# Verifique a instalação
python3 --version
📁 Estrutura do Repositório
text
AtividadePratica1/
│
├── pratica01.py              # Programa 1: Saudação "Olá, mundo!"
├── calculadoraSoma.py        # Programa 2: Soma de números
├── calculadoraVolume.py      # Programa 3: Cálculo de volume
├── calculadoraPrecoTotal.py  # Programa 4: Cálculo de preço
│
├── README.md                # Este arquivo de instruções
└── .gitignore              # Arquivos ignorados pelo Git
🎯 Saída Esperada dos Programas
Executando pratica01.py:
text
Olá, mundo!
Executando calculadoraSoma.py:
text
2- Calculadora de Soma
Primeiro número: 12
Segundo número: 14
Soma: 12 + 14 = 26
------------------------------
Executando calculadoraVolume.py:
text
3- Calculadora de Volume
Comprimento: 12 cm
Largura: 14 cm
Altura: 20 cm
Volume: 12 × 14 × 20 = 3360 cm³
------------------------------
Executando calculadoraPrecoTotal.py:
text
4- Calculadora de Preço Total
Produto: Cadeira Infantil
Preço unitário: R$ 12.40
Quantidade: 3
Preço total: R$ 12.40 × 3 = R$ 37.20
------------------------------
🔧 Dicas para Trabalhar com Python no Windows 11
Configurar o Terminal:
Use o Windows Terminal (já instalado no Windows 11)

Personalize (Ctrl + ,) para definir Python como padrão

Use tabs para executar vários programas simultaneamente

Editor de Código Recomendado:
VS Code: code.visualstudio.com

Extensões úteis:

Python (Microsoft)

Pylance

Python Indent