<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio práctica 1_Programación 1</title>
</head>
<body>
    
    <script>

//Declaro las variables de categoría de sueldo

    const categoria1 = 1000;
    const categoria2 = 2000;
    const categoria3 = 3000;

// Declaro las variables de subcategorías

    const subCategoriaA = 1.5;
    const subCategoriaB = 2;
    const subCategoriaC = 2.5; 

//Solicito que el usuario ingrese los 2 datos que necesito para hacer el cálculo (categoría de sueldo y subcategoria)

 let categoriaSueldo =  parseInt(prompt("Por favor, ingrese su Categoría de sueldo (1, 2 o 3), según corresponda):"));

    if ( categoriaSueldo === 1){
        categoriaSueldo = categoria1
    }

    else if (categoriaSueldo ===2) {
        categoriaSueldo = categoria2
    }

    else if (categoriaSueldo ===3) {
        categoriaSueldo = categoria3
    }

console.log ("La categoria es:" + categoriaSueldo); 


 let subcategoriaSueldo = prompt("Ahora, ingrese su Subcategoría de sueldo (A, B o C), según corresponda):");

    if ( subcategoriaSueldo == "A"){
        subcategoriaSueldo = subCategoriaA
    }

    else if (subcategoriaSueldo =="B") {
        subcategoriaSueldo = subCategoriaB
    }

    else if (subcategoriaSueldo =="C") {
        subcategoriaSueldo = subCategoriaC
    }

console.log ("La subcategoria es:" + subcategoriaSueldo); 


 // Calculo el sueldo del empleado 

 let sueldoEmpleado = (categoriaSueldo * subcategoriaSueldo);

 console.log ("El SUELDO del empleado es de:" + sueldoEmpleado); 

 

 //Valido el sueldo y determino el rango correspondiente

 let rangoSueldo;

    if (sueldoEmpleado >= 1500 && sueldoEmpleado <= 3000) {

    rangoSueldo = "INICIAL";
    }


    else if (sueldoEmpleado > 3000 && sueldoEmpleado <= 4000 ) {

    rangoSueldo = "INTERMEDIO";
    }

    else if ( sueldoEmpleado > 4000) {
    
    rangoSueldo = "AVANZADO";    
    }

console.log ("El rango del sueldo es: " + rangoSueldo);



// IMPRIMO INFORMACIÓN EN LA PANTALLA

document.write ("<h1>Datos del empleado</h1><ul>")
document.write ("<li>El sueldo del empleado es: " + sueldoEmpleado +" USD </li>");
document.write ("<li>El rango de sueldo del empleado es: " + rangoSueldo +"</li>")



    </script>    

</body>
</html>
