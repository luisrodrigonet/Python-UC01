
# Tutorial: Criando um Ambiente Virtual no Python

Neste tutorial, vamos aprender a criar um ambiente virtual no Python, associar uma conta do GitHub diferente daquela utilizada fora do ambiente virtual, e clonar e sincronizar um repositório remoto.

#### Passo 1: Criando um Ambiente Virtual

1. **Instale o `virtualenv` (se ainda não tiver instalado):**

```bash
pip install virtualenv
python -m pip install --upgrade pip
```

2. **Crie um diretório para o seu projeto:**

```bash
mkdir python-uc1-venv
cd python-uc1-venv
```

3. **Crie o ambiente virtual:**

```bash
virtualenv venv
```

Isso criará uma pasta chamada `venv` dentro do diretório `meu_projeto`.

4. **Ative o ambiente virtual:**

- No Windows:

```bash
venv\Scripts\activate
```
