Desafíos:

1.Pregunta al usuario qué día de la semana es. Si la respuesta es "Sábado" o "Domingo", muestra "¡Buen fin de semana!". De lo contrario, muestra "¡Buena semana!".

let diaDeLaSemana=promt("¿Que dia es?);

if (diaDeLaSemana === 'Sábado' || diaDeLaSemana === 'Domingo') 
{alert("¡Buen fin de semana!");

} else {
    alert("¡Buena semana!");}



2.Verifica si un número ingresado por el usuario es positivo o negativo. Muestra una alerta informativa.

let numero=promt("Ingrese un numero");

if (numero > 0) 
{alert("El numero es positivo");
} else if ( numero < 0 ) {
alert("El numero es negativo");
}
3.Crea un sistema de puntuación para un juego. Si la puntuación es mayor o igual a 100, muestra "¡Felicidades, has ganado!". En caso contrario, muestra "Intentalo nuevamente para ganar.".

let puntuacion=98
if (numero >= 100) {alert("¡Felicidades, has ganado!");
} else {alert("Intentalo nuevamente para ganar");}

4.Crea un mensaje que informe al usuario sobre el saldo de su cuenta, utilizando un template string para incluir el valor del saldo.

SaldoEnCuenta=500
alert(`Tu saldo en tu cuenta es ${SaldoEnCuenta}`);

5.Pide al usuario que ingrese su nombre mediante un prompt. Luego, muestra una alerta de bienvenida usando ese nombre.
let usuario=promt("Ingrese su nombre:")
alert(`Bienvenido ${usuario}`);
