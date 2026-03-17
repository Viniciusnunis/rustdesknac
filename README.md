# RustDesk Custom Builder — Nacional Automação

Repositório para gerar o cliente RustDesk personalizado com a marca da empresa.

## Como gerar um novo instalador

1. Acesse a aba **Actions** no GitHub
2. Clique em **Build Custom RustDesk Client**
3. Clique em **Run workflow**
4. Preencha os campos:
   - **Nome do aplicativo** (ex: Nacional Automacao Remote)
   - **IP do servidor** (ex: 72.60.254.113)
   - **Cor principal** (ex: #ee3520)
5. Clique em **Run workflow** (botão verde)
6. Aguarde ~40 minutos
7. Baixe o `.exe` na seção **Releases** ou **Artifacts**

## Personalizar logo e ícone

Coloque os arquivos na pasta `assets/`:
- `assets/logo.png` — Logo principal (256x256 recomendado)
- `assets/icon.ico` — Ícone do Windows

Faça commit e depois rode o workflow.

## Estrutura

```
.github/
  workflows/
    build.yml     ← Workflow de compilação
assets/
  logo.png        ← Sua logo (coloque aqui)
  icon.ico        ← Seu ícone (coloque aqui)
README.md
```
