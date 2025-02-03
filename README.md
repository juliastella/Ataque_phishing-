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

No terminal da maquina virtal do Kali Linux







