self.addEventListener('fetch', event => {
  // O service worker está aqui para permitir a instalação (PWA),
  // mas não implementa caching offline para manter a simplicidade.
  // A app continuará a precisar de internet para contactar a base de dados.
});