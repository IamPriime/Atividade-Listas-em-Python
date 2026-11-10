```markdown
# 📦 Sistema de Cadastro e Controle de Estoque de Produtos

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)

Um script simples e interativo em Python para gerenciamento de estoque, permitindo a listagem, cadastro e remoção de produtos e seus respectivos preços de forma dinâmica.

## 🚀 Funcionalidades

- **Parte 1 (Listagem de Produtos):** Inicializa o sistema com um estoque padrão e exibe os produtos cadastrados formatados em Real (R$).
- **Parte 2 (Cadastro Interativo):** Permite ao usuário cadastrar novos produtos informando o nome e o preço através de entradas do console.
- **Parte 3 (Controle de Saída):** Remove o último produto inserido no estoque (estrutura LIFO/Pilha) e exibe as informações do item removido.

## 🛠️ Tecnologias Utilizadas

- **Python 3**: Linguagem de programação principal.
- **Estruturas de Dados**: Listas dinâmicas (`append()`, `pop()`) e iteração com `zip()` para manipulação conjunta de chaves e valores.

## 📂 Estrutura do Código

O projeto está estruturado em três etapas lógicas:

1. **Inicialização do Estoque:**
   ```python
   produtos = ["Camiseta Básica", "Calça Jeans", "Jaqueta Corta-Vento"]
   precos = [49.90, 129.90, 219.90]
   ```
2. **Inclusão de Novos Itens:**
   ```python
   novo_produto = input("Digite o nome do novo produto")
   novo_preco = float(input("Digite o novo valor do produto"))
   ```
3. **Remoção de Itens (Descarte de Estoque):**
   ```python
   if len(produtos) > 0:
       removido = produtos.pop()
       preco_removido = precos.pop()
   ```

## 💻 Como Rodar o Projeto

### Pré-requisitos
Você precisará ter o Python instalado em sua máquina ou utilizar um ambiente online como o **Google Colab**.

### Passo a Passo
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Acesse a pasta do projeto e execute o script:
   ```bash
   python seu_script.py
   ```
3. Siga as instruções no terminal para interagir com o cadastro e visualização do estoque.

---
Desenvolvido como parte do aprendizado prático de estruturas de dados básicas em Python! ⭐
```
