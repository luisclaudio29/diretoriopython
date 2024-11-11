Listar Arquivos em um Diretorio
Este projeto em Python é um script simples para listar todos os arquivos e diretórios em um diretório especificado. Ele pode ser útil para navegação rápida e visualização dos arquivos em um diretório diretamente pelo terminal.

Funcionalidades
Listagem de todos os arquivos e subdiretórios em um diretório especificado
Exibição dos nomes dos arquivos diretamente no terminal
Pré-requisitos
Python 3: Certifique-se de que você tem o Python 3 instalado em sua máquina.
Instalação
Clone ou baixe o repositório para sua máquina.
No terminal, navegue até o diretório do projeto.

Para executar o script, siga os passos abaixo:

Abra o terminal e certifique-se de que está no diretório do projeto.
Execute o script usando o comando:
bash:
python listar_arquivos.py
O script irá listar todos os arquivos e diretórios no diretório atual. Caso queira listar arquivos de outro diretório, você pode modificar a linha diretorio_atual = os.getcwd() para o caminho desejado, por exemplo:

diretorio_atual = '/caminho/do/diretorio/desejado'


Estrutura do Código
ListarArquivos: Classe principal que representa o listador de arquivos em um diretório.
Método __init__: Inicializa a classe com o diretório especificado.
Método listar: Lista e imprime todos os arquivos no diretório fornecido.

Exemplo de Saída:

Ao executar o script, ele exibirá uma lista de arquivos no formato:

arquivo1.txt
arquivo2.png
pasta1
pasta2
...


Melhorias Futuras
Adicionar opções para listar apenas arquivos ou apenas diretórios.
Permitir a escolha do diretório via linha de comando.
Salvar a lista de arquivos em um arquivo de texto.
Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas e pull requests.

Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter mais informações.








