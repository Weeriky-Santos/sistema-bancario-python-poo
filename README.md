# Sistema Bancário Digital em Python (POO)

Este é um sistema bancário digital completo desenvolvido em Python, aplicando conceitos de **Programação Orientada a Objetos (POO)** e modularização estruturada de pacotes. O projeto foi desenvolvido como parte do Mini-Projeto 2 da formação em Python da Data Science Academy (DSA).

---

## 🛠️ Arquitetura do Projeto

O código foi dividido estrategicamente em pacotes para garantir a manutenibilidade, seguindo as melhores práticas de engenharia de software:

* **`dsaentidades`**: Módulos responsáveis por gerenciar as entidades de negócio (ex: `Cliente` e `Conta`).
* **`dsaoperacoes`**: Módulo central que gerencia as operações e regras de negócio do banco (`Banco`).
* **`dsautilitarios`**: Contém as exceções customizadas para tratamento de erros específicos do sistema.
* **`main.py`**: O script principal que inicia a aplicação e serve de ponto de entrada.

---

## 🧠 Conceitos de POO Aplicados

* **Encapsulamento Rígido:** Uso de propriedades (`@property`) para proteger atributos sensíveis, como o saldo e dados das contas.
* **Herança e Classes Abstratas:** Implementação de uma classe base abstrata para servir de modelo arquitetural para diferentes tipos de contas bancárias.
* **Polimorfismo:** Sobrescrita de métodos para comportamentos dinâmicos de saques e taxas de acordo com o tipo de conta (Corrente ou Poupança).
* **Composição:** Gerenciamento centralizado de listas de clientes e contas de forma relacional dentro da classe do Banco.
* **Tratamento de Erros:** Criação de exceções personalizadas para regras de negócio (como saldo insuficiente ou conta não encontrada), garantindo a robustez do sistema.

---

## 🚀 Como Executar o Projeto

1. Certifique-se de ter o Python instalado no seu computador.
2. Baixe ou clone este repositório.
3. No terminal, navegue até a pasta raiz do projeto.
4. Execute o comando:
```bash
   python main.py
