# PF2_De-Jesus_Castillo_Pedro-Isaac

ventana desde tkinter import * #llamamos las librerias from tkinter.ttk import *


![image](https://user-images.githubusercontent.com/79875930/112527309-8ad0ff80-8d68-11eb-92bd-a3661d846760.png)


window = Tk () window.title ("programa") #con windos tk inicializamos o arrancamos un programa lbl = Label (window, text = "robot", font = ("Arial Bold", 50)) #tenemos un objeto etiqueta con sus atributos de palabras lbl.grid (column = 0, row = 0) #pocicionamiento de etiqueta


![image](https://user-images.githubusercontent.com/79875930/112527318-8efd1d00-8d68-11eb-900c-486ba58f6bde.png)




txt = Entrada (ventana, ancho = 0) #tenemos otros objetos de texto con su pocicionamiento txt.grid (columna = 0, fila = 1)
txt.focus () #objeto focus


![image](https://user-images.githubusercontent.com/79875930/112527338-9290a400-8d68-11eb-8fa4-9ec038a0abeb.png)

def Cliked (): res = "inteligencia artificial" + txt.get () #metodo clik asignamos este evento y las secuencias que tendra al pulsar este objeto esque manda a llamar lbl.configure (text = res)


![image](https://user-images.githubusercontent.com/79875930/112527359-96bcc180-8d68-11eb-8601-51fc408975d7.png)

indow.geometry ("500x500") btn = Botón (ventana, texto = "clik", comando = Clik) ​​ btn.grid (columna = 1, fila = 1)
window.mainloop () 

![image](https://user-images.githubusercontent.com/79875930/112527523-c4a20600-8d68-11eb-849d-0a4bc8cc72d4.png)
