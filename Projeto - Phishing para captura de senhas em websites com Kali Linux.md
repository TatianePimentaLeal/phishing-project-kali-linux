# Projeto - Phishing para captura de senhas em websites com Kali Linux



**Disclaimer**

Este projeto foi criado como parte da trilha de aprendizado do Bootcamp Santander DIO Cybersecurity e não tem intenção de comprometer ou prejudicar qualquer sistema.

---



## **Phishing para captura de senhas com o SETOOLKIT**



Acessar o Kali Linux em modo root

img 1



Iniciar o SETOOLKIT

```
setoolkit
```

img 2



Concordar com os termos de serviço

img 3



Para o projeto, dentre as opções, foi selecionado o item 1

img 4

img 5

img 6



Dentre os vetores de ataque apresentados, selecionar o item 2 “”Website Atack Vectors”

img 7

img 8



Escolher a opção 3 “Credential Harvester Attack Method”

img 9



No menu de opções seguinte, selecionar a opção 2 “Site Cloner”

img10



No passo seguinte, o SETOOLKIT informa que o Site Cloner funciona clonando o site e buscando campos para reeescrever. Ele rodará um pequeno servidor com a página falsa, por isso o IP da máquina é necessário, o que justifica a configuração de rede do Kali Linux precisar do modo Bridge

img11



O Site Cloner vai sugerir um IP ao final do texto de explanação

> set:webattack> IP address for the POST back in Harvester/Tabnabbing [192.168.1.42]:



E então clicamos em ENTER

img 12



Será solicitada a URL a ser clonada: [Login | Alura - Cursos online de tecnologia](https://cursos.alura.com.br/loginForm)

img13



Para acessar a página clonada, é só acessar utilizando o IP (no caso, o IP utilizado foi)

> 192.168.1.42



A partir da URL provida, o Site Cloner irá iniciar a clonagem

img14



E a captura dos dados será iniciada

img15



Ao final das ações ainda é possível gerar um relatório do exploit

img16



Que será salvo e pode ser acessado conforme o caminho provido pelo SETOOLKIT

img17


