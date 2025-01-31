Descriptografar arquivo
Objetivo é descriptograr um arquivo para o arquivo se tornar legivel novamente.

Ferramentas utilizadas:
Kali Linux (https://www.kali.org/)
Linguagem Python (https://www.python.org/)
NANO (neste exemplo usaremos o NANO para construir e executar o código, mas podem usarem outras ferramentas como myCompiler, CMD etc. Já tem instalado no Kali) 
Para descriptograr arquivo, precisa usar o mesmo padrão de criptor. 

Código construido aqui é um simples, pode ser melhorado automatizando a localização do arquivo, por exemplo.

Caso ao executar o codigo apresente o erro "ModuloNotFoundError: No modulo named 'pyaes'". Então, deve instalar a biblioteca: pyaes.

- sudo apt-get update && sudo apt-get upgrade

- sudo apt install python3-pyaes
Resumo:
Acesso o Terminal Emulator (CMD)
Iniciar NANO: nano
Construir o código para abrir o arquivo criptografado
Construir o código para chave de descriptografar
Construir o código para remover o arquivo criptografado
Construir o código para criar o arquivo descriptografado
