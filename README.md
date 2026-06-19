# 🚀 FastDebit
![Status](https://img.shields.io/badge/status-refatotação-orange)

FastDebit é uma aplicação desktop desenvolvida com Tkinter para agilizar a inserção dados na [Plataforma de Gestão de Dívidas](https://divida.apps.tcu.gov.br/calculadora-debito).


## Objetivo

- Separação de responsabilidades
- Estrutura em camadas
- Evolução para aplicação de Design Patterns

---

## Tecnologias Utilizadas

- Python 3.14+
- Tkinter
- Openpyxl
- Pandas
- Programação Orientada a Objetos (POO)

---

## Funcionalidades

- selecionar arquivo
- Escrever

---

## Estrutura

```python
src/
│
├── views/
│ └── form_view.py
│
├── services/
│ ├── conversion.py
│ ├── file.py
│ └── path.py
│
├── repository/
│ └── repository.py
└── main.py
```


- **Views** → Interface gráfica e eventos
- **Services** → Regras de negócio  
- **Src** → Orquestração da aplicação  

Essa separação permite:

- Redução de acoplamento
- Manutenabilidade
- Possível evolução para padrões mais avançados

---

## Screenshots

### Principal

![Interface Principal](docs/screenshots/main.png)



## Demonstração

![Demonstração do Sistema](docs/demo1.gif)

---

## Como exercutar?

### 1) Clone o repositório
```bash

git clone https://github.com/CodePhsp/projeto-fastdebit.git
cd projeto-fastdebit

```

### 2) Crie ambiente virtual
Para o sistema operacional windows

> Dica: você pode escolher qualquer nome para seu ambiente virtual 
```bash
python -m venv .venv
venv\Scripts\activate  
```

Para o sistema operacional Linux
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3) Instale as dependências

```bash
python -m pip install -r requirements.txt
```

### 4) Execute
```bash
cd src
python main.py
```
