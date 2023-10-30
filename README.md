Piano Simulator Documentation in English and Portuguese below:

 # **Piano Simulator Documentation**

## Introduction  
The Piano Simulator is a project developed as part of a challenge in a bootcamp. It provides an interactive interface that allows users to simulate playing musical notes as on a real piano, both through the keyboard and by clicking on the interface.

## **Project Structure**  
The project comprises four main files: index.html, main.css, reset.css, and engine.js.

**1. index.html**  
This file contains the HTML structure of the application, defining the page's structure, interaction elements such as the virtual piano keyboard, volume controls, and options to show or hide the keys.

**2. main.css**  
The main.css file is responsible for the visual style and appearance of the piano simulator. It defines the layout, colors, sizes, and styles of the elements present on the page.

**3. reset.css**  
The reset.css file is used to reset the default browser styles, ensuring visual consistency across different browsers. Additionally, it sets the font type used in the project.

**4. engine.js**  
The engine.js file contains the core logic of the piano simulator. It defines how click and keyboard events are handled to play the corresponding musical notes, control volume, and show or hide the piano keys on the interface.

## **Key Features**
**Note Playback**  
Clicking on a piano key on the interface or pressing the corresponding key on the keyboard triggers the simulator to produce the sound of the musical note associated with that key.  
**Volume Control**  
A slider control allows users to adjust the volume of the sound played by the simulator.  
**Show/Hide Keys**  
A toggle button on the interface enables users to display or hide the piano keys, offering a customizable user experience.  

**Code Explanation (engine.js)**  
**The engine.js file governs the core logic of the project. Here are some key functions and behaviors implemented:**  

**playTune()**: This function plays the sound of the musical note associated with the pressed or clicked key. It also briefly highlights the active key visually.

**Click and Keyboard Events:** Individual click events are implemented for each piano key on the interface, enabling the playback of the associated musical notes. Additionally, keyboard events are captured to facilitate playing musical notes via the physical keyboard keys.

**Volume Control:** The handleVolume() function adjusts the sound volume according to the slider's position.

**Show/Hide Keys:** The showHideKeys() function toggles the visibility of the keys on the interface.

## **Conclusion**  
The Piano Simulator project showcases the use of HTML, CSS, and JavaScript to create an interactive interface that mimics the experience of playing a piano. It provides basic functionalities for playing musical notes, volume control, and interface customization.

This documentation offers an overview of the project and its structure, providing insights into the implementation and functioning of the Piano Simulator.


--------------------------------------------------------------------


# **Documentação do Simulador de Piano**

## Introdução  
O Simulador de Piano é um projeto desenvolvido como parte de um desafio em um bootcamp. Ele oferece uma interface interativa que permite simular a reprodução de notas musicais como um piano real, tanto por meio do teclado quanto por cliques na interface.

## Estrutura do Projeto  
O projeto é composto por quatro principais arquivos: index.html, main.css, reset.css e engine.js.

**1. index.html**  
Este arquivo contém a estrutura HTML da aplicação, definindo a estrutura da página, os elementos de interação, como o teclado virtual do piano, controles de volume e opções para exibir ou ocultar as teclas.

**2. main.css**  
O arquivo main.css é responsável pelo estilo e aparência visual do simulador de piano. Ele define o layout, as cores, tamanhos e estilos dos elementos presentes na página.

**3. reset.css**  
O arquivo reset.css é usado para resetar os estilos padrão do navegador, garantindo consistência visual entre diferentes navegadores. Além disso, ele define o tipo de fonte utilizada no projeto.

**4. engine.js**  
O arquivo engine.js contém a lógica principal do simulador de piano. Ele define como os eventos de clique e teclado são manipulados para reproduzir os sons das notas musicais correspondentes, controlar o volume e mostrar ou ocultar as teclas do piano na interface.

## **Funcionalidades Principais**
**Reprodução de Notas**  
Ao clicar em uma tecla do piano na interface, ou pressionar a tecla correspondente no teclado, o simulador reproduz o som da nota musical associada àquela tecla.  
**Controle de Volume**  
Um controle deslizante (slider) permite ajustar o volume do som reproduzido pelo simulador.  
**Mostrar/Ocultar Teclas**  
Um botão de alternância na interface permite mostrar ou ocultar as teclas do piano, proporcionando uma experiência personalizável ao usuário.  

**Explicação do Código (engine.js)**  
**O arquivo engine.js é responsável pela lógica principal do projeto. Aqui estão algumas das funções e comportamentos-chave implementados:**

**playTune():** Esta função reproduz o som da nota musical correspondente à tecla pressionada ou clicada. Além disso, ela destaca visualmente a tecla ativa por um breve período.

**Evento de Clique e Teclado:** É implementado um evento de clique para cada tecla do piano na interface, permitindo a reprodução do som da nota associada. Também é capturado o evento de teclado para permitir a reprodução das notas musicais através das teclas do teclado físico.

**Controle de Volume:** A função handleVolume() é responsável por ajustar o volume do som reproduzido, de acordo com a posição do controle deslizante.

**Mostrar/Ocultar Teclas:** A função showHideKeys() possibilita alternar a visibilidade das teclas na interface.

## **Conclusão**  
O Simulador de Piano é um projeto que demonstra a utilização de HTML, CSS e JavaScript para criar uma interface interativa que simula a experiência de tocar um piano. Ele oferece funcionalidades básicas de reprodução de notas musicais, controle de volume e personalização da interface.

Esta documentação fornece uma visão geral do projeto e sua estrutura, permitindo compreender a implementação e funcionamento do Simulador de Piano.
