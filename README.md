# Phishing-Kali-DIO
Resolução do Desafio "Criação de um Phishing com o Kali Linux"

1. Acessar como root: Primeiramente, é necessário obter acesso root (sudo su)
2. Iniciar o Social-Engineer Toolkit com o comando: setoolkit
3. Selecionar o tipo de ataque. Escolhi a opção 1) Social-Engineering Attacks digitando:
4. Escolher o vetor de ataque. Selecionei o vetor de ataque 2) Web Site Attack Vectors digitando:
5. Escolhi o método de ataque 3) Credential Harvester Attack Method digitando:
6. Selecionar o método "Site Cloner" (opção 2)
7. Obter o endereço IP da máquina virtual executando: ifconfig. Endereço IP exibido (192.168.100.92).
8. Clonar o site de destino. Digitei: http://www.google.com
9. Testar no navegador da máquina física. Abri o navegador na máquina física e insiri o endereço IP da máquina virtual.
    
Qualquer dado inserido nos campos será capturado e exibido no terminal do SET. O resultado que obtive foi:


![Kali Phishing](https://github.com/user-attachments/assets/77914457-8e41-407e-a1ae-533331a6de9b)
