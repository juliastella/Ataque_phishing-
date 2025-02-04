<h1>Ataque Phishing para captura dados de login</h1>

Nesse projeto criaremos um ataque phishing com o sistema operacional Kali Linux ou Parrot Security.

**Prerequisitos**

- Kali Linux ou Parrot Security;
- Gnome box; 
- Setoolkit;
- Visual Studio Code

<h2>Instalação e configuração</h2>

<h3>Gnome Box</h3>

A instalação do Gnome Box pode ser feita no [site oficial](https://apps.gnome.org/en/Boxes/), estou utilizando o sistmema
operacional fedora. Com isso, utilizei o terminal seguindo os seguintes passos

<h4>1. Atualização do sitema</h4>

Para a instalação do Kali Linux é importante ler a documentação do sistema operacioanal, como
também qual a maquina virtual será usada. Nesse projeto, usarei a [***Gnome Box***](https://apps.gnome.org/en/Boxes/).

Necessário atualizar o sistema:

```bash
sudo dnf update && sudo dnf upgrade
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

<h3>Kali Linux ou Parrot Security</h3>

A instalação da imagem iso pode ser feita no [site oficial Kali Linux](https://www.kali.org/get-kali/#kali-installer-images) ou [site oficial Parrot Security](https://parrotsec.org/download/), utilizei a opção **Installer images => Kali Linux 2024.4 Changelog** 

<h3>Setoolkit</h3>

<h4>Parte 1</h4>

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

<br></br>
Módulo web ataque:

```txt
Credential Harvester Attack Method
```
<img src="https://github.com/user-attachments/assets/fa4531ef-c5a7-47fb-a8f5-e4f1e97e1c2e" alt="passo3" width="500" height="400" />

<br></br>
Método de ataque:

```txt
Custom Import
```

<img src="https://github.com/user-attachments/assets/1851173e-f06c-4d6f-9b66-0c79033cb9d5" alt="passo4" width="400" height="200" />


<h4>Parte 2</h4>

Depois da escolha do método de ataque, iremos confirmar o nosso **IP da maquina** somente apertando na tecla Enter:

<img src="https://github.com/user-attachments/assets/25cc5dc9-f3ec-4787-8397-0094afb00548" alt="passo4" width="400" height="200" />

<br></br>
Posteriomente, adicionaremos a nossa URl de login. Aqui estou utilizando a URL do **www.facebook.com**:

<img src="https://github.com/user-attachments/assets/dc3b7c15-284d-40f3-9930-c3e0bc5337b3" alt="passo4" width="400" height="200" />

Para continuar o processo indo até o site do Facebook, salvar a página em formato de arquivo com o código. Para isso, será necessario
aperta com o lado esquerdo do mouse e selecionar a opção **Save Page As...**:

<img src="" alt="passo4" width="400" height="200" />



