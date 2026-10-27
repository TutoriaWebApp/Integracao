# Repositório de Integração: WebTutoria

Este repositório é dedicado à documentação e execução de testes de integração do sistema WebTutoria.

## 📂 Estrutura do Projeto

- **`WebTutoria - Completo.postman_collection.json`**: Coleção completa de requisições para testes.
- **`newman/`**: Diretório contendo os relatórios de execução gerados pelo Newman.

## 🚀 Como Executar os Testes

Para executar os testes automaticamente, utilizamos o **Newman**, a ferramenta de linha de comando do Postman.

### Pré-requisitos

Certifique-se de ter o Node.js instalado e, em seguida, instale o Newman globalmente:

```bash
npm install -g newman
```

### Execução

Navegue até a pasta `Integracao` e rode o script de execução:

```bash
cd Integracao
newman run "WebTutoria - Completo.postman_collection.json"
```

---

*Desenvolvido para o projeto WebTutoria.*
