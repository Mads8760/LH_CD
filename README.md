# Projeto modelo de Regressão linear
Esse projeto tem como objetivo implementar um modelo de regressão linear para prever preços de imóveis de alugueis por temporada na cidade de Nova York. A análise exploratoria dos dados e o modelo foram desenvolvidos em um jupyter notebook e salvo em um arquivo pkl. para utilização futura.


# Pré-requisitos 
É importante que, antes de executar o projeto, observe se possui as seguintes ferramentas de instalção:
1. Python 3x.
2. Jupyter notebook: Para executar o Notebook
3. Gerenciador de pacotes pip: Normalmente ja vem instaldo com o python

# Instalação
Para instalação e configuração do ambiente de execução, siga os passos a seguir:
1. Clonando o git utilizando o sistema operacional Windows:
   * Abra o Prompt de comando ou powershell. Pressione `Win` + `R`, digite cmd ou PoweShell e pressione enter.
   * Navegue ate a pasta onde você quer clonar o repositorio usando o comando cd. Exemplo:
     - cd C: \caminho\para\pasta\de\destino
     -  Em seguida execute o codigo: git clone https://github.com/sue-usuario/u-respositorio.git
     -  Apos isso execute os comanado de instalação: pip install -r requirements.txt
2. Clonando utilizando o Linux/Mac:
   * Abra o terminal com os comandos `Ctrl` + `Alt` + `T`:
   * Navegue ate a pasta onde você quer clonar o repositorio usando o comando cd. Exemplo:
     - cd C: \caminho\para\pasta\de\destino
     -  Em seguida execute o codigo: git clone https://github.com/sue-usuario/u-respositorio.git
     -  Apos isso execute os comanado de instalação: pip install -r requirements.txt
3. InstalandoJupyter Notebook:
   * No prompt de comando digite jupyter notebook e espere instalar. Apos isso escolha qual browser você quer abri-lo.
   * Apos isso, na pagina inicial do jupyter notebook ( onde e possivel ver os arquivos e pastas), clique em New localizado na canto superior direito e selecione Terminal
   * Navegue ate a pasta do projeto utilizando o comando cd e execute os comandos de instalação:
     - cd C: \caminho\para\pasta\de\destino
     - pip install -r requirements.txt
4. No terminal integrado com o Vs Code:
   * Abra a pasta do projeto no VS Code
   * Acesse o terminal integrado: Terminal > Nem terminal ou acesse elo atalho `Ctrl + `
   * O diretorio será aberto na pasta do projeto
   * Navegue ate a pasta do projeto utilizando o comando cd e execute os comandos de instalação:
     - cd C: \caminho\para\pasta\de\destino
     - pip install -r requirements.txt
5. No Anaconda prompt:
   * Abra o Anaconda Prompt
   * Navegue ate a pasta do projeto utilizando o comando cd e execute os comandos de instalação:
     - cd C: \caminho\para\pasta\de\destino
     - pip install -r requirements.txt
6. No googgle colab:
   * O google colab não possui um terminal tradicional, mas é possivel instalar dependencias diretamente em uma célular usando:
     - !pip install -r requirements.txt
  * Lembre-se que o google colab é uma ferramenta baseada em nuvem, o que não o torna uma boa escolha para projetos locais.


# Executando o Jupyter Notebook
   * No prompt de comando digite jupyter notebook e espere instalar. Apos isso escolha qual browser você quer abri-lo.
   * No navegador, abra o arquivo Teste_Indicium_Analise_e_Modelo.ipynb
   * Apos isso, a analise e o modelo pode ser visto e testado.


# Modelo salvo em pkl
 * Para esecutar o modelo salvo em pkl , execute o seguinte comando no seu jupyter notebook:
 
 - importar bibliotecas
 

      `import pickle`
  
      `import pandas as pd`

- Carregar o modelo salvo

 
  `with open('Teste_Indicium_Analise_e_Modelo.pkl', 'rb') as file:`
   
    `model = pickle.load(file)`


# Estrutura do Projeto
A estrutura do projeto esta organizada da seguinte forma:
-  LH_CD/ - Repositório
1. README.md - O presente arquivo
2. requirements.txt - Lista de dependências      
3. Teste_Indicium_Analise_e_Modelo.ipynb -Jupyter Notebook com o código do modelo                     
4. Teste_Indicium_Analise_e_Modelo.pkl - Modelo treinado salvo em formato .pkl                            


# Dependências
As bibliotecas utilizadas no projeto são:
1. Jupyter: Para executar o notebook
2. Pandas: Para manipulação do dados
3. Numpy: Para calculos numericos
4. matplotlib/ Seaborn: Para visuualização do dados
5. Scikit-learn: Para implementar o modelo de regressão linear
6. Voce pode instalar todas as dependencias usando o arquvio requirements.txt: pip install -r requirements.txt
