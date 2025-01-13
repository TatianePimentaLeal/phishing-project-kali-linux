# Projeto - Phishing para captura de senhas em websites com Kali Linux

**Disclaimer**

Este projeto foi criado como parte da trilha de aprendizado do Bootcamp Santander DIO Cybersecurity e não tem intenção de comprometer ou prejudicar qualquer sistema.

---

## **Phishing para captura de senhas com o SETOOLKIT**

Acessar o Kali Linux em modo root

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-1.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-1.png)



Iniciar o SETOOLKIT

```
setoolkit
```

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-2.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-2.png)



Concordar com os termos de serviço

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-3.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-3.png)



Para o projeto, dentre as opções, foi selecionado o item 1

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-4.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-4.png)



![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-5.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-5.png)



![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-6.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-6.png)



Dentre os vetores de ataque apresentados, selecionar o item 2 “”Website Atack Vectors”

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-7.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-7.png)



![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-8.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-8.png)



Escolher a opção 3 “Credential Harvester Attack Method”

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-9.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-9.png)



No menu de opções seguinte, selecionar a opção 2 “Site Cloner”

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-10.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-10.png)



No passo seguinte, o SETOOLKIT informa que o Site Cloner funciona clonando o site e buscando campos para reeescrever. Ele rodará um pequeno servidor com a página falsa, por isso o IP da máquina é necessário, o que justifica a configuração de rede do Kali Linux precisar do modo Bridge

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-11.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-11.png)

O Site Cloner vai sugerir um IP ao final do texto de explanação

> set:webattack> IP address for the POST back in Harvester/Tabnabbing [192.168.1.42]:

E então clicamos em ENTER

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-12.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-12.png)



Será solicitada a URL a ser clonada: [Login | Alura - Cursos online de tecnologia](https://cursos.alura.com.br/loginForm)

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-13.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-13.png)



Para acessar a página clonada, é só acessar utilizando o IP (no caso, o IP utilizado foi)

> 192.168.1.42

A partir da URL provida, o Site Cloner irá iniciar a clonagem

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-14.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-14.png)



E a captura dos dados será iniciada

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-15.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-15.png)



Ao final das ações ainda é possível gerar um relatório do exploit

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-16.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-16.png)



Que será salvo e pode ser acessado conforme o caminho provido pelo SETOOLKIT

![phishing-project-kali-linux/phishing-kali-linux-cybersec_img/projeto-kali-phishing-17.png at main · TatianePimentaLeal/phishing-project-kali-linux · GitHub](https://github.com/TatianePimentaLeal/phishing-project-kali-linux/blob/main/phishing-kali-linux-cybersec_img/projeto-kali-phishing-17.png)
