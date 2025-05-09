
# 🤝 Como Contribuir com o Projeto

Este projeto utiliza um fluxo de trabalho baseado em **forks** e **pull requests**. Siga as etapas abaixo para colaborar da forma correta.

---

## 🔧 Requisitos

- Ter uma conta no GitHub
- Ter o Git instalado localmente

---

## 📥 1. Faça um fork do repositório

Clique em **Fork** no canto superior direito da página do repositório original no GitHub.

---

## 💻 2. Clone o seu fork

```bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO
````

---

## 🔗 3. Adicione o repositório original como `upstream`

```bash
git remote add upstream https://github.com/USUARIO_DO_PROJETO/REPOSITORIO_ORIGINAL.git
```

Verifique com:

```bash
git remote -v
```

---

## 🔄 4. Sincronize seu fork com o original

Antes de começar a trabalhar em algo novo:

```bash
git checkout main
git fetch upstream
git merge upstream/main
```

Depois, envie as mudanças para o seu fork:

```bash
git push origin main
```

---

## 🌱 5. Crie uma nova branch

Crie uma branch para sua funcionalidade ou correção:

```bash
git checkout -b nome-da-sua-branch
```

Exemplos:

* `ajuste-footer`
* `feature-login-google`
* `correcao-botao-cadastro`

---

## ✏️ 6. Faça suas alterações e commit

```bash
git add .
git commit -m "Descrição clara da mudança"
```

---

## 🚀 7. Envie sua branch para o seu fork

```bash
git push origin nome-da-sua-branch
```

---

## 📬 8. Crie um Pull Request

1. Vá até o repositório original no GitHub.
2. Clique em **"Compare & Pull Request"**.
3. Descreva o que você fez.
4. Envie para revisão.

---

## 🔁 9. Após o merge do seu PR

Atualize sua `main` local:

```bash
git checkout main
git fetch upstream
git merge upstream/main
git push origin main
```

---

## ✅ Boas práticas

* **Não trabalhe diretamente na `main`**
* **Use nomes descritivos para branches e commits**
* **Sempre sincronize com a `main` antes de criar uma nova branch**
* **Abra PRs claros e com descrição do que foi feito**

---

Obrigado por contribuir! 💙
