# 🦷 StepView  

StepView é um projeto desenvolvido para facilitar o agendamento de consultas em clínicas odontológicas, oferecendo uma interface simples e intuitiva tanto para pacientes quanto para administradores. O objetivo é otimizar o processo de reserva de horários, proporcionando uma experiência mais fluida e organizada.  

---

## 🎯 Tecnologias Utilizadas  

- **PHP**: Lida com a lógica de backend da aplicação.  
- **Hack**: Linguagem derivada do PHP, trazendo mais desempenho e recursos adicionais.  
- **CSS**: Cuida da estilização, tornando a interface moderna e responsiva.  
- **JavaScript**: Garante interatividade e melhora a experiência do usuário.  
- **HTML**: Define a estrutura das páginas web.  

---

## 🚀 Funcionalidades  

### 🔹 Para Secretária 
- **Agendamento de Consultas**: Checar estado do cliente no sistema
- **Administrar dados do cliente**: Manter CRUD, Procurar cliente, Consultar cadastro  


### 🔹 Para Odontológico 
- **Checar Informações gerais do Cliente**: Adicionar comentários no perfil, Criar agenda da consulta   


### 🔹 Para Gerente Administrativo
- **Analisar métricas de clientes**: Aplicar filtragem de datas    
- **Adicionar usuários**: Definir controle de permissão dos funcionários

---

## 🛠️ Instalação  

### ✅ Requisitos  
- [MySQL](https://www.mysql.com/)  

### 📌 Passo a Passo  

1. **Clone o repositório:**  
    ```bash
    git clone https://github.com/Angelsseq/StepView.git  
    cd StepView  
    ```

2. **Instale as dependências:**  
    ```bash
    npm install  
    ```

3. **Configure o banco de dados** (se necessário).  

4. **Inicie o servidor:**  
    ```bash
    npm start  
    ```

5. **Abra o navegador e acesse:**  
    ```bash
    http://localhost:3306  
    ```
    *(Obs: o padrão pode ser 3307, ajuste conforme sua configuração.)*  

---

## 🤝 Como Contribuir  

1. **Faça o fork deste repositório.**  
2. **Crie uma nova branch:**  
    ```bash
    git checkout -b feature/NovaFuncionalidade  
    ```
3. **Implemente suas modificações.**  
4. **Envie um pull request para o branch principal.**  

---

## 📂 Estrutura de Diretórios  

```bash
StepView/  
├── CORPOS      # Código backend em PHP  
├── ESTILOS     # Estilos em CSS  
├── IMAGENS     # Imagens e outros arquivos públicos  
├── OUTROS      # SQL e outros recursos  
├── SCRIPTS     # JavaScript e páginas HTML  
└── README.md   # Este arquivo  
