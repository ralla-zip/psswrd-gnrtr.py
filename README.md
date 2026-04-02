# 🔐 Gerador de Senhas

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

Projeto pessoal para gerar senhas e PINs aleatórios. Nasceu como um script Python de terminal e ganhou uma interface web minimalista ao longo do caminho.

---

## 📦 O que tem aqui

| Arquivo | O que faz |
|---|---|
| `password_generator.py` | Gera senhas com letras, números e símbolos via terminal |
| `pin_generator.py` | Gera PINs numéricos via terminal |
| `index.html` | Interface web com os dois geradores, indicador de força e botão de copiar |

---

## 🚀 Como rodar

### Versão Python (terminal)

Você precisa do Python 3.9 ou superior instalado.

```bash
# Clone o repositório
git clone https://github.com/ralla-zip/password_generator.git
cd password_generator

# Gerador de senhas
python password_generator.py

# Gerador de PIN
python pin_generator.py
```

Vai aparecer um menu no terminal pedindo pra você escolher o tamanho. É só digitar a opção e a senha aparece.

### Versão Web (interface)

Sem instalação nenhuma — é só abrir o arquivo no browser:

```bash
# Abra direto pelo terminal...
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux

# ...ou arraste o arquivo pro browser mesmo
```

---

## 🛠 Tecnologias

**Python**
- `random` — geração dos valores aleatórios
- Sem dependências externas

**Web**
- HTML5 + CSS3 + JavaScript puro (sem frameworks)
- `crypto.getRandomValues()` — aleatoriedade criptograficamente segura no browser

---

## 📋 Opções disponíveis

**Senha** (Python e Web)
- 8, 12 ou 18 caracteres
- Letras minúsculas, maiúsculas, números e símbolos (`#$%&*?@_-`)
- Na versão web, cada tipo pode ser ativado/desativado individualmente

**PIN** (Python e Web)
- 4, 8 ou 10 dígitos
- Somente números

---

## 💬 Observações

Projeto feito pra aprender. Críticas e sugestões são bem-vindas — abre uma issue ou manda um PR.
