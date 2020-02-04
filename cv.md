# Andrei Chapiuk
____
#### My contacts:
[![N|Solid](https://s3.us-east-2.amazonaws.com/upload-icon/uploads/icons/png/4299173531574338602-64.png)](<venik2281488@gmail.com>)[![N|Solid](https://s3.us-east-2.amazonaws.com/upload-icon/uploads/icons/png/1766858341556105723-64.png)](https://telegram.me/kod321)
### Purpose of my training:
>I am interested in web development, and I want to learn how to develop on a high level, what I’m doing now while studying in RSS.
I am also interested in new technologies and development in the modern world.
I have poor technical knowledge for now but I try to do everything to fix it.
I like training, it’s interesting :)
### My skills: 
  - HTML.
  - CSS/SCSS.
    - JavaScript.
  - Git.
  - Bootstrap.
  - Layout by PSD and figma.
  - Adaptive layout.
### Code examples:
```sh
function validatePIN(pin) {
  if (pin.length == 4 ) {
  for (let i = 0; i < 4; i++) { 
   if ( pin[i] == '\n') {
        return false;
      }
    if (isNaN(pin[i]) == true){
  return false;
        }
  }
  return true;
  }
  if (pin.length == 6) {
  for (let i = 0; i < 6; i++) {
     if ( pin[i] == '\n'){
        return false;
      }
    if (isNaN(pin[i]) == true){
  return false;
      }
  }
  return true;
  }
  if ( pin.length != 4) {
  return  false;
  } 
  if ( pin.length != 6) {
  return  false;
  } 
}
// Функция принимает PIN (только цифры, length = 4||6);
```