// script.js

// Função para alternar o tema claro/escuro
document.getElementById('themeButton').addEventListener('click', function() {
  document.body.classList.toggle('modo-escuro');
});

// Função para alternar entre fontes
document.getElementById('fontButton').addEventListener('click', function() {
  // Alterna entre as fontes padrão, secundária e terciária
  if (document.body.classList.contains('fonte-secundaria')) {
    document.body.classList.remove('fonte-secundaria');
    document.body.classList.add('fonte-terciaria');
  } else if (document.body.classList.contains('fonte-terciaria')) {
    document.body.classList.remove('fonte-terciaria');
    document.body.classList.add('fonte-padrao');
  } else {
    document.body.classList.add('fonte-secundaria');
  }
});

// Função para aumentar o tamanho da fonte
document.getElementById('sizeButton').addEventListener('click', function() {
  document.body.classList.toggle('aumentar-fonte');
});
