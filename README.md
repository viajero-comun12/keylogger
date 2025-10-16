instalar el keyboard con "pip install keyboard del requiremnts"

se importa el keyboard que registrara el ingreso de todo por teclado,
creamos la funcion encargada de guardar el ingreso por teclado con el parametro de event el cual guardara lo que este pasando en este momento
luego creamos el archivo donde se almacena lo que guardamos con keyboard mediante open("damos el nombre que le damos") ,("lo que se hace en el archivo, en este caso el a de append para que guarde lo que ya esta y no lo sobrescriba o borre) como archivo as file
luego guardamos lo que recivimos en el archivo con file.write(el evento.lo guardado (name))
asignamos que guardamos
keyboard.on_press (funcion de escribir el archivo)
pritn mensaje si queremos 
y como salimos
keyboard.wait(lo que queremos terminar)
