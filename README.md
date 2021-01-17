# Proyecto-Final
Realizar un rol de pagos
#include <stdio.h>
#include <stdlib.h>
#include <windows.h>
#define a 850

/* run this program using the console pauser or add your own getch, system("pause") or input loop */
typedef struct Encabezado{
	char nombreEmpresa [20];
	char mes [10];
	int year;
}Encabezado; 
typedef struct Datos{
	char nombreEmpleado [30];
	char apellidoEmpleado [30];
	char cedula [11];
	char profesion [15];
	int horasLaboradas;
}Datos;
typedef struct Ingresos{
	float sueldo;
	int diasLaborados;
	float horasExtra;
	float totalIngresos;
}Ingresos;
 typedef struct Egresos{
 	float anticipioSueldo;
 	float prestamosIESS;
 	float impuestoRenta;
 	float IESS;
 	float totalEgresos;
 }Egresos;
