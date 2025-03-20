//            Ejercicio de evaluación de condiciones combinadas

//       Crea un programa que haga dos validaciones conjuntas para verificar si aplica o no para un descuento especial de la siguiente manera, que se imprima en consola en c#:



//Pregunte al usuario si:  Tiene una cuenta premium(Sí o No)

//                                              Ha realizado más de 5 compras(Sí o No)



//Reglas:



//            Utiliza el operador OR

//Declara dos variables de tipo bool(tienePremium, haRealizadoCompras) e iguálalas a las variables de respuesta

//Utiliza la estructura IF

//La salida por pantalla debe indicar lo siguiente:



//            *Si se cumple al menos una de las condiciones, imprimir: "Usted es elegible para un descuento especial."



//            * Si no se cumple ninguna de las condiciones, imprimir: "Lo siento, no es elegible para el descuento."





            bool TienePrimium = true;
            bool HaRealizadoCompras = true;
            string valor;

            Console.WriteLine("BIENVENIDO A TIENDAS EL POLLON ");
            Console.WriteLine();

            Console.WriteLine("Tiene una cuenta premium(Sí o No)");
            valor = Console.ReadLine();
            TienePrimium = Convert.ToBoolean(valor);
            Console.WriteLine();

            Console.WriteLine("Ha realizado más de 5 compras(Sí o No)");
            valor = Console.ReadLine();
            TienePrimium = Convert.ToBoolean(valor);
            Console.WriteLine();


            if (TienePrimium != true || HaRealizadoCompras != true)
            {
                Console.WriteLine("Lo siento, no es elegible para el descuento.");

            }
            else
            {
                Console.WriteLine("Usted es elegible para un descuento especial.");
            }
            Console.ReadKey();
