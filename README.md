<h1>Ataque Phishing</h1>

Nesse projeto criaremos um ataque phishing com o sistema operacional Kali Linux.

**Requistos do projeto**

 - [Conhecimento básico com sistemas operacionais do Linux;](https://www.hostgator.com.br/blog/linux-tudo-sobre-sistema/)
 - [Conhecimento básico em maquina virtual;](https://www.redhat.com/pt-br/topics/virtualization/what-is-a-virtual-machine)  
 - [Conhecimento básico em Pentest;](https://resh.com.br/blog/pentest-o-que-e-como-funciona-e-para-que-serve/)

**Ferramentas utilizadas**

- Kali Linux;
- Gnome box; 
- Setoolkit;
- Visual Studio Code

<h2>Instalação e configuração</h2>

<h3>Gnome Box</h3>

A instalação do Gnome Box pode ser feita no site [oficial](https://apps.gnome.org/en/Boxes/), estou utilizando o sistmema
operacional fedora. Com isso, utilizei o terminal seguindo os seguintes passos

<h4>1. Atualização do sitema</h4>

Para a instalação do Kali Linux é importante ler a documentação do sistema operacioanal, como
também qual a maquina virtual será usada. Nesse projeto, usarei a [***Gnome Box***](https://apps.gnome.org/en/Boxes/):

```bash
sudo dnf update
```

<h4>2. Instalação do Gnome</h4>

Estou utilizando o gerenciador de pacote **dnf**:

```bash
sudo dnf install gnome-boxes
```

<h4>3. Verificar a instalação</h4>

```bash
gnome-boxes --version
```

<h3>Kali Linux</h3>

A instalação da imagem iso pode ser feita no site [oficial](https://www.kali.org/get-kali/#kali-installer-images), utilizei a opção **Installer images => Kali Linux 2024.4 Changelog** 

<h3>Setoolkit</h3>

No terminal da maquina virtal do Kali Linux digite para entra como sudo:

```bash
sudo su
```

Depois de colocar sua senha, iniciei o setoolkit:

```bash
setoolkit
```
<img src="https://github.com/user-attachments/assets/ca610a75-3ec8-4cf4-b529-762872172a4b" alt="Design sem nome (1)" width="500" height="400" />

<br></br>

Agora iremos escolher a opção de tipo de ataque:

```txt
Social-Engineering Attacks 
```

<img src="https://github.com/user-attachments/assets/178f0323-97be-44cf-b789-ff16b7422811" alt="passo1" width="500" height="400" />

<br></br>
Nosso vertor de ataque:

```txt
Web Site Attack Vectors
```

<img src="https://github.com/user-attachments/assets/81e08e3a-a406-4c90-8a09-f99cc558e9de" alt="passo2" width="500" height="400" />








