# 👓 PlayerVR - Video Player com Efeito "Ambient Light"

PlayerVR é um projeto conceitual de um player de vídeo imersivo, desenvolvido com **HTML, CSS e JavaScript puros**. A principal inovação deste projeto é a criação de um efeito de **"Ambient Light"** (luz ambiente), que utiliza a API de IFrame do YouTube para sincronizar dois vídeos, proporcionando uma experiência visual mais envolvente.

---

### **🎬 Demonstração**

![image](https://github.com/YanzinhoCaue/PROJETO-PLAYER-VR/assets/127339610/af82714a-0775-4d94-8d90-8e0283660ecd)

---

### **✨ Features e Inovações Técnicas**

* **Efeito "Ambient Light" com a API do YouTube**:
    * O efeito é criado utilizando **duas instâncias do Player de Vídeo do YouTube** carregadas e sincronizadas via JavaScript.
    * O player de fundo (`ambient-light`) é estilizado com CSS para ficar borrado e posicionado atrás do player principal.
    * Os estados dos dois players (Play, Pause) são sincronizados em tempo real através dos **event listeners da API do YouTube**, garantindo que o efeito de luz ambiente corresponda sempre ao vídeo principal.
    * Para otimizar o desempenho, o vídeo de fundo é configurado para rodar na **menor qualidade possível**, economizando banda.

* **Design Moderno com Glassmorphism**:
    * A interface do player (menus laterais, rodapé) foi desenhada com o efeito de **Glassmorphism** ("vidro fosco"), utilizando a propriedade `backdrop-filter: blur()` do CSS para criar um visual moderno e translúcido.

* **Layout com CSS Grid**:
    * A estrutura principal da aplicação (`header`, `main`, `aside`, `footer`) foi construída de forma semântica e organizada com **CSS Grid Layout**, demonstrando o uso de técnicas de layout modernas.

* **Animações de Entrada com CSS**:
    * A aplicação possui uma animação de entrada suave, criada com `@keyframes`, que melhora a experiência inicial do usuário.

---

### **🛠️ Tecnologias Utilizadas**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![YouTube](https://img.shields.io/badge/YouTube_API-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
![Ionicons](https://img.shields.io/badge/Ionicons-3880FF?style=for-the-badge&logo=ionic&logoColor=white)

---

### **▶️ Como Executar o Projeto**

Este é um projeto estático que consome uma API externa.

**Simplesmente clone o repositório e abra o arquivo `index.html` em um navegador moderno.** É necessária uma conexão com a internet para que a API do YouTube e os ícones funcionem.

```bash
git clone [https://github.com/YanzinhoCaue/projeto-player-vr.git](https://github.com/YanzinhoCaue/projeto-player-vr.git)
cd projeto-player-vr
# Abra o arquivo index.html

🧠 Principais Aprendizados
 * Manipulação de APIs Externas: Interação avançada com a API de IFrame do YouTube, incluindo carregamento dinâmico, controle de estado e otimização de players.
 * Técnicas de CSS Moderno: Aplicação prática de CSS Grid, backdrop-filter para o efeito de Glassmorphism e animações com @keyframes.
 * Sincronização de Eventos com JavaScript: Criação de uma lógica para manter dois elementos (os players) sincronizados com base nas ações do usuário.
💬 Contato
Yan Cauê
LinkedIn: linkedin.com/in/yancaue
GitHub: github.com/YanzinhoCaue

