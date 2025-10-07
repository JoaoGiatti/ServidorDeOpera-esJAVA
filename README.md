# ☕ Projeto Servidor & Cliente Java  
### Comunicação via Socket — Cliente e Servidor em Java

---

## 📖 Descrição Geral

Este projeto demonstra a comunicação **Cliente-Servidor em Java**, utilizando **sockets TCP/IP** para o envio e recebimento de mensagens entre duas aplicações independentes.

O **servidor** escuta conexões na porta configurada e responde às solicitações do **cliente**, que pode pedir um número aleatório ou encerrar a conexão.  
É um ótimo exercício prático para entender **redes, threads e fluxo de dados** em Java.

---

## 🚀 Guia de Execução

> ⚠️ **Pré-requisito:** Certifique-se de ter o **Java** instalado (versão recomendada: **Java 21** ou superior).

### 🧩 Etapa 1 — Executar o Servidor

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/JoaoGiatti/ServidorDeOpera-esJAVA.git
   cd [diretorioDoRepositorio]
   
2. **Compile os arquivos Java:**
   ```bash
   javac Servidor.java Cliente.java

3. **Execute o Servidor**
   ```bash
   java Servidor

4. O servidor será iniciado e ficará **aguardando conexões na porta 8888**.

---

### 💻 Etapa 2 — Executar o Cliente

5. **Abra outro terminal** (com o servidor ainda em execução).

6. **Compile os arquivos Java:**
   ```bash
   javac Servidor.java Cliente.java
   
7. **Execute o cliente:**
   ```bash
   java Cliente

8. **Aproveite para estudar o funcionamento, e brinque com o compilador de continhas!**

📍 PUC Campinas — Engenharia de Software  
🐙 [GitHub](https://github.com/JoaoGiatti)
