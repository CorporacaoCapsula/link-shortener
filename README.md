# Encurtador de URLs com GUI em JavaFX

Uma aplicação desktop elegante e intuitiva para transformar URLs longas em links curtos com apenas alguns cliques. Desenvolvida em Java 17 e JavaFX 20, esta ferramenta demonstra conceitos de geração de códigos aleatórios em Base62, manipulação de interface gráfica e armazenamento em memória, além de facilitar o compartilhamento imediato dos links encurtados direto para o clipboard.

---

## ✨ Principais Recursos

- **Interface Limpa e Responsiva**  
  Campo de texto claro para inserção da URL original, botão de ação destacado e área de histórico organizada.

- **Geração Automática de Slugs**  
  Códigos curtos de 6 caracteres em Base62, garantindo alta entropia e reduzindo colisões.

- **Histórico de Encurtamentos**  
  Exibição em tempo real de todos os pares `shortUrl → originalUrl` criados durante a sessão.

- **Cópia Instantânea**  
  Após cada encurtamento, o link é automaticamente copiado para o clipboard do sistema.

- **Pronto para Evoluir**  
  Arquitetura modular que permite adicionar facilmente persistência em arquivo/banco, servidor HTTP embutido, validação de URLs e temas personalizados.

---

## 📸 Pré-visualização

![Preview do Encurtador](docs/preview.png)

---

## 🚀 Como Executar

1. **Pré-requisitos**  
   - JDK 17 ou superior  
   - Maven  
   - Conexão com a internet (para baixar dependências JavaFX)

2. **Clone o repositório**  
   ```bash
   git clone https://github.com/seu-usuario/url-shortener-gui.git
   cd url-shortener-gui
