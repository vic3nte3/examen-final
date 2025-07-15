# examen-final
productos=[talla , , ram , , disco , gb de DD , procesador , video ]

marca=["hp, dell, acer, asus"]

print("productos disponibles:")

print ("hp, 15.6, 8, 256 ,i5,nvidia gtx 1050")
print ( "dell , 15,6,8, 512 ,i7 amd")
print ("acer , 15,6,16, 1 tb , i5, nvidia")
print ( "asus , 15,6,8, 256 . i5, nvida")

stock=["8475HD(387990,10), fgdxFHD(664990,21) ,GF75HD(74999,0),uwu131hd(349990,1) fs1230hd(249990,0)"]

#____MENU PRINCIPAL____

while True:
    print("\n--- Menú de Opciones ---")
    print("Seleccione una opción:")
    print("1. Buscar marca")
    print("2. Buscar por precio")
    print("3. Listado de productos")
    print("4. Salir")

    opcion = input("Ingrese el número de la opción: ")

    if opcion == "1":
        marca = input("Ingrese la marca a buscar: ")
        
        print(f"Buscando productos de la marca {marca}...")

    elif opcion == "2":
        precio = input("Ingrese el rango de precio (ejemplo: 100000-500000): ")
       
        print(f"Buscando productos en el rango de precio {precio}...")

    elif opcion == "3":

        print("Listando todos los productos disponibles...")

    elif opcion == "4":
        print("Saliendo del programa...")
        break

    else:
        print("Opción no válida, intente nuevamente.")

        def lista_de_productos():

            print("productos disponibles:")
            for producto in productos:
                print(producto)
                lista_de_productos()
            print("fin de la lista de productos")
            
            print¨(" gracias por usar nuestro sitio web")

   print ("programa finalizado")

