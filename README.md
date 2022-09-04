# LandinPage
Uma simples pagina de login, so ainda não terminei a responsividade por conta de outros projetos.
##Testei meus conhecimentos com uma pagina de Login :smile:

###Poderia ter usado **Jquery** mas usei javascript puro mesmo
```javascript
		var link = document.querySelector(".header");
		var btnLogar = document.querySelector("#btnLogar");
		var esc = document.querySelector(".esc");
		var btnCad = document.querySelector("#btnCadastrar");
		var cadas = document.querySelector(".cadastro");
		var p1 = document.querySelector(".p1");
		var log = document.querySelector(".login")
		var h1 = document.querySelector(".h1");
		btnLogar.addEventListener('click',function(){
			link.setAttribute("class","header2");
			esc.style.display = "none";
			cadas.style.display="none";
			p1.style.display="none";

		})
		btnCad.addEventListener('click',function(){
			link.setAttribute("class","header1");
			esc.style.display = "none";
			log.style.display="none";
			p1.style.display="none";
			h1.innerHTML = "Cadastrar"
			h1.style.color="purple"
		})


```
