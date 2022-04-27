import java.awt.*;
class Mypadd extends Frame
{
MenuBar mb;
Menu file,edit,format,view,help;
MenuItem fa,fb,fc,fd,ea,eb,ec,ed,ffa,ffb,va,vb,ha,hb,hc;
 Mypadd()
{
setTitle("Notepad");
mb=new MenuBar();
file=new Menu("File");
edit=new Menu("Edit");
format=new Menu("Format");
view=new Menu("View");
help=new Menu("Help");
setMenuBar(mb);
mb.add(file);
mb.add(edit);
mb.add(format);
mb.add(view);
mb.add(help);
fa=new MenuItem("new");
fb=new MenuItem("open");
fc=new MenuItem("save");
fd=new MenuItem("print");
file.add(fa);
file.add(fb);
file.add(fc);
file.add(fd);
ea=new MenuItem("cut");
eb=new MenuItem("copy");
ec=new MenuItem("paste");
ed=new MenuItem("select all");
edit.add(ea);
edit.add(eb);
edit.add(ec);
edit.add(ed);
ffa=new MenuItem("Word wrap");
ffb=new MenuItem("font");
format.add(ffa);
format.add(ffb);
va=new MenuItem("Zoom");
vb=new MenuItem("status bar");
view.add(va);
view.add(vb);
ha=new MenuItem("new");
hb=new MenuItem("open");
hc=new MenuItem("save");
help.add(ha);
help.add(hb);
help.add(hc);
pack();
}
}
class create
{
public static void main(String args[])
{
 Mypadd m=new  Mypadd();
m.setSize(400,400);
m.show();
}
}
