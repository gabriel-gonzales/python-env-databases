# Criar um Novo Ambiente Virtual para Desenvolvimento

## Por que é importante?

- **Isolamento de Dependências**: Evita conflitos entre pacotes e versões de bibliotecas utilizadas em diferentes projetos.
- **Reprodutibilidade**: Facilita a reprodução do ambiente de desenvolvimento, garantindo que outros desenvolvedores possam trabalhar no projeto com as mesmas dependências.
- **Segurança**: Reduz o risco de que mudanças em pacotes globais afetem o funcionamento do projeto.

## Como fazer?

1. **Instalar o Virtualenv** (se ainda não estiver instalado):

	pip install virtualenv


2. **Criar um novo ambiente virtual:**


	python -m venv nome_do_ambiente

Isso criará um diretório nome_do_ambiente no diretório atual, contendo uma instalação isolada do Python e do pip para gerenciar pacotes.

Ativar o ambiente virtual:

No Windows(GitBash):

	source nome_do_ambiente/Scripts/activate

No Windows (usando cmd):



	nome_do_ambiente\Scripts\activate.bat



3. **Instalar bibliotecas no ambiente virtual**:

Após ativar o ambiente virtual, você pode instalar as bibliotecas necessárias utilizando o pip. Por exemplo:


	pip install <nome-da-biblioteca>


Todas as bibliotecas serão instaladas localmente no ambiente virtual, sem afetar o ambiente global do sistema.
