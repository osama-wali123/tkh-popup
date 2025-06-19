setTimeout(() => {
  let menuItems = document.querySelectorAll('.nav-item a');
  let firstDiv = document.querySelector('.widget.widget-popup > div:first-of-type');
  let svg = document.querySelector('.widget.widget-popup svg');

  if (menuItems.length && firstDiv && svg) {
    menuItems.forEach(item => {
      if (item.textContent.trim() === 'TKH Coin') {
        item.addEventListener('click', function(e) {
          e.preventDefault();
          setTimeout(() => {
            firstDiv.style.display = 'flex';
          }, 1000);
        });
      }
    });

    svg.addEventListener('click', function(e) {
      e.preventDefault();
      firstDiv.style.display = 'none';
    });
  }
}, 3000);
