# 🧪 Projeto Acadêmico – Sistema de Agendamento (MediSync)

Este repositório contém toda a documentação, planejamento e execução de testes desenvolvidos durante o **4º período da graduação em Análise e Desenvolvimento de Sistemas**, no projeto interdisciplinar **MediSync**, voltado para **agendamento médico online**.

O objetivo principal foi simular um **ambiente corporativo real**, aplicando metodologias ágeis, engenharia de requisitos, testes manuais e automatizados, com **organização profissional** e foco em qualidade de software.



## 📂 Estrutura do Repositório


sistema-agendamento-medisync/
│
├── 01-planejamento-requisitos/
│   ├── Relatorio_Requisitos.docx
│   └── Sistema_Agendamento.pdf
│
├── 02-documentacao-testes/
│   ├── Relatorio_Qualidade.docx
│   ├── Evidencias_Testes.docx
│   └── Casos_Testes_BDD.docx
│
├── 03-automacao/
│   ├── scripts-robot/
│   │   ├── teste_pacientes.robot
│   │   ├── agendar_consulta.robot
│   │   └── executar_teste.bat
│   └── log_erro_robot.txt
│
├── 04-apresentacoes/
│   ├── video-apresentacao.mp4
│   └── slides-apresentacao.pdf
│
└── README.md


## 🎯 Objetivos do Projeto

- Desenvolver um **sistema web funcional** para agendamento médico.
- **Elaborar e documentar requisitos funcionais e não funcionais**.
- Criar **testes manuais e automatizados**, simulando um fluxo real de QA.
- Aplicar a **norma ISO/IEC 25010** como referência para qualidade.
- Produzir **evidências organizadas e relatórios claros** para apresentação.



## 🛠️ Tecnologias Utilizadas

- **Metodologia Ágil:** Scrum (Sprints semanais)
- **Gerenciamento:** Trello
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript
- **Banco de Dados:** SQLite
- **Automação de Testes:** Robot Framework + SeleniumLibrary
- **Navegador Automação:** Google Chrome


## 🗂️ Documentação Incluída

### **1. Planejamento e Requisitos**
Documentos que definem a base do projeto:
- Levantamento de requisitos funcionais e não funcionais.
- Histórias de usuário e casos de uso.
- Resumo de funcionalidades planejadas.

📄 **Principais arquivos:**
- `Relatorio_Requisitos.docx`
- `Sistema_Agendamento.pdf`


### **2. Testes Manuais (ISO/IEC 25010)**
Relatórios completos de testes manuais, com foco em:
- Cenários positivos e negativos.
- Critérios de aceite bem definidos.
- Estrutura em **BDD (Behavior Driven Development)** usando Gherkin.

📊 **Exemplo de caso de teste BDD:**

```gherkin
Funcionalidade: Cadastro de Paciente
Cenário: Cadastro de paciente com dados válidos
  Dado que o usuário acessa o formulário de cadastro
  E preenche os campos com informações válidas
  Quando clica em "Salvar"
  Então o sistema exibe a mensagem "Paciente cadastrado com sucesso"
  E salva o paciente no banco de dados
```

📄 **Principais arquivos:**
- `Casos_Testes_BDD.docx`
- `Evidencias_Testes.docx`



### **3. Automação de Testes**
Automação desenvolvida para validar os fluxos principais:
- Cadastro de pacientes.
- Agendamento de consultas.

📌 **Estrutura de scripts:**
- `teste_pacientes.robot` → Validações completas do formulário de pacientes.
- `agendar_consulta.robot` → Fluxo completo de agendamento.

📊 **Relatórios:**
- `log_erro_robot.txt` → Logs detalhados de execução.
- Prints automáticos salvos durante os testes.



### **4. Evidências e Prints**
Todas as evidências estão organizadas para facilitar a análise visual:
```
evidencias/
├── cadastro_paciente_sucesso.png
├── erro_cpf_invalido.png
└── agendamento_sucesso.png
```

---

## 📊 ISO/IEC 25010 Aplicada
O relatório de qualidade foi baseado na norma **ISO/IEC 25010**, abordando:

| **Atributo**         | **Detalhes Avaliados** |
|----------------------|------------------------|
| **Funcionalidade**   | Cadastro, login, agendamento. |
| **Confiabilidade**   | Estabilidade do sistema em entradas inválidas. |
| **Usabilidade**      | Clareza de mensagens e interface acessível. |
| **Eficiência**       | Tempo médio de resposta e performance. |
| **Compatibilidade**  | Testes cross-browser no Chrome. |
| **Segurança**        | Planejamento futuro para autenticação e criptografia. |

📄 **Arquivo:** `Relatorio_Qualidade.docx`

---

## 🚀 Estrutura de Testes Automatizados

| **Camada**            | **Objetivo** |
|-----------------------|--------------|
| **Smoke Tests**       | Garantir que funcionalidades principais estão ativas. |
| **E2E (End-to-End)**  | Validar fluxo completo de cadastro + agendamento. |
| **Negativos**         | Garantir tratamento correto de erros e mensagens. |

📄 **Arquivo:** `Relatorio_Testes_Automatizados.docx`

---

## 🖥️ Apresentações
Além da documentação técnica, o projeto conta com:
- **Slides de apresentação** (`slides-apresentacao.pdf`).
- **Vídeo explicativo** com a demonstração do sistema (`video-apresentacao.mp4`).

---

## 🔒 Confidencialidade
> **Nota Importante:**  
> Todos os dados presentes neste projeto são **fictícios e acadêmicos**.  
> Este repositório tem finalidade **exclusivamente educacional e de portfólio**, sem vínculo com empresas reais.

---

## 👨‍💻 Autor

**Jefferson Paulo**  
QA | Analista de Qualidade e Automação  
[LinkedIn] | [GitHub](https://github.com/seuusuario)

