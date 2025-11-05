# Programação Orientada a Objetos (POO)

Repositório contendo materiais e exercícios práticos da disciplina de Programação Orientada a Objetos do curso de Ciência da Computação. Este repositório documenta o aprendizado e implementação dos principais conceitos de POO utilizando a linguagem Java.

## Conteúdo

### 01 - Classes e Objetos
Fundamentos da programação orientada a objetos, incluindo:
- Criação de classes e instanciação de objetos
- Atributos e métodos
- Encapsulamento (getters e setters)
- Construtores

**Projetos:**
- **ContaCorrente**: Sistema bancário básico com operações de depósito e saque
- **Employee**: Gerenciamento de funcionários com cálculo de salário anual
- **Invoice**: Sistema de faturamento de produtos
- **FormatarData**: Validação e formatação de datas

### 02 - Herança
Implementação de hierarquia de classes e reutilização de código:
- Herança simples
- Palavra-chave `extends`
- Sobrescrita de métodos (`@Override`)
- Classes base e derivadas

**Projetos:**
- **Banco**: Sistema bancário com diferentes tipos de contas (Corrente, Corrente Especial, Poupança)
- **Escola**: Cadastro de pessoas (Alunos, Professores, Técnicos Administrativos)
- **FormasBidimensionais**: Hierarquia de formas geométricas

### 03 - Sobrecarga
Polimorfismo de sobrecarga de métodos:
- Múltiplas assinaturas de métodos
- Diferenciação por número e tipo de parâmetros

**Projetos:**
- **Quadrado**: Cálculo de quadrado com diferentes tipos de entrada (int e double)

### 05 - Polimorfismo
Conceitos avançados de polimorfismo:
- Classes abstratas
- Métodos abstratos
- Variáveis polimórficas
- Instanceof e casting

**Projetos:**
- **ImpostoDeRenda**: Cálculo de impostos para Pessoa Física e Jurídica
- **AlunoCurso**: Exemplo de variáveis de classe

### 06 - Interfaces
Implementação de contratos e múltipla herança:
- Definição de interfaces
- Implementação múltipla
- Métodos abstratos em interfaces
- Variáveis estáticas (static)

**Projetos:**
- **Animal**: Hierarquia de animais com interfaces de domesticação e estimação
- **vendaDespesaSalario**: Sistema de movimentação financeira
- **Pessoa**: Demonstração de variáveis de classe e incremento automático

### 07 - Exceções (Exception)
Tratamento de erros e exceções:
- Try-catch-finally
- Exceções personalizadas
- Throws e throw
- Hierarquia de exceções

**Projetos:**
- **Calculadora**: Tratamento de divisão por zero com exceção customizada

### 08 - Collections
Estruturas de dados da API Java:
- ArrayList e List
- Iteração de coleções
- Collections.sort()
- Interface Comparable e Comparator

**Projetos:**
- **Ferramentas**: Sistema completo de locação e venda de ferramentas
- **Associacao**: Relacionamentos entre classes (Cliente, Venda, Produto, Compra)
- **Locacao**: Sistema de locação de veículos
- **ListaAlunosExemplos**: Ordenação e manipulação de listas

## Tecnologias

- **Linguagem**: Java
- **IDE**: NetBeans
- **Paradigma**: Orientação a Objetos

## Estrutura dos Projetos

A maioria dos projetos segue a arquitetura MVC (Model-View-Controller):

```
projeto/
├── src/
│   ├── br/edu/ifsp/pep/
│   │   ├── modelo/        # Classes de domínio
│   │   ├── controller/    # Lógica de negócio
│   │   ├── exception/     # Exceções customizadas
│   │   └── Principal.java # Classe principal
```

## Conceitos Aplicados

- **Encapsulamento**: Proteção de dados através de modificadores de acesso
- **Herança**: Reutilização de código e hierarquia de classes
- **Polimorfismo**: Flexibilidade através de classes abstratas e interfaces
- **Abstração**: Modelagem de entidades do mundo real
- **Composição**: Relacionamentos entre objetos
- **Tratamento de Exceções**: Robustez e confiabilidade do código
- **Collections**: Gerenciamento eficiente de conjuntos de dados

---

Este repositório foi desenvolvido exclusivamente para fins acadêmicos, documentando o progresso e aprendizado ao longo da disciplina de Programação Orientada a Objetos. Os projetos apresentam complexidade crescente, acompanhando a evolução dos conceitos estudados.
