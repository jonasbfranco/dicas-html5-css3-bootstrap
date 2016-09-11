#Dicas de HTML5, CSS3 e BOOTSTRAP.
##Nestas dicas vamos usar Linux Ubuntu como Sistema Operacional.

##Canal YouTube - [https://www.youtube.com/c/JonasFranco](https://www.youtube.com/c/JonasFranco "Dicas de HTML5, CSS3 e BOOTSTRAP")


## DICAS

### 1ª Dica
* Media Querys - Resolução da sua Página para diversos Dispositivos, uma rápida explicação.

/* SmartPhone */
@media (max-width: 480px) and (orientation: portrait){
	.c_pc, .c_tablet{
		display: none;
	}

}

@media (max-width: 732px) and (orientation: landscape){
	.c_pc, .c_tablet{
		display: none;
	}	
}



/* tablet */
@media (min-width: 481px) and (max-width: 1024px) and (orientation: portrait){
	.c_smartphone, .c_pc {
		display: none;
	}
}

@media (min-width: 960px) and (max-width: 1280px) and (orientation: landscape){
	.c_smartphone, .c_pc {
		display: none;
	}
}


/* PC */
@media (min-width: 1366px) and (orientation: landscape){
	.c_smartphone, .c_tablet{
		display: none;
	}
}




### Até a próxima dica

