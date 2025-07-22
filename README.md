# 🤖 Automação de Cadastro de Produtos com Python

Este projeto tem como objetivo automatizar o processo de cadastro de produtos em um sistema web utilizando Python e a biblioteca PyAutoGUI. A ideia é transformar uma tarefa repetitiva e manual em um processo rápido, eficiente e sem intervenção humana.

---

## 🎯 Objetivo

Automatizar o preenchimento de formulários de cadastro de produtos com dados extraídos de uma planilha `.csv`.

---

## 🧰 Tecnologias e Bibliotecas Utilizadas

- Python 3.x
- PyAutoGUI
- Pandas
- Time

---

## 🚀 Passo a Passo

1. **Abrir o navegador (Opera)** e acessar o sistema de cadastro da empresa:
   - [https://dlp.hashtagtreinamentos.com/python/intensivao/login](https://dlp.hashtagtreinamentos.com/python/intensivao/login)

2. **Fazer login automaticamente** com e-mail e senha pré-definidos.

3. **Importar a base de produtos** (`produtos.csv`) com colunas como:
   - `codigo`, `marca`, `tipo`, `categoria`, `preco_unitario`, `custo`, `obs`

4. **Cadastrar cada produto** preenchendo os campos do formulário web com base na planilha.

5. **Repetir o processo** até o fim da planilha.

---

## 📁 Estrutura do Projeto


---

## ⚙️ Como Usar

> ⚠️ **Importante:** Esse script depende de coordenadas exatas da sua tela e da resolução usada. Pode ser necessário ajustar os valores de `pyautogui.click(x=..., y=...)`.

1. Instale as bibliotecas necessárias:

```bash
pip install pandas pyautogui

python cadastro_automatico.py
