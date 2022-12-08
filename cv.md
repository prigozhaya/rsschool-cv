## [rsschool-cv](#адрес "cv")
----
# **Prigozhaya Elizaveta**
----
### Junior Frontend Developer
----
### Contacts
**Phone:** +375445331051

**E-mail:** elizavetaprigozhaya@gmail.com

[![N|Solid](https://i.ibb.co/54PLNpS/ion-logo-behance.png)](https://www.behance.net/Prigozhaya) [![N|Solid](https://i.ibb.co/ZLFcsJF/cib-telegram.png)](https://t.me/gorekorabl) [![N|Solid](https://i.ibb.co/93NftjB/bi-github.png)](https://github.com/prigozhaya)
-----
-----
### About me
I have an analytical mind and a sense of taste. I am responsible and fast learner. I love to create beautiful solutions. I strive to design useful and attractive websites.

-----
### Skills
* HTML
* CSS
* JavaScript (Basic)
* Figma
* Adobe Photoshop
* SQL
----
### Code example
ROT13 is a simple letter substitution cipher that replaces a letter with the letter 13 letters after it in the alphabet. ROT13 is an example of the Caesar cipher.
Create a function that takes a string and returns the string ciphered with Rot13. If there are numbers or special characters included in the string, they should be returned as they are. Only letters from the latin/english alphabet should be shifted, like in the original Rot13 "implementation".
```
function rot13(message) {
  let arr = message.split("");
  for (let i in arr)
    if (arr[i].match("^[a-zA-Z]+$")) {
      let code = arr[i];
      if (code.match("^[n-zN-Z]+$")) {
        code = code.charCodeAt(0) - 13;
      } else {
        code = code.charCodeAt(0) + 13;
      }
      arr[i] = String.fromCharCode(code);
    }
  return arr.join("");
}
```

----
### Education

**Belarusian State University of Informatics and Radioelectronics**
2018 - 2022 Bachelor
Specialty - information technology and management in technical systems

**Educational Center for Programming and High Technologies "IT-Academy"**
2020 - 2021
Training in UI/UX design tools
Web and mobile interface design

-----
### Languages
English - Intermediate (B1) certificate of Streamline Language School
Russian - Native
