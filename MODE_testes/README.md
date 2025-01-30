Conteúdo do Diretório
Este diretório contém os seguintes arquivos e recursos:

2 arquivos com elipses: Representam a Previsão e a Observação para comparação.
2 arquivos com círculos: Representam a Previsão e a Observação para comparação.
1 notebook: Contém o código necessário para a criação do arquivo de configuração e visualização das saídas do MODE.
Instruções para Utilização
Para utilizar os dados de teste e o notebook, siga os passos abaixo:

Passo 1: Acesse o diretório de dados do MET
Execute o comando abaixo para navegar até o diretório onde os dados estão localizados:
```
cd ~/DTC/MET-11.1.1/MET-11.1.1/data
```
Passo 2: Clone o repositório
Clone o repositório com o código e os recursos necessários utilizando o Git:

```
git clone https://github.com/Victorrani/MODE_MET_br.git
```
Passo 3: Crie o ambiente Conda
Crie o ambiente Conda com todas as dependências necessárias utilizando o arquivo environment.yml:

```
conda create --name MODE-MET --file environment.yml
```
Passo 4: Ative o ambiente Conda
Ative o ambiente Conda recém-criado:
```
conda activate MODE-MET
```

Passo 5: Entre no jupyter notebook

```
jupyter notebook
```
Após seguir esses passos, você estará pronto para utilizar os dados de teste e o notebook com o MODE do MET.



