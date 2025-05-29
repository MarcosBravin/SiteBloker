# 🚫 SiteBloker v2.1.8

**SiteBloker** é um sistema avançado de **controle e bloqueio de conteúdo online**, projetado especialmente para ambientes **educacionais** e **corporativos**.  
Na versão **2.1.8**, oferece bloqueio automatizado de páginas web, com base em palavras-chave, listas de exceção e desbloqueio temporário, garantindo **segurança**, **produtividade** e uma **experiência de uso moderna e intuitiva**.

---

## ✨ Principais Recursos

### ✅ Bloqueio inteligente por palavras-chave
- Análise em tempo real do **título da janela** e do **conteúdo da aba ativa**.
- Detecção eficiente para impedir acesso a conteúdos não permitidos.

### ✅ Exceções configuráveis (Whitelist)
- Criação de uma lista de **URLs e palavras permitidas**.
- Flexibilidade para liberar conteúdos específicos conforme necessidade.

### ✅ Monitoramento em tempo real no navegador Microsoft Edge
- Captura precisa da **URL real** da aba ativa.
- Redução significativa de **falsos positivos**.

### ✅ Desbloqueio temporário controlado
- Liberação de conteúdo mediante um **temporizador configurável**.
- Ideal para **atividades práticas** ou **exceções pontuais**.

### ✅ Registro de atividades (Logs)
- **Histórico detalhado** de tentativas de acesso e bloqueios.
- Transparência e possibilidade de auditoria.

### ✅ Interface moderna e responsiva
- Desenvolvida com **CustomTkinter**.
- **Modo escuro** para melhor conforto visual e usabilidade.

### ✅ Arquitetura modular e leve
- Compatível com **Windows**.
- **Baixo consumo de recursos**, ideal para ambientes com múltiplos dispositivos.

---

## ⚙️ Personalizações Disponíveis

- ✅ **Palavras bloqueadas e permitidas:**  
  Gerenciadas através de um arquivo **JSON externo** para fácil manutenção.

- ✅ **Lista de sites liberados:**  
  Configuração por **domínio completo** ou **parte de uma URL**.

- ✅ **Identidade visual:**  
  Personalização do **logotipo** e **nome da instituição** na interface.

---

## 🖥️ Tecnologias Utilizadas

- **Python** — linguagem principal.
- **CustomTkinter** — interface gráfica moderna.
- **PyWin32** — detecção de janelas e processos no Windows.
- **Selenium** — captação de URLs no Edge.
- **JSON** — armazenamento de configurações dinâmicas.

---

## 🚀 Instalação

### Pré-requisitos:
- Python 3.8 ou superior.
- Windows 10 ou superior.
- Microsoft Edge instalado.

### Passos:

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/sitebloker.git
cd sitebloker

# Instale as dependências
pip install -r requirements.txt

# Configure os arquivos de bloqueio e exceção
