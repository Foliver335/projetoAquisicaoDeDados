# Projeto aquisiçao de dados (Web Scrap)


Este repositório contém scripts em Python para aquisição de dados de uma fonte específica.
Esses Scripts utilizam tecnologias que auxiliarão na coleta dedados de maneira automatica de maneira elegante, eficaz e de facil utilização.

Esses scripts estão separados em pastas com os nome " Aquisicoes", juntamente com pastas para organizar o tipo de dado desejado.

Requisitos
Para rodar o script é necessário ter o Python instalado em sua máquina, além das seguintes bibliotecas:

* Beautiful Soup (Biblioteca de análise de HTML e XML para Python. Ela é usada para extrair dados de arquivos HTML e XML, tornando mais fácil a manipulação desses dados em um programa Python).
* LXML (Biblioteca de processamento de XML e HTML para Python. Ela é usada para analisar, validar e manipular documentos XML e HTML de forma eficiente).
PyQuery (biblioteca que fornece uma interface semelhante ao jQuery para Python. Ela permite que você faça seleções de elementos HTML usando a sintaxe do jQuery e manipule esses elementos facilmente em seus programas Python)
* Scrapy (Biblioteca de web scraping de alta performance para Python. Ela é usada para extrair dados de websites de forma automatizada e escalável, permitindo que você crie programas que coletam informações de várias páginas web em pouco tempo).
* Selenium (Biblioteca de automação de testes para web que permite a interação com páginas web em um navegador real ou emulado. Ela é usada principalmente para testes automatizados, mas também pode ser usada para web scraping em sites que requerem interações com o usuário
* Requests (Biblioteca de HTTP para Python. Ela é usada para enviar solicitações HTTP para servidores web e receber respostas. Ela fornece uma interface simples para lidar com solicitações e respostas HTTP, permitindo que você escreva programas que interagem com servidores web).

Caso ainda não possua o Python em sua máquina, siga os passos a seguir:

Windows: Para instalar o Python em uma máquina com Windows, siga os seguintes passos:
1. Acesse o site oficial de download do Python: https://www.python.org/downloads/.
2. Clique no botão "Download Python X.X.X" (onde X.X.X é a versão mais recente do Python disponível).
Selecione o instalador apropriado para o seu sistema operacional Windows (32 ou 64 bits) e faça o download. Certifique-se de escolher a versão correta para o seu sistema operacional.
3. Execute o arquivo de instalação que foi baixado e siga as instruções do instalador. Na janela de instalação, certifique-se de marcar a opção "Adicionar Python X.X ao PATH" para que o Python possa ser acessado de qualquer diretório em seu computador.
4. Clique em "Instalar agora" para iniciar a instalação.
5. Aguarde até que a instalação seja concluída. O instalador irá notificá-lo quando estiver concluído.
6. Para verificar se o Python foi instalado corretamente, abra uma janela de prompt de comando e digite "python --version". Isso deve mostrar a versão do Python instalada em seu computador.
7. Após a instalação do Python, você pode começar a escrever e executar programas em Python na linha de comando ou utilizando um ambiente de desenvolvimento integrado (IDE) como PyCharm, VS Code, entre outros.

Linux : Para instalar o Python em uma máquina com Linux, siga os seguintes passos:
1. Abra o terminal do Linux. Dependendo da distribuição Linux que você estiver usando, pode ser necessário executar o terminal como administrador.
2. Verifique se o Python já está instalado em sua máquina digitando o seguinte comando no terminal: python --version. Se o Python já estiver instalado, o terminal irá mostrar a versão do Python instalada. Caso contrário, siga para o próximo passo.
3. Digite o seguinte comando no terminal para atualizar a lista de pacotes disponíveis: sudo apt-get update
4. Em seguida, digite o seguinte comando para instalar o Python: sudo apt-get install python3. Este comando irá instalar a versão mais recente do Python 3 disponível em seu repositório de pacotes.
5. Verifique se o Python foi instalado corretamente digitando o seguinte comando no terminal: python3 --version. Isso deve mostrar a versão do Python 3 instalada em sua máquina.
6. Você também pode instalar o pip, o gerenciador de pacotes do Python, digitando o seguinte comando no terminal: sudo apt-get install python3-pip.
7. Para verificar se o pip foi instalado corretamente, digite o seguinte comando no terminal: pip3 --version.
Pronto, agora você tem o Python instalado em sua máquina com Linux e pode começar a escrever e executar programas em Python.

Mac: Para instalar o Python em uma máquina com Mac, siga os seguintes passos:
1. Acesse o site oficial de download do Python: https://www.python.org/downloads/.
2. Clique no botão "Download Python X.X.X" (onde X.X.X é a versão mais recente do Python disponível).
3. Role a página até encontrar os downloads para Mac e clique no instalador "macOS 64-bit installer".
4. Abra o arquivo .pkg baixado e siga as instruções do instalador.
5. Certifique-se de marcar a opção "Install for all users" e "Add Python X.X to PATH" para que o Python possa ser acessado de qualquer diretório em seu Mac.
6. Clique em "Install" para iniciar a instalação.
7. Aguarde até que a instalação seja concluída. O instalador irá notificá-lo quando estiver concluído.
8. Para verificar se o Python foi instalado corretamente, abra o terminal e digite "python3 --version". Isso deve mostrar a versão do Python instalada em seu Mac.
Após a instalação do Python, você pode começar a escrever e executar programas em Python no terminal ou utilizando um ambiente de desenvolvimento integrado (IDE) como PyCharm, VS Code, entre outros.

Você pode instalar todas as dependências utilizando o pip:

1. Copy code
2. pip install -r requirements.txt
3. Como usar
4. Clone este repositório na sua máquina.
5. Insira a chave de acesso à fonte de dados no arquivo config.py.
6. Rode o script utilizando o seguinte comando:
7. Copy code
8. python script.py
9. O script irá adquirir os dados da fonte especificada e salvá-los em um arquivo CSV na pasta data. Em seguida, será feita uma análise dos dados e serão gerados alguns gráficos para visualização.

Contribuições
Este script foi criado como um exemplo simples de aquisição de dados. Contribuições para melhorias e novas funcionalidades são sempre bem-vindas.

Licença
Este projeto está licenciado sob a licença MIT - consulte o arquivo LICENSE para obter detalhes.
