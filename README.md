# AjusteRelatorioDatas.exe / ajuste_relatorio_datas.py

Ferramenta para **atualizar datas em relatórios PDF técnicos**, preservando o layout original.

- Atualiza **todas as datas** no formato `dd MMM yyyy` (ex.: `30 Nov 2025`)
- Ajusta **Test Date** para a nova data
- Ajusta a coluna **Calibration Date (15 posições)** da página 2 para **NOVA DATA - 6 meses**
- Mantém o layout (apenas sobrescreve o texto das datas)

---

## 1. Tecnologias

- Python 3.9+ (testado em Windows)
- [PyMuPDF (`fitz`)](https://pymupdf.readthedocs.io/)
- [python-dateutil](https://dateutil.readthedocs.io/)

---

## 2. Instalação (modo Python)

```bash
git clone https://github.com/SEU_USUARIO/AjusteRelatorioDatas.git
cd AjusteRelatorioDatas
pip install -r requirements.txt
