# AjusteRelatorioDatas.exe / ajuste_relatorio_datas.py

Ferramenta para **atualizar datas em relatórios PDF técnicos**, preservando o layout original.

- Atualiza **todas as datas** no formato `dd MMM yyyy` (ex: **30 Nov 2025**)
- Ajusta o **Test Date** para a nova data
- Ajusta a coluna **Calibration Date (15 posições)** da página 2 para **NOVA DATA - 6 meses**
- Mantém o layout (apenas sobrescreve o texto das datas, sem mover nada)

---

## 1. Tecnologias

- Python 3.9+ (testado no Windows)
- [PyMuPDF (fitz)](https://pymupdf.readthedocs.io/)
- python-dateutil

---

## 2. Instalação (modo Python)

```bash
git clone https://github.com/Tricoloreeu/AjusteRelatorioDatas.git
cd AjusteRelatorioDatas
pip install -r requirements.txt

python ajuste_relatorio_datas.py

4. Execução pelo EXE (técnicos de campo)

Copie AjusteRelatorioDatas.exe para uma pasta ou pendrive

Coloque o PDF na mesma pasta

Abra o EXE

Digite o nome do PDF (exemplo: input.pdf)

Digite a nova data no formato dd MMM yyyy

O arquivo resultante será output.pdf
