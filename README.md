# AjusteRelatorioDatas.exe / ajuste_relatorio_datas.py

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Windows](https://img.shields.io/badge/Platform-Windows-blue)
![PDF](https://img.shields.io/badge/PDF-automation-orange)

Ferramenta corporativa para **atualizar datas em relatórios PDF técnicos**, preservando o layout original.

---

## 🚀 Funcionalidades

✔ Atualiza **todas as datas** no formato `dd MMM yyyy`  
✔ Ajusta o **Test Date** para a nova data  
✔ Ajusta a coluna **Calibration Date (15 posições)** da página 2 para  
➡️ **NOVA DATA - 6 meses**  
✔ Não move texto — apenas sobrescreve a data  
✔ Funciona em **qualquer computador**, sem instalar Python (via EXE)

---

## 🧩 1. Tecnologias

- Python 3.9+
- PyMuPDF (fitz)
- python-dateutil
- GitHub Actions (compilação automática)

---

## 📦 2. Instalação (modo Python)

```bash
git clone https://github.com/Tricoloreeu/AjusteRelatorioDatas.git
cd AjusteRelatorioDatas
pip install -r requirements.txt

## 🖥️ 3. Execução via Python (modo desenvolvedor)

Se você deseja rodar a ferramenta diretamente pelo script Python:

1. Certifique-se de ter Python 3.9+ instalado  
2. Instale as dependências:

```bash
pip install -r requirements.txt

Execute o comando:

python ajuste_relatorio_datas.py
Informe o nome do PDF (ex: input.pdf)

Digite a nova data no formato dd MMM yyyy (ex: 30 Nov 2025)

O PDF editado será salvo como: output.pdf


