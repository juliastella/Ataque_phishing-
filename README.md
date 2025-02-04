# Ataque Phishing para Captura de Dados de Login

Este projeto demonstra a criação de um ataque phishing utilizando os sistemas operacionais Kali Linux ou Parrot Security.

## 📌 Pré-requisitos

- Kali Linux ou Parrot Security
- Gnome Boxes
- Setoolkit
- Visual Studio Code

---

## 🚀 Instalação e Configuração

### 🖥️ Gnome Boxes
A instalação do Gnome Boxes pode ser feita através do [site oficial](https://apps.gnome.org/en/Boxes/). Neste projeto, estou utilizando o sistema operacional Fedora. Portanto, utilizei o terminal e segui os seguintes passos:

#### 1️⃣ Atualização do Sistema
Antes de instalar o Kali Linux, é importante consultar a documentação oficial do sistema operacional e decidir qual máquina virtual será utilizada. Neste projeto, utilizarei o [**Gnome Boxes**](https://apps.gnome.org/en/Boxes/).

Atualize o sistema com:
```bash
sudo dnf update && sudo dnf upgrade
```

#### 2️⃣ Instalação do Gnome Boxes
Utilizando o gerenciador de pacotes **dnf**:
```bash
sudo dnf install gnome-boxes
```

#### 3️⃣ Verificar a Instalação
```bash
gnome-boxes --version
```

---

### 📥 Instalação do Kali Linux ou Parrot Security
A imagem ISO pode ser baixada nos sites oficiais:
- [Kali Linux](https://www.kali.org/get-kali/#kali-platforms)
- [Parrot Security](https://parrotsec.org/download/)

Opções utilizadas neste projeto:
- **Kali Linux** → *Installer images → Kali Linux 2024.4 Changelog*
- **Parrot Security** → *Live → Security → AMD64*

---

### 🛠️ Configuração do Setoolkit

#### 🔹 Parte 1: Iniciando o Setoolkit
No terminal da máquina virtual do Kali Linux, entre como superusuário:
```bash
sudo su
```
Após inserir a senha, inicie o **Setoolkit**:
```bash
setoolkit
```


<img src="https://github.com/user-attachments/assets/ca610a75-3ec8-4cf4-b529-762872172a4b" alt="Design sem nome (1)" width="500" height="400" />

<br></br>
> **Escolha o tipo de ataque:**

Social-Engineering Attacks



<img src="https://github.com/user-attachments/assets/178f0323-97be-44cf-b789-ff16b7422811" alt="passo1" width="500" height="400" />

<br></br>
> **Selecionar vetor de ataque:**

Web Site Attack Vectors



<img src="https://github.com/user-attachments/assets/81e08e3a-a406-4c90-8a09-f99cc558e9de" alt="passo2" width="500" height="400" />

<br></br>
> **Módulo de ataque web:**

Credential Harvester Attack Method



<img src="https://github.com/user-attachments/assets/fa4531ef-c5a7-47fb-a8f5-e4f1e97e1c2e" alt="passo3" width="500" height="400" />

<br></br>
> **Método de ataque:**

Custom Import



<img src="https://github.com/user-attachments/assets/1851173e-f06c-4d6f-9b66-0c79033cb9d5" alt="passo4" width="400" height="200" />

<br></br>
#### 🔹 Parte 2: Configuração do Ataque
Após selecionar o método de ataque, pressione **Enter** para confirmar o **IP da máquina**.


<img src="https://github.com/user-attachments/assets/25cc5dc9-f3ec-4787-8397-0094afb00548" alt="passo5" width="500" height="400" />

<br></br>
Em seguida, adicione a **URL de login** desejada. Neste caso, utilizarei **www.facebook.com**.


<img src="https://github.com/user-attachments/assets/dc3b7c15-284d-40f3-9930-c3e0bc5337b3" alt="passo6" width="500" height="400" />

<br></br>
Agora, vá até o site do Facebook e salve a página como um arquivo contendo o código-fonte:


<img src="https://github.com/user-attachments/assets/57d1c2bd-8ac8-4f86-8e9b-783d26687d20" alt="passo7" width="500" height="400" />

<br></br>
Depois, abra o código salvo no **Visual Studio Code**, localize o botão de **Login** via **Inspect Element (Q)** e copie seu ID. Em seguida, remova esse ID do código.


<img src="https://github.com/user-attachments/assets/e1287be6-fd90-415c-87a9-a71b3d2d2c25" alt="passo8" width="500" height="400" />

<br></br>
Agora, no **Path to the website you imported**, informe o caminho do arquivo salvo. Na opção **URL of the website you imported**, insira `www.facebook.com`.


<img src="https://github.com/user-attachments/assets/aeb14373-1a45-42dd-bf79-0d49965bde10" alt="passo10" width="500" height="400" />


---

## 🎯 Resultado
Após concluir o processo, conseguimos visualizar os dados capturados, incluindo **e-mail** e **senha**:


<img src="https://github.com/user-attachments/assets/cd02056e-d791-4c3d-8ef0-776fd1abf31c" alt="passo11" width="500" height="400" />


---

## ⚠️ Nota de Esclarecimento
Este repositório tem **fins educacionais** e busca contribuir para o conhecimento geral da comunidade sobre segurança cibernética. Lembramos que o uso de ataques phishing com intenção maliciosa é crime e está previsto na [Lei 14.155/2021](https://www12.senado.leg.br/noticias/materias/2021/05/28/lei-com-penas-mais-duras-contra-crimes-ciberneticos-e-sancionada).

---

**🔒 Estude cibersegurança de forma ética!**

