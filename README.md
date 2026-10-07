<div align="center">
  <img src="./banner.svg" alt="John Keyrrison — IA, PLN, LLMs e RAG" width="100%" />
</div>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=750&lines=Estudante+de+Inform%C3%A1tica+no+IFCE+%F0%9F%8E%93;Bolsista+PIBIC-AF+Jr.+2026+%F0%9F%94%AC;Construindo+um+chatbot+com+LLMs+%2B+RAG+%F0%9F%A4%96;IA+%7C+PLN+%7C+Java+%7C+Web+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=JKeyrrison&style=for-the-badge&color=2C5364&label=VISITAS" alt="Visitas" />
  <img src="https://img.shields.io/badge/IFCE-Maranguape-2C5364?style=for-the-badge" alt="IFCE" />
  <img src="https://img.shields.io/badge/PIBIC--AF%20Jr.-2026-36BCF7?style=for-the-badge" alt="PIBIC-AF Jr" />
  <img src="https://img.shields.io/badge/LEIAH-Laborat%C3%B3rio-203A43?style=for-the-badge" alt="LEIAH" />
</p>

---

## 👨‍💻 Sobre mim

Sou estudante do curso **Técnico Integrado em Informática** no **Instituto Federal do Ceará (IFCE) — Campus Maranguape**. Desenvolvo pesquisas aplicadas em **Inteligência Artificial, Processamento de Linguagem Natural (PLN)** e **Desenvolvimento de Software**.

Integro o **LEIAH (Laboratório de Eletrônica, Informática Aplicada e Humanidades)**, onde busco conectar tecnologia de ponta, acessibilidade e impacto social para a comunidade acadêmica.

```text
🎓 Formação    → Técnico Integrado em Informática | IFCE Maranguape
🔬 Pesquisa    → PIBIC-AF Jr. 2026 (Chatbot acadêmico com LLMs + RAG)
🧪 Laboratório → LEIAH – Eletrônica, Informática Aplicada e Humanidades
🌱 Aprendendo  → Python avançado, LangChain/LlamaIndex, ChromaDB/FAISS, APIs de LLM
```

---

## 🔬 Projeto em destaque — PIBIC-AF Jr. 2026

<table>
  <tr>
    <td>
      <h3>🤖 Assistente Inteligente do IFCE Campus Maranguape</h3>
      <p>Chatbot acadêmico que responde dúvidas da comunidade (estudantes, servidores, familiares e visitantes) sobre <b>calendário, regimento, ementas, editais e procedimentos administrativos</b>. Usa <b>LLMs gratuitos</b> e a técnica <b>RAG (Geração Aumentada por Recuperação)</b>, sempre indicando <b>as fontes</b> de cada resposta.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
        <img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
        <img src="https://img.shields.io/badge/Llama%203%20(Groq)-0467DF?style=flat-square&logo=meta&logoColor=white" />
        <img src="https://img.shields.io/badge/FAISS%20%7C%20ChromaDB-FF6F00?style=flat-square" />
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

**Como o chatbot funciona:**

```mermaid
flowchart LR
    subgraph PREP["Preparação (feita uma vez)"]
        A["Documentos do campus<br/>PDF, DOCX, HTML"] --> B["Divisão em chunks"]
        B --> C["Embeddings<br/>Sentence-Transformers"]
        C --> D[("Base vetorial<br/>FAISS / ChromaDB")]
    end
    subgraph USO["Uso (a cada pergunta)"]
        E["Pergunta do usuário"] --> F["Busca semântica"]
        F --> G["LLM gratuito<br/>Gemini / Llama 3"]
        G --> H["Resposta + fontes"]
    end
    D -.-> F
    classDef azul fill:#203a43,stroke:#36BCF7,stroke-width:2px,color:#ffffff
    class A,B,C,D,E,F,G,H azul
```

**Etapas do projeto (set/2026 → ago/2027):**

| Fase | Período | Entrega |
|------|---------|---------|
| 📚 **Base de conhecimento** | Set → Nov/2026 | Documentos do campus coletados, segmentados e indexados em base vetorial |
| ⚙️ **Pipeline RAG** | Dez/2026 → Mar/2027 | Chatbot em Python comparando pelo menos 3 LLMs gratuitos |
| 🌐 **Interface e avaliação** | Abr → Ago/2027 | App web acessível (WCAG 2.1), teste com 100+ perguntas reais e apresentação no Encontro de Iniciação Científica do IFCE |

> 👩‍🏫 Orientação: Profa. Dra. Jessyca Almeida Bessa

---

## 🔐 Projeto em equipe — PassGuardian

<table>
  <tr>
    <td>
      <h3>🔑 PassGuardian — gerenciador de senhas em Java + JavaFX</h3>
      <p>Aplicativo em desenvolvimento <b>em equipe</b> na organização <a href="https://github.com/PassWarriors"><b>PassWarriors</b></a> para a disciplina de <b>Programação Orientada a Objetos (POO)</b>. A proposta é ser <i>"a chave para a sua segurança digital"</i>, aplicando na prática classes, encapsulamento, herança e polimorfismo em uma interface gráfica com JavaFX.</p>
      <p><b>Algumas Funcionalidades:</b></p>
      <ul>
        <li>Salvar</li>
        <li>Criptografar</li>
        <li>Checkar</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
        <img src="https://img.shields.io/badge/JavaFX-4285F4?style=flat-square" />
        <img src="https://img.shields.io/badge/POO-203A43?style=flat-square" />
        <img src="https://img.shields.io/badge/Status-em%20desenvolvimento-yellow?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

## 🔭 Áreas de interesse

| | |
|---|---|
| 🧠 **Inteligência Artificial** | 💬 **Engenharia de Prompt** |
| 🗄️ **Bancos de Dados Vetoriais** | 🔌 **Eletrônica Básica** |
| 🌐 **Programação Web** | 📡 **Redes** |

---

## 🛠️ Tecnologias

<div align="center">

<img src="https://skillicons.dev/icons?i=python,java,flask,html,css,js,git,github&theme=dark" alt="Tecnologias" />

<br><br>

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/LlamaIndex-8E75B2?style=for-the-badge" />
<img src="https://img.shields.io/badge/ChromaDB-FF6F00?style=for-the-badge" />
<img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini%20API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge" />
<img src="https://img.shields.io/badge/JavaFX-4285F4?style=for-the-badge" />

</div>

---

## 📊 Estatísticas do GitHub

<div align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=JKeyrrison&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="Stats" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JKeyrrison&layout=compact&theme=tokyonight&hide_border=true" alt="Top Langs" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=JKeyrrison&theme=tokyonight&hide_border=true" alt="Streak" />
</div>

---

## 🐍 Contribuições

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JKeyrrison/JKeyrrison/output/github-contribution-grid-snake-dark.svg" />
    <img alt="Cobrinha comendo as contribuições" src="https://raw.githubusercontent.com/JKeyrrison/JKeyrrison/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

---

## 📫 Vamos conversar?

<div align="center">
  <a href="mailto:keyrrisonjohn186@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="http://lattes.cnpq.br/0291449767609376">
    <img src="https://img.shields.io/badge/Curr%C3%ADculo_Lattes-104E8B?style=for-the-badge&logo=book&logoColor=white" alt="Lattes" />
  </a>
</div>

<br>

<div align="center">
  <i>"Aprender, construir, errar, corrigir e repetir."</i>
</div>

<br>

<img src="./footer.svg" alt="Rodapé" width="100%" />
