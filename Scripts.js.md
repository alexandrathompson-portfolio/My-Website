# Scripts.js  
  
// Smooth Scroll for Navigation  
document.querySelectorAll('a[href^="#"]').forEach(anchor => {  
  anchor.addEventListener('click', function(e) {  
    e.preventDefault();  
    document.querySelector(this.getAttribute('href')).scrollIntoView({  
      behavior: 'smooth'  
    });  
  });  
});  
  
// Contact Form Validation  
document.getElementById('contact-form').addEventListener('submit', function(e) {  
  e.preventDefault();  
  const name = document.getElementById('name').value;  
  const email = document.getElementById('email').value;  
  const message = document.getElementById('message').value;  
  
  if (name && email && message) {  
    alert('Form submitted! (This is a demo; replace with email API.)');  
    this.reset();  
  } else {  
    alert('Please fill out all fields.');  
  }  
});  
