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
gi.requiere_version("Gtk", "3.0")
from gi.repository import Gtk

class from(Gtk.window):
    def _unit_(self):
        super()._unit_(title="Juego") 
        self.self_default_size(300,300)
        self.set_border_width(40)
        clok = gi.time.clok()
        vb = Gtk.VBox(spacing=2)
        self.add 
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


 Gtk.window
Window = mainwindow()
return 0
