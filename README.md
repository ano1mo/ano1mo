- 👋 Hi, I’m @ano1mo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ano1mo/ano1mo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
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
    btnplayer = Gtk_button_new_with_label("Player")  
    Gtk_conteiner_add(GTK_CONTAINER(mainwindow), btnplayer)
   
    Gtk_box_pack_start(GTK_BOX(box) , btnplayer, False, False, 0);

    g_signal_conect(object(mainwindow),"destroy", 
                    callback(Gtk_main_quit),NULL)
    
    Gtk_widget_show_all(mainwindow)
    Gtk_main();
    from gi.repository import Gtk
Window = Gtk.window 
window.conect("delete event", Gtk.main_quit)
Window.show_all()
Gtk.main()

class mainwindow(Gtk.window):
    def__unit__(self, tittle = "button clicked 2.0")
    self.button = Gtk.button(label ="play now")
    self.button.conect("clicked", self.button_clicked)
    self.add(self.button)
    def button_clicked(self,witget)
        print("gametime")
 Gtk.window
Window = mainwindow()
    return 0
