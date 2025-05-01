#🎗️ Exercício 3 - Componente Campanha com CSS Modularizado
Este exercício tem como objetivo a criação de um componente React chamado `Campanha`, utilizando **CSS Modules** para aplicar estilos condicionais de acordo com o mês informado.

---

📚 Questão A) Crie um CSS Modularizado para um componente chamado Campanha.
• Esse componente exibe na tela uma mensagem de acordo com o mês.
• Essa frase deve ser exibida na cor preta.
• A cor de fundo de uma tarja (pode ser uma div) e a mensagem (dentro da tarja) devem mudar de acordo com o mês que passamos como prop (string) para o componente filho.
• Setembro -> cor: amarelo, mensagem: Prevenção ao suicídio.
• Outubro -> cor: rosa, mensagem: Conscientização sobre o câncer de mama.
• Novembro -> cor: azul, mensagem: Prevenção e combate ao câncer de próstata.

<h1>Solução: </h1>

O componente `Campanha` recebe via **props** o nome de um mês (string). A partir disso:

- Exibe uma **mensagem específica** relacionada à campanha do mês.
- A **cor de fundo** da tarja (div) muda conforme o mês informado.
- A **mensagem** sempre é exibida em cor **preta**.
- Os estilos são organizados com **CSS Modularizado** para manter o encapsulamento e evitar conflitos.

🛠️ Código do Componente

![image](https://github.com/user-attachments/assets/6241cb6d-df76-4daa-9d72-206576083d92)

💻 Resultado no navegador:

![image](https://github.com/user-attachments/assets/795e7a7e-98a8-43c0-b716-e34d5f3e8623)
![image](https://github.com/user-attachments/assets/8ed09e72-bf75-4e41-b85c-923523a1815d)
![image](https://github.com/user-attachments/assets/87c3b112-5000-4a99-8011-7c491c6f4385)
