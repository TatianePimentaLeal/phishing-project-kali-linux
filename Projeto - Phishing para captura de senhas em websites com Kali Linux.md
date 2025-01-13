# Projeto - Phishing para captura de senhas em websites com Kali Linux

**Disclaimer**

Este projeto foi criado como parte da trilha de aprendizado do Bootcamp Santander DIO Cybersecurity e não tem intenção de comprometer ou prejudicar qualquer sistema.

---

## **Phishing para captura de senhas com o SETOOLKIT**

Acessar o Kali Linux em modo root

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-1.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-1.png)

img 1

Iniciar o SETOOLKIT

```
setoolkit
```

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-2.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-2.png)

img 2



Concordar com os termos de serviço

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-3.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-3.png)

img 3



Para o projeto, dentre as opções, foi selecionado o item 1

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-4.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-4.png)

img 4

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-5.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-5.png)

img 5

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-6.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-6.png)

img 6



Dentre os vetores de ataque apresentados, selecionar o item 2 “”Website Atack Vectors”

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-7.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-7.png)

img 7

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-8.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-8.png)

img 8



Escolher a opção 3 “Credential Harvester Attack Method”

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-9.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-9.png)

img 9



No menu de opções seguinte, selecionar a opção 2 “Site Cloner”

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-10.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-10.png)

img10



No passo seguinte, o SETOOLKIT informa que o Site Cloner funciona clonando o site e buscando campos para reeescrever. Ele rodará um pequeno servidor com a página falsa, por isso o IP da máquina é necessário, o que justifica a configuração de rede do Kali Linux precisar do modo Bridge

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-11.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-11.png)

img11



O Site Cloner vai sugerir um IP ao final do texto de explanação

> set:webattack> IP address for the POST back in Harvester/Tabnabbing [192.168.1.42]:



E então clicamos em ENTER

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-12.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-12.png)

img 12



Será solicitada a URL a ser clonada: [Login | Alura - Cursos online de tecnologia](https://cursos.alura.com.br/loginForm)

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-13.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-13.png)

img13



Para acessar a página clonada, é só acessar utilizando o IP (no caso, o IP utilizado foi)

> 192.168.1.42



A partir da URL provida, o Site Cloner irá iniciar a clonagem

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-14.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-14.png)

img14



E a captura dos dados será iniciada

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-15.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-15.png)

img15



Ao final das ações ainda é possível gerar um relatório do exploit

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-16.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-16.png)

img16



Que será salvo e pode ser acessado conforme o caminho provido pelo SETOOLKIT

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-17.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-17.png)

img17
