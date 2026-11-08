# 🧠 Context Sanitizer Oracle

Uma Skill para IAs (como o Claude Code) que resolve dois problemas clássicos de desenvolvedores:
1. **Estouro de Contexto:** Lê apenas o "esqueleto" de arquivos Python (imports, classes, assinaturas), economizando até 90% de tokens.
2. **Alucinação de Dependências:** Consulta o PyPI/NPM em tempo real para verificar se um pacote realmente existe antes de sugerir a instalação.

## 🛠️ Como instalar
1. Baixe o conteúdo deste repositório.
2. Copie a pasta para o diretório de skills do seu Claude: `~/.claude/skills/` (No Windows: `C:\Users\SeuUsuario\.claude\skills\`).
3. Reinicie o Claude Code.

## 🚀 Como usar
No terminal:
```bash
# Sanitizar um arquivo (economizar tokens):
python sanitizer.py sanitize seu_arquivo.py

# Verificar se um pacote existe:
python sanitizer.py check nome-do-pacote
