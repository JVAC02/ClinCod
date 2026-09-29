# 🩺 ClinCod

> **Sistema Inteligente de Emissão de Laudos de AIH e APAC do SUS com Consulta Integrada à Tabela SIGTAP.**

ClinCod é uma aplicação médica moderna, desenvolvida para agilizar a emissão de **Autorização de Internação Hospitalar (AIH)** e **Autorização de Procedimentos Ambulatoriais de Alta Complexidade / Alto Custo (APAC)** no âmbito do Sistema Único de Saúde (SUS), garantindo precisão documental e prevenindo glosas regulatórias.

🌐 **Acesso Online:** [https://jvac02.github.io/ClinCod/](https://jvac02.github.io/ClinCod/)

---

## 🚀 Principais Funcionalidades

- **🏥 Emissor Oficial de Laudo de AIH:**
  - Carimbo automatizado sobre o formulário oficial do Ministério da Saúde.
  - Busca inteligente por patologia, sinônimos clínicos ou código CID-10.
  - Associação instantânea com procedimentos autorizados (Grupos 03 Clínico e 04 Cirúrgico da Tabela SIGTAP).

- **🔬 Emissor Oficial de Laudo de APAC (Exames & Terapias de Alto Custo):**
  - Catálogo completo com 4.984 procedimentos de alta complexidade e exames de imagem/diagnóstico (Grupo 02: Tomografias, Ressonâncias, Cintilografias, Cateterismos, Biópsias; e Grupos 03/06: Hemodiálise, Quimioterapia, Medicamentos Especializados).
  - Atalhos rápidos com 1 clique para exames diagnósticos frequentes.
  - Gerenciamento de exames secundários dinâmicos (até 5 procedimentos complementares).
  - Acesso direto via `index.html#apac` ou `apac.html`.

- **🛡️ Auditor Preventivo Anti-Glosa em Tempo Real:**
  - Validação cruzada automática de Sexo x Procedimento (evita procedimentos ginecológicos para homens ou procedimentos urológicos/próstata para mulheres).
  - Alerta de inconsistência de Faixa Etária (procedimentos pediátricos/neonatais em adultos ou obstétricos fora da faixa etária).

- **🏢 Perfil Multi-Hospital do Médico:**
  - Gerenciador rápido para alternar entre diferentes hospitais, UPAs ou unidades de saúde onde o profissional atua com apenas 1 clique, preenchendo automaticamente Nome do Estabelecimento e CNES.

- **🖨️ Duplo Modo de Emissão:**
  - **Baixar Laudo (PDF):** Download direto do documento oficial preenchido.
  - **Gerar e Imprimir Direto:** Abertura imediata do laudo no visualizador do navegador com a impressora engatilhada.

- **🕒 Histórico Local de Laudos Recentes:**
  - Armazenamento privado e seguro na memória local do navegador dos últimos laudos gerados.
  - Restauração de todos os dados do paciente com 1 clique para reimpressão imediata.

- **🔒 100% Offline & Privacidade Total:**
  - Não utiliza servidor externo nem banco de dados em nuvem.
  - Nenhum dado de paciente ou profissional sai do dispositivo do usuário.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3 Moderno** (com variáveis CSS e suporte completo a Modo Escuro/Claro).
- **Vanilla JavaScript (ES6+)** (execução rápida e sem dependência de frameworks pesados).
- **PDF-Lib** (manipulação vetorial e carimbo preciso nas coordenadas oficiais dos formulários do SUS).
- **GitHub Pages & GitHub Actions** (deploy e entrega contínua automatizada).

---

## 📄 Licença

Distribuído sob a licença MIT. Consulte `LICENSE` para obter mais informações.
