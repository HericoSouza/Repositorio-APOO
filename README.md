# 🐾 Sistema de Gestão de Hospitais Veterinários

Repositório destinado à documentação e ao desenvolvimento do projeto acadêmico **Sistema de Gestão de Hospitais Veterinários**, elaborado para a disciplina de **Análise e Projeto Orientado a Objetos (APOO)**.

O projeto tem como objetivo modelar um sistema de informação capaz de centralizar e organizar as atividades clínicas, administrativas e gerenciais de hospitais e clínicas veterinárias, facilitando o acompanhamento dos animais atendidos e o gerenciamento das informações da instituição.

---

## 📌 Sobre o Projeto

O Sistema de Gestão de Hospitais Veterinários foi idealizado para atender às necessidades de organização e gerenciamento de instituições voltadas à saúde animal.

A proposta consiste em reunir, em um único sistema, informações sobre animais, tutores, veterinários, atendimentos, prontuários, exames, procedimentos, prescrições de medicamentos e internações.

Além das funcionalidades clínicas, o sistema contempla recursos de acompanhamento gerencial, permitindo a consulta de informações consolidadas sobre atendimentos, internações e procedimentos realizados.

O projeto é desenvolvido no contexto acadêmico, com foco na aplicação dos conceitos de análise, modelagem e projeto de sistemas orientados a objetos.

## 🎯 Objetivos

- Centralizar as informações dos animais atendidos e de seus respectivos tutores.
- Organizar os registros de consultas e atendimentos veterinários.
- Manter o histórico clínico dos animais por meio de prontuários.
- Permitir o registro de diagnósticos, exames, procedimentos e prescrições.
- Gerenciar internações, leitos e acompanhamento clínico dos pacientes.
- Organizar as informações profissionais dos veterinários.
- Disponibilizar informações consolidadas para apoiar a gestão hospitalar.
- Aplicar conceitos de Engenharia de Software e modelagem orientada a objetos.

## 🧩 Principais Funcionalidades

| Módulo | Descrição |
|---|---|
| Cadastro de animais | Registro e consulta dos dados de identificação dos pacientes. |
| Gestão de tutores | Cadastro dos responsáveis e associação com seus animais. |
| Atendimento veterinário | Registro de consultas, diagnósticos e observações clínicas. |
| Prontuário animal | Consulta e manutenção do histórico clínico dos pacientes. |
| Exames e procedimentos | Registro de exames solicitados, resultados e procedimentos realizados. |
| Prescrição de medicamentos | Registro de medicamentos, dosagens, vias e frequências de administração. |
| Gestão de internações | Controle de entradas, saídas, leitos e motivos da internação. |
| Acompanhamento clínico | Registro da evolução dos animais internados e das ocorrências durante o tratamento. |
| Gestão de profissionais | Cadastro de veterinários e suas especialidades. |
| Painel gerencial | Consulta de indicadores e geração de relatórios para apoio à tomada de decisão. |

## 👥 Usuários do Sistema

O sistema prevê diferentes perfis de usuários, com responsabilidades específicas:

- **Veterinário:** realiza atendimentos clínicos, registra diagnósticos, solicita exames, prescreve medicamentos e gerencia prontuários.
- **Recepcionista:** realiza o acolhimento, cadastra tutores e animais e auxilia no gerenciamento dos atendimentos.
- **Responsável pela Internação:** acompanha os animais internados, controla os leitos, registra a evolução clínica e acompanha a administração de medicamentos.
- **Gestor:** consulta indicadores e relatórios consolidados para apoiar a tomada de decisões.

## 📚 Organização do Trabalho

O repositório reúne os materiais produzidos ao longo das etapas do projeto.

### M1 — Fase de Requisitos

Etapa dedicada à definição do problema, ao levantamento das necessidades do sistema e à identificação de suas funcionalidades.

Principais entregáveis:

- Descrição geral do projeto.
- Protótipos das interfaces de usuário.
- Lista de requisitos funcionais (RF01–RF30).
- Lista de requisitos não funcionais (RNF01–RNF10).

Os protótipos contemplam o painel de atendimento, o prontuário do animal, a gestão de internações, o cadastro e relacionamento entre animais e tutores e o painel gerencial.

### M1 — Fase de Requisitos/Análise

Etapa dedicada à documentação dos casos de uso e à representação das interações entre os usuários e o sistema.

Principais entregáveis:

- Documentação do Modelo de Casos de Uso (MCU).
- Glossário de atores.
- Regras de negócio.
- Diagrama de Casos de Uso (DCU).
- Descrições narrativas dos casos de uso.

Casos de uso documentados:

| Código | Caso de Uso |
|---|---|
| CSU01 | Realizar atendimento veterinário |
| CSU02 | Gerenciar prontuário do animal |
| CSU03 | Registrar internação do animal |
| CSU04 | Cadastrar animal |
| CSU05 | Registrar exames e procedimentos |
| CSU06 | Prescrever medicamento |
| CSU07 | Acompanhar animal internado |
| CSU08 | Gerar relatórios gerenciais |

### M1 — Fase de Análise

Etapa voltada à identificação das principais classes do domínio e de suas responsabilidades dentro do sistema.

Principais entregáveis:

- Documentação do modelo.
- Glossário do modelo.
- Identificação das classes, responsabilidades e atributos principais.
- Diagrama de classes de domínio.

Entre as classes identificadas estão `Tutor`, `Animal`, `Veterinário`, `Atendimento`, `Prontuário`, `ExameProcedimento`, `Prescrição`, `Internação`, `Leito` e `Gestor`.

## 📐 Regras de Negócio

O projeto estabelece regras para manter a consistência das informações e representar adequadamente o funcionamento de uma instituição veterinária.

- **RN01 — Associação Obrigatória:** todo animal cadastrado deve estar vinculado a pelo menos um tutor responsável.
- **RN02 — Unicidade do Prontuário:** cada animal possui um único prontuário histórico.
- **RN03 — Atendimento Vinculado:** todo atendimento clínico exige a identificação do animal e do veterinário responsável.
- **RN04 — Ocupação de Leito:** uma internação só pode ser efetivada quando houver um leito físico vago e compatível.
- **RN05 — Controle de Permissões:** o acesso às funcionalidades deve respeitar o perfil de cada usuário.

## 🛠️ Ferramentas Utilizadas

- **[Balsamiq Wireframes](https://balsamiq.com/):** elaboração dos protótipos de interfaces de usuário.
- **[Astah UML](https://astah.net/):** construção e documentação dos diagramas UML utilizados na modelagem do sistema.
- **[GitHub](https://github.com/):** armazenamento, organização e versionamento dos materiais do projeto.
- **Markdown:** elaboração da documentação do repositório.

## 🔒 Requisitos Não Funcionais

O sistema também considera características necessárias para sua qualidade e confiabilidade:

- Segurança e controle de acesso.
- Integridade e consistência dos dados.
- Usabilidade das interfaces.
- Desempenho adequado nas consultas.
- Privacidade das informações.
- Disponibilidade durante o funcionamento do hospital.
- Confiabilidade no armazenamento dos registros.
- Recuperação de dados por meio de cópias de segurança.
- Manutenibilidade da estrutura do sistema.
- Compatibilidade com os dispositivos utilizados pela instituição.

## 🌱 Motivação

A escolha do tema está relacionada à experiência dos integrantes
