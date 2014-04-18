// Esta es la fecha a programar la alarma
var myDate  = new Date("May 15, 2012 16:20:00");

// Esta es la información a pasar a la alarma
var data    = {
  foo: "bar"
}

// La cadena "ignoreTimezone" es lo que hace a la alarma ignorar esto
var request = navigator.mozAlarms.add(myDate, "ignoreTimezone", data);

request.onsuccess = function () {
  console.log("La alarma ha sido programada");
};

request.onerror = function () { 
  console.log("Ha ocurrido un error: " + this.error.name);
};
