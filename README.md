#NOMBRE: MARIA MEDINA AMADOR
#CARRERA: INFORMATICA
#MATERIA DESARR. DE APP WEB
#PRACTICA 2.2

fecha=input("Fecha (formato 'dia, DD/MM'); ")
fecha=fecha.lower()
diasemana=fecha [0:fecha.find(',') ]
dianro=int(fecha[fecha.find(',')+1:fecha.find('/') ])
mesnro=int(fecha[fecha.find('/')+1:])
if dianro>31 or mesnro<12:
    print("Fecha incorrecta")
else:
    if diasemana in "lunes,martes,miercoles":
        respuesta=input("¿se tomaron examenes? S/N: ")
        if respuesta =="S" or respuesta=="S":
            aprobados= int(input("cantidad de aprobados: "))
            reprobados== int(input("cantidad de reprobados: "))
            print("porcentaje de aprobados ", (aprobados*100)/(aprobados+reprobados) ,"%")
    elif diasemana == "jueves":
        asistencia=int("porcentaje de asistencia: ")
        if asistencia>50:
            print("Asistio la mayoria")
        else:
            print ("No asistio la mayoria")

    elif diasemana == "viernes":
        if dianro==1 and (mesnro==1 or mesnro==7):
            print("comienzo de nuevo ciclo")
            alumnos=int(input("cantidad de alumnos"))
            arancel=float(input("Arancel: $"))
            print("ingreso total: $", almunos*arancel1)

    else:
        print("Fecha incorrecta")

print("Fin del programa")

