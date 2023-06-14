document.getElementById('formjs').addEventListener("submit", (e) => {
  e.preventDefault();

  // Datos de usuarios y contraseñas almacenados en un diccionario
  const users = {
    "karen@gmail.com": "123",
    "josias@gmail.com": "456",
    "patricia@gmail.com": "789",
    // Agrega más usuarios y contraseñas según sea necesario
  };
  
  let email = document.getElementById('inputEmail').value;
  let password = document.getElementById('inputPassword').value;

  if (users.hasOwnProperty(email) && users[email] === password) {
    window.location.href = "menuPrincipal.html";
  } else {
    alert("Email o Password incorrecto");
  }
});
