# 🌟 Contribuindo em um Projeto Open Source no GitHub

Repositório desenvolvido para fins didáticos, como fork do laboratório **Contribuindo em um Projeto Open Source no GitHub** da [Digital Innovation One (DIO)](https://www.dio.me/). O projeto foca em introduzir o básico sobre contribuição em repositórios e projetos Open Source no GitHub.

---

## 🎯 Objetivo
Aprender na prática como realizar contribuições no GitHub, passando por todo o fluxo de Fork, Clone, Commit, Push e criação de Pull Requests.

## 🛠️ Ferramentas Utilizadas
- **Git** - Sistema de Controle de Versão
- **GitHub** - Plataforma de hospedagem de código fonte

---

## 🚀 Como Contribuir (Desafio Profile README)

O desafio principal consiste em criar um *Profile README* na pasta `community` que contemple informações sobre você (badges, status do GitHub, projetos, etc).

### ⚙️ Passo a Passo

1. Faça o **Fork** do repositório original.
2. Clone localmente:
```bash
git clone https://github.com/SEU_USERNAME/dio-lab-open-source.git
```
3. Crie uma nova branch para a sua feature:
```bash
git checkout -b feat/community/SEU_USERNAME
```
4. Navegue até a pasta `community` e crie um arquivo Markdown (`.md`) com o nome do seu usuário do GitHub (ex: `elidianaandrade.md`).
5. Adicione suas informações e conteúdo utilizando os úlitilitários disponíveis na pasta `utils`.
6. Adicione no _staging area_ e faça o commit:
```bash
git add community/SEU_USERNAME.md
git commit -m "feat: add SEU_USERNAME profile"
```
7. Envie (Push) para a sua branch:
```bash
git push origin feat/community/SEU_USERNAME
```
8. Crie um **Pull Request**.

---

## 📁 Estrutura do Repositório
| Pasta | Descrição |
|---|---|
| `community/` | Local onde os *Profile READMEs* dos contribuidores são criados e armazenados |
| `docs/` | Documentação, arquivos estáticos da página web de membros da comunidade |
| `utils/` | Exemplos, links úteis e templates para Badges e GitHub Stats Cards |
| `scripts/` | Scripts auxiliares de automatização do repositório |

---

## 🤝 Comunidade
Este projeto é focado na comunidade e construído colaborativamente pelos alunos da plataforma DIO. Consulte as pastas e crie o seu próprio Perfil para demonstrar suas habilidades!

## 📜 Créditos e Licença
Projeto original feito com 💙 por [Eli (elidianaandrade)](https://github.com/elidianaandrade). Fork mantido para fins práticos e educacionais.
