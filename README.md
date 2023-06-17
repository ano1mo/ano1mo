- 👋 Hi, I’m @ano1mo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ano1mo/ano1mo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import gi
gi.require_version("Gtk", "3.0")
from gi.repository import Gtk
 class MyWindow(Gtk.Window):
    def __init__(self):
        super().__init__(title="GARDS GAME")
        self.set_default_size(300, 300)


    whiledone:
    for event in gi.event.get():
        if event.type == gi.QUIT:
            done = True      
    box = Gtk_box_new(orientacion_vertical, 0 );        
    button = Gtk.Button(label="Mostrar Nombres")
   button.connect("clicked", self.on_button_clicked)
   box.pack_start(button, True, True, 0)
   listbox = Gtk.ListBox()
   box.pack_start(listbox, True, True, 0)
   for nombre in nombres:
       row = Gtk.ListBoxRow()
       label = Gtk.Label(label=nombre)
       row.add(label)
       listbox.add(row)


class mainwindow(Gtk.window):
    def__unit__(self, tittle = "button clicked 2.0")
    self.button = Gtk.button(label ="play now")
    self.button.conect("clicked", self.button_clicked)
    self.add(self.button)
    def button_clicked(self,witget)
        print("gametime")
    def on_button_clicked(self, button):
       # Aquí se añadirá el código para mostrar los nombres seleccionados
    pass

def guardar_puntajes(widget):
    puntajes = []  # Ejemplo de lista de puntajes
    puntajes_ordenados = sorted(puntajes, reverse=True)
    print(puntajes_ordenados)

button.connect("clicked", guardar_puntajes)

button.start = gtk.button("star")
start_button.connect("clicked", self.start_game)
self, add(start_button)

def start_game(self, widget):
        # Aquí puedes agregar la lógica para iniciar el juego
        print("El juego ha comenzado")

class Carta:
       def __init__(self, valor):
           self.valor = valor
           self.boca_arriba = False
           
       def voltear(self):
           self.boca_arriba = not self.boca_arriba
           
       def comparar(self, otra_carta):
           return self.valor == otra_carta.valor
class Tablero:
       def __init__(self, pares):
           self.cartas = []
           for i in range(pares):
               self.cartas.append(Carta(i))
               self.cartas.append(Carta(i))
           random.shuffle(self.cartas)
           
       def voltear_carta(self, posicion):
           self.cartas[posicion].voltear()
           
       def comparar_cartas(self, posicion1, posicion2):
           return self.cartas[posicion1].comparar(self.cartas[posicion2])
class Juego:
       def __init__(self, pares):
           self.tablero = Tablero(pares)
           
           self.window = gtk.Window(gtk.WINDOW_TOPLEVEL)
           self.window.connect("destroy", lambda x: gtk.main_quit())
           
           self.table = gtk.Table(rows=pares, columns=2)
           for i in range(pares):
               button = gtk.Button()
               button.connect("clicked", self.on_card_clicked, i)
               self.table.attach(button, i % 2, (i % 2) + 1, i // 2, (i // 2) + 1)
           
           self.window.add(self.table)
           self.window.show_all()
           
       def on_card_clicked(self, button, posicion):
           self.tablero.voltear_carta(posicion)

win = MyWindow()
win.connect("destroy", Gtk.main_quit)
win.show_all()
Gtk.main()
