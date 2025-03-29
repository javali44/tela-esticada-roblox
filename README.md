// Seleciona o elemento que contém a tela do jogo (ajuste conforme necessário)
const gameScreen = document.querySelector("#gameScreen"); // ou o seletor correto do seu jogo

// Função para ajustar o tamanho da tela
function stretchGameScreen() {
    // Ajusta a largura e altura da tela para o tamanho da janela
    gameScreen.style.width = window.innerWidth + 'px';
    gameScreen.style.height = window.innerHeight + 'px';
}

// Chama a função para ajustar o tamanho da tela inicialmente
stretchGameScreen();

// Ajusta automaticamente a tela quando a janela for redimensionada
window.addEventListener('resize', stretchGameScreen);
