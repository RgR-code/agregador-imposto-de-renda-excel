# 📋 Agregador e Organizador de Imposto de Renda (IRPF) no Excel

Ferramenta prática e modular desenvolvida em Microsoft Excel para reunir, organizar e consolidar todas as informações essenciais necessárias para o preenchimento da Declaração de Ajuste Anual do Imposto de Renda de Pessoa Física (IRPF).

---

## 🎯 Objetivo do Projeto
Facilitar a organização financeira anual do contribuinte, reduzindo o risco de erros e esquecimentos no envio da declaração à Receita Federal através de um ambiente centralizado, intuitivo e com validações automáticas.

---

## 🛠️ Módulos e Estrutura da Planilha

### 1. 🗂️ Menu Principal (Painel Central)
* **Navegação Interativa:** Botões hiperlinkados para rápida alternância entre abas.
* **Links Oficiais da Receita Federal:** Atalhos diretos para o Portal *e-CAC*, programa oficial de transmissão, consulta de restituição e manual de dúvidas (*Perguntão IRPF*).

### 2. 💵 Módulo 1: Rendimentos
* Organização detalhada de salários, pro-labore, dividendos, rendimentos isentos e aluguéis.
* **Validação de Dados:** Seleção de categorias tributárias via menu suspenso.
* Consolidação automática de rendimento bruto, IRRF retido, INSS e 13º salário.

### 3. 🏠 Módulo 2: Bens e Direitos (Patrimônio)
* Registro de bens imóveis, veículos, aplicações financeiras e contas bancárias.
* **Cálculo de Variação Patrimonial:** Comparativo automático entre a situação em 31/12 do ano anterior e 31/12 do ano atual.

### 4. 🏥 Módulo 3: Despesas Dedutíveis
* Cadastro de pagamentos de saúde, instrução/educação, previdência privada (PGBL) e dependentes.
* **Estimativa de Dedução:** Lógica automatizada para teto dedutível e controle de entrega de comprovantes/recibos (`OK` / `PENDENTE`).

### 5. 📊 Módulo 4: Resumo Consolidado IRPF
* **Dashboard de KPIs:** Cards com os principais indicadores financeiros do ano.
* **Tabela de Transcrição:** Valores consolidados e prontos para inserção no programa oficial da Receita.
* **Checklist de Documentação:** Validação final de documentos e informes coletados.

---

## 📂 Arquivos no Repositório
* `Agregador_Imposto_de_Renda_IRPF.xlsx`: Planilha interativa pronta para uso no Excel.
* `README.md`: Documentação técnica detalhada do projeto.

---

## 💻 Tecnologias e Recursos Utilizados
* **Microsoft Excel** (Fórmulas de consolidação, `SUM`, `MIN`, `IF`, validação de dados, hyperlinks internos e externos)
* **Markdown** (Estruturação da documentação no GitHub)
