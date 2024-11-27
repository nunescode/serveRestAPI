# 🌟 Bootcamp #01 - **Qualiters Club!** 🌟  
🔧 **Teste de API Rest do manual ao CI/CD**  

---

## 📖 O que é  
Repositório criado para o bootcamp de teste de API Rest ministrado pela **Priscila Caimi**.  

---

## 🛠️ Tecnologias Utilizadas  

- ![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat&logo=postman&logoColor=white) **Postman**  
- ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white) **Node.js v20.16.0**  
- ![Newman](https://img.shields.io/badge/-Newman-000000?style=flat&logoColor=white) **Newman v6.2.1**  
- ![HTML Extra](https://img.shields.io/badge/-HTML%20Extra-4285F4?style=flat&logo=html5&logoColor=white) **Newman Reporter HTML Extra**  

---

## 📚 Documentações  

📄 **Doc da API**: [Consulta Swagger](https://serverest.dev/#/)  

---

## ⚙️ Como Instalar o Ambiente  

1. **Instale o Node.js**  
   - [Download Node.js](https://nodejs.org/en/download/package-manager)  

2. **Instale o Newman globalmente**  
   ```bash
   npm install -g newman
   ```

3. **Instale o Newman Reporter HTML Extra (opcional)**  
   ```bash
   npm install -g newman-reporter-htmlextra
   ```

---

## 🚀 Como Rodar os Testes  

### 🖥️ **Postman Desktop ou Web**  
1. Importe a **Collection** e o **Environment**.  
2. Execute os testes manualmente ou automatize-os.  

---

### 🖥️ **Pelo Newman (Linha de Comando)**  
1. Escolha o console de sua preferência.  
2. Execute os comandos abaixo:  

   - **Testes básicos**  
     ```bash
     newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
     ```

   - **Testes com relatório customizado**  
     ```bash
     newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r htmlextra
     ```

   - **Observação**: Para relatórios gerados com o `newman-reporter-htmlextra`, os arquivos serão salvos na pasta `newman`.  

---

## 📬 Entre em Contato  

📧 **E-mail**: [pedro.hq_@outlook.com](mailto:pedro.hq_@outlook.com)  
🌐 **LinkedIn**: [linkedin.com/in/nunescodex](https://linkedin.com/in/nunescodex)  

---
