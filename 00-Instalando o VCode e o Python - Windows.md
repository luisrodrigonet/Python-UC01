
# **Instalação do Visual Studio Code e Python 3 no Windows**  

Este guia demonstra passo a passo como instalar o **Visual Studio Code (VS Code)** e o **Python 3** em um computador com **Windows 11**, incluindo configurações essenciais para desenvolvimento.  

---

## **📥 Passo 1: Baixar e Instalar o Python 3**  

### **1. Acesse o site oficial do Python**  
🔗 [https://www.python.org/downloads/](https://www.python.org/downloads/)  

![Site do Python](https://www.python.org/static/img/python-logo.png) *(Imagem ilustrativa)*  

### **2. Faça o download da versão mais recente**  
- Clique em **"Download Python 3.x.x"** (a versão mais recente).  

### **3. Execute o instalador**  
- Abra o arquivo baixado (ex: `python-3.x.x-amd64.exe`).  
- **Marque a opção:**  
  ✅ **"Add Python to PATH"** (Isso permite usar o Python no terminal).  
- Clique em **"Install Now"**.  

![Instalador do Python](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*0CFJAW0h2vZ3O4YpU4WvXg.png) *(Imagem ilustrativa)*  

### **4. Verifique a instalação**  
- Abra o **Prompt de Comando (CMD)** e digite:  
  ```bash
  python --version
  ```
- Se aparecer a versão (ex: `Python 3.12.0`), a instalação foi bem-sucedida.  

---

## **💻 Passo 2: Baixar e Instalar o Visual Studio Code**  

### **1. Acesse o site do VS Code**  
🔗 [https://code.visualstudio.com/download](https://code.visualstudio.com/download)  

![Site do VS Code](https://code.visualstudio.com/assets/images/homepage/screenshot-win.png) *(Imagem ilustrativa)*  

### **2. Faça o download para Windows**  
- Clique no botão **"Windows"** (versão Stable).  

### **3. Execute o instalador**  
- Abra o arquivo baixado (`VSCodeSetup-x64-x.x.x.exe`).  
- Siga as instruções padrão.  
- **Opcional:** Marque as opções:  
  ✅ **"Adicionar ação 'Abrir com Code' ao menu de contexto do Windows"**  
  ✅ **"Registrar o Code como editor para tipos de arquivo suportados"**  

### **4. Abra o VS Code**  
- Após a instalação, abra o programa.  

---

## **⚙️ Passo 3: Configurar o VS Code para Python**  

### **1. Instale a extensão Python**  
- No VS Code, clique no ícone de **Extensões** (📦) ou pressione `Ctrl+Shift+X`.  
- Busque por **"Python"** (desenvolvido pela Microsoft) e clique em **"Install"**.  

![Extensão Python no VS Code](https://code.visualstudio.com/assets/docs/python/python-tutorial/python-extension-marketplace.png) *(Imagem ilustrativa)*  

### **2. Selecione o Interpretador Python**  
- Abra um novo terminal (`Ctrl+Shift+``) ou crie um arquivo Python (`.py`).  
- No canto inferior direito, clique no interpretador Python (ex: `Python 3.x.x`).  
- Selecione a versão instalada.  

### **3. Execute um código de teste**  
- Crie um arquivo (`teste.py`) e digite:  
  ```python
  print("Olá, Mundo!")
  ```
- Execute com `F5` ou clique em **"Run Python File"**.  
