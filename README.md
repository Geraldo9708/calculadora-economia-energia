# ⚡ Calculadora de Economia de Energia

Projeto **calculadora-economia-energia** criado para uma apresentação acadêmica na pós-graduação em **Data Science & IA**, com foco em unir aprendizado prático e comunicação clara. A aplicação permite estimar a **economia na conta de luz** com base em parâmetros como consumo (kWh), tarifa (R$/kWh) e cenários simulados (ex.: troca de equipamentos, ajuste de hábitos, etc.).

> Este README foi estruturado para uso profissional no GitHub, com seções objetivas e instruções de execução.

---

## 📑 Sumário
- [Visão Geral](#-visão-geral)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias](#-tecnologias)
- [Estrutura do Projeto (sugerida)](#-estrutura-do-projeto-sugerida)
- [Como Executar](#-como-executar)
- [Configuração para Produção](#-configuração-para-produção)
- [Qualidade & Padrões](#-qualidade--padrões)
- [Roadmap (sugestão)](#-roadmap-sugestão)
- [Contribuição](#-contribuição)
- [Licença](#-licença)

---

## 🔎 Visão Geral
Ferramenta simples e didática para apoiar **apresentações de estatística e eficiência energética**, permitindo simular cenários e visualizar rapidamente o impacto na fatura de energia elétrica.

**Exemplos de uso**: 
- Aula/apresentação de estatística (médias, percentuais e comparação de cenários)
- Demonstração de economia ao substituir lâmpadas, eletrodomésticos ou ajustar horários de uso
- Introdução a interfaces web com HTML/CSS/JavaScript

---

## ✅ Funcionalidades
- Entrada de **consumo (kWh)** e **tarifa (R$/kWh)**
- Cálculo de **custo atual** e **economia estimada**
- **Cenários simulados** (ex.: redução de consumo em N%)
- Feedback rápido e interface simples para apresentação

> Observação: ajuste esta lista conforme as funcionalidades reais do seu projeto.

---

## 🧰 Tecnologias
- **HTML5 / CSS3**
- **JavaScript (ES6+)**
- *(Opcional)* **Angular**: se o projeto for em Angular, as instruções abaixo contemplam ambos os casos (estático vs. Angular).*

---

## 🗂️ Estrutura do Projeto (sugerida)
```
calculadora-economia-energia/
├─ index.html            # Entrada principal (projeto estático)
├─ style.css             # Estilos
├─ script.js             # Lógica da calculadora
├─ assets/               # Imagens/ícones
├─ README.md
├─ LICENSE
└─ .github/workflows/    # CI opcional (build/test)
```
> Caso seja **Angular**, a estrutura típica inclui `angular.json`, `src/`, `package.json`, etc.

---

## ▶️ Como Executar

### Opção A) Projeto Estático (HTML/CSS/JS puros)
1. Baixe/clonе o repositório:  
   ```bash
   git clone https://github.com/SEU_USUARIO/calculadora-economia-energia.git
   cd calculadora-economia-energia
   ```
2. Abra o `index.html` diretamente no navegador **ou** sirva com um servidor local (recomendado para evitar bloqueios do navegador):  
   ```bash
   # Python 3
   python -m http.server 5500
   # Depois acesse http://localhost:5500
   ```

### Opção B) Projeto em Angular (se houver `angular.json`/`package.json`)
1. Instale as dependências:
   ```bash
   npm ci   # ou npm install
   ```
2. Rode em desenvolvimento:
   ```bash
   npm start    # ou ng serve
   # Acesse http://localhost:4200
   ```
3. Build de produção:
   ```bash
   npm run build    # ou ng build --configuration production
   ```

---

## 🚀 Configuração para Produção
- **Estático**: gere os arquivos finais (HTML/CSS/JS) e publique com GitHub Pages, Netlify ou Vercel.
- **Angular**: após `ng build --configuration production`, publique a pasta `dist/` em seu provedor (GitHub Pages via `gh-pages`, Netlify, Vercel, etc.).

---

## 🧭 Qualidade & Padrões
- `.editorconfig` para padronizar indentação e charset
- `.gitattributes` para normalização de finais de linha (evita *diffs* falsos)
- `.gitignore` para Node/Angular/IDE
- **Commits semânticos** (ex.: `feat:`, `fix:`, `docs:`)
- `CHANGELOG.md` (mantido por versão)
- **CI** (workflow opcional incluso) com build automático quando houver `package.json`

---

## 🗺️ Roadmap (sugestão)
- [ ] Adicionar exportação de relatório (PDF/CSV)
- [ ] Permitir simulações múltiplas lado a lado
- [ ] Salvar cenários no `localStorage`
- [ ] Testes automatizados (ex.: Jest)
- [ ] Dark mode

---

## 🤝 Contribuição
1. Faça um *fork*
2. Crie uma *branch*: `git checkout -b feat/nome-da-feature`
3. *Commit*: `git commit -m "feat: descrição curta"`
4. *Push*: `git push origin feat/nome-da-feature`
5. Abra um *Pull Request*

---

## 📜 Licença
Este projeto é distribuído sob a licença **MIT**. Veja o arquivo `LICENSE` para mais detalhes.
