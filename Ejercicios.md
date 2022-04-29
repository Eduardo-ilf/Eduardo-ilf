/* A) 3 chicos de 23 años perfectamente normales entran a una heladeria a comprar, pero hay un problema= los precios no estab al lado de cada estante con su respectivo helado. 
Ellos quieren comprar el helado mas caro que puedan con el dinero que tienen.

Roberto tiene 1.5 usd 
Pedro tiene 1.7 usd 
Cofla tiene 3 usd 

Los precios de los helados son los siguientes= 
palito de helado de agua = 0.6 usd
palito de helado de crema = 1 usd
bombon helado de marca heladix = 1.6 usd
bombon de helado de marca helardo = 1.8 usd
potecito de helado con confites = 2.9 usd
pote de 1/4 kg = 2.9 usd

Crear soluciones=
- pedirles que ingresen el monto que tienen y mostrarles el helado mas caro que pueda comprar
- si hay 2 o mas con el mismo precio, mostra ambos
- Cofla quiere saber cuanto es el vuelto */

dinerocofla = prompt("cuanto dinero tienes Cofla?")
dineroroberto = prompt("cuanto dinero tienes Roberto?")
dineropedro = prompt("cuanto dinero tienes Pedro?")

if (dinerocofla >= 0.6 && dinerocofla < 1){
    alert ("compra el helado de agua")
}
else if (dinerocofla >= 1 && dinerocofla <1.6){
alert("compra el helado de crema")

}
else if (dinerocofla >= 1.6 && dinerocofla < 1.7) {
    alert("compra el helado de heladix")

}
else if (dinerocofla >= 1.7 && dinerocofla < 1.8) {
    alert("compra el helado de helardo")

}
else if (dinerocofla >= 1.8 && dinerocofla < 2.9) {
    alert("compra el helado con confites o pote de 1/4kg")

}
else (dinerocofla >= 2.9)
 {
    alert("lo siento pobre de mierda, no te alcanza para un helado")
}
