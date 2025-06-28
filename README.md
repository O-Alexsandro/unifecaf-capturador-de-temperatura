# 🌤️ Capturador de Temperatura
Portfólio - UNIFECAF

# Descrição
Uma aplicação Python com interface gráfica feita em Tkinter que coleta a **temperatura atual**, **sensação térmica** e **umidade** da cidade de **São Paulo (SP)** diretamente do site [Climatempo](https://www.climatempo.com.br/). Os dados são automaticamente salvos em uma planilha Excel (`temperaturas-salvas.xlsx`).

---

## 🚀 Funcionalidades

- Captura:
  - 🌡️ Temperatura atual
  - 🔥 Sensação térmica
  - 💧 Umidade
  - 🗓️ Data e 🕐 Hora da coleta
- Interface amigável com botão para iniciar a coleta
- Os dados são salvos automaticamente na próxima linha disponível da planilha
- Integração com o navegador Google Chrome via Selenium

---

## 🖼️ Interface

A interface é simples, com:
- Um botão amarelo: **"Pesquisar a temperatura atual"**
- Visual com tema azul-claro (cor de céu) e emojis climáticos ☀️
- Exibição dos dados coletados diretamente na janela

---

## 📁 Estrutura da Planilha

Os dados são salvos no arquivo `temperaturas-salvas.xlsx` na aba `Clima` com as colunas:

| Temperatura | Sensação | Umidade | Data       | Hora     |
|-------------|----------|---------|------------|----------|
| 25°         | 26°      | 60%     | 28/06/2025 | 17:45:01 |

---

## 🧰 Tecnologias Utilizadas

- Python 3.11
- [Selenium](https://pypi.org/project/selenium/)
- [Tkinter (GUI padrão do Python)](https://docs.python.org/pt-br/3/library/tkinter.html)
- [openpyxl](https://openpyxl.readthedocs.io/en/stable/)

---

## ✅ Requisitos

- Navegador **Google Chrome** instalado
- **ChromeDriver** compatível com a sua versão do Chrome (adicione ao PATH ou mantenha na mesma pasta do script)

### Instalação das dependências

```bash
pip install selenium openpyxl

```

## ⚡ Como Executar

1. Clone o repositório:

   `git clone https://github.com/O-Alexsandro/unifecaf-capturador-de-temperatura.git` 

   `cd unifecaf-capturador-de-temperatura`

2. Execute a aplicação:

   `python Capturador.py`

## 👨‍💻 Autor

**Alexsandro Ribas**  

--- 
