## 🌙 Luna IA — Inteligência Artificial no Terminal (Modo TXT)

**Luna IA** é uma assistente de linha de comando em **shell script** com integração em **Python e AIML**, projetada para funcionar **totalmente em modo texto (terminal)**, mesmo em sistemas leves, servidores ou ambientes offline.

Ela combina automação em bash, inteligência artificial básica, e utilitários práticos para o dia a dia no Linux, criando uma experiência de “assistente pessoal” acessível direto do console.

---

### 🧩 Estrutura do Projeto

| Arquivo / Script              | Função                                                                 |
| ----------------------------- | ---------------------------------------------------------------------- |
| **ia.sh**                     | Inicializa a IA Luna no terminal (modo texto).                         |
| **ia.py**                     | Núcleo em Python que interpreta e responde via AIML.                   |
| **basic.aiml**                | Base de conhecimento AIML com respostas automáticas e personalizáveis. |
| **clima.json / prevtempo.sh** | Consulta e exibe a previsão do tempo.                                  |
| **dolar.sh**                  | Mostra a cotação atual do dólar.                                       |
| **gasolina.sh**               | Obtém o preço médio atual da gasolina.                                 |
| **hora.sh / time.sh**         | Mostra ou fala a hora atual no formato 12h/24h.                        |
| **biohack.sh**                | Script de automação e ajustes rápidos no sistema.                      |
| **disco.sh**                  | Gera relatórios sobre o uso do disco e partições.                      |
| **myip.sh**                   | Exibe o IP público e local da máquina.                                 |
| **scanrede.sh**               | Varre a rede local em busca de hosts ativos.                           |
| **limpa.sh**                  | Limpa arquivos temporários e otimiza o sistema.                        |
| **code.sh**                   | Permite executar snippets de código diretamente pela IA.               |
| **install.sh**                | Instala dependências e configurações iniciais.                         |
| **std-startup.xml**           | Arquivo de inicialização AIML (respostas padrão).                      |
| **.termux/tasker/**           | Integração opcional com o Tasker (Android/Termux).                     |

---

### ⚙️ Instalação

```bash
git clone https://github.com/seuusuario/LunaIA.git
cd LunaIA/Bot
chmod +x *.sh
./install.sh
```

---


📋 Pré-requisitos


### ⚙️ Instalação no Linux

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install bc jq curl git nmap wget python3 python3-pip espeak libxml2 libxslt termux-api -y
```

Instale as bibliotecas Python necessárias:

```bash
pip3 install BeautifulSoup4 requests lxml python-aiml
```

---

### 💬 Como usar

Inicie a IA com:

```bash
./ia.sh
```

Depois basta conversar em texto:

```
> Olá Luna
Luna: Olá! Como posso ajudar você hoje? 🌙
```

---

### 🧠 Recursos

* ✨ Interface 100% em modo texto
* ⚙️ Totalmente offline (sem dependência de nuvem)
* 🧩 Expansível com módulos em bash ou Python
* 🔗 Compatível com **Termux**, **Ubuntu**, **Debian**, **Alpine** e derivados
* 🔉 Suporte a voz (opcional via `espeak` ou `gTTS`)
* 🌐 Scripts utilitários integrados (rede, clima, hora, sistema etc.)

---

### 📜 Licença

Distribuído sob a **MIT License**.
Livre para estudar, modificar e melhorar — contribuições são bem-vindas! 🧑‍💻

---

Quer que eu gere esse texto já formatado como um **README.md** com emojis, cabeçalhos e comandos prontos (para colocar direto no GitHub)?
