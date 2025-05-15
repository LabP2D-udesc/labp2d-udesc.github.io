# LabP2D - UDESC

Este repositório contém o site estático do LabP2D - UDESC, desenvolvido com Jekyll e hospedado no GitHub Pages. A estrutura foi planejada para permitir a atualização de conteúdo em Markdown e integração futura com serviços externos, como o Google Calendar.

## 🛠️ Estrutura do Projeto

A estrutura do repositório está organizada da seguinte forma:

* `index.md` - Página inicial em inglês, desenvolvida em Markdown.
* `_config.yml` - Arquivo de configuração do Jekyll, incluindo informações gerais do site e plugins utilizados.
* `assets/` - Diretório destinado a arquivos estáticos (CSS, JS, imagens).
* `img/` - Pasta específica para armazenar imagens utilizadas no site.
* Arquivos Markdown adicionais - Páginas como `GraduatedStudents.md`, `Parceiros.md` e `Related Projects.md` estão organizadas de forma modular para facilitar a manutenção.

## 📦 Como Clonar o Repositório

1. Clone o repositório:

   ```bash
   git clone https://github.com/LabP2D-udesc/labp2d-udesc.github.io.git
   ```

2. Acesse o diretório do projeto:

   ```bash
   cd labp2d-udesc.github.io
   ```

## 🚀 Executando o Projeto Localmente

Para visualizar o site localmente:

1. Instale o Jekyll e as dependências:

   ```bash
   gem install bundler jekyll
   bundle install
   ```

2. Inicie o servidor local:

   ```bash
   bundle exec jekyll serve
   ```

3. Acesse o site no navegador: `http://localhost:4000`

## 📝 Atualizando o Conteúdo

* Edite os arquivos Markdown localizados na raiz do projeto ou na pasta `assets`.
* Após as edições, execute o commit:

  ```bash
  git add .
  git commit -m "Atualização do conteúdo"
  git push origin main
  ```

## 🌐 Integração com Google Calendar

A integração com o Google Calendar ainda não foi implementada. Para futuras atualizações, a estrutura será organizada de forma que a integração ocorra em uma página HTML separada, fora do escopo do Jekyll, evitando conflitos de build.

## 🛠️ Rebuild e Debug

* Em caso de falha no build ou ausência de atualização automática no GitHub Pages, execute um commit vazio:

  ```bash
  git commit --allow-empty -m "Forçando rebuild"
  git push origin main
  ```

* Verifique os logs e mensagens de erro nas configurações do GitHub Pages para identificar possíveis inconsistências.

## 📦 Backup e Recuperação

* Mantenha backups locais regulares.
* Utilize branches para novas funcionalidades e mescle com a branch principal somente após os testes.

---

© 2025 LabP2D - UDESC. Todos os direitos reservados.
