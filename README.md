# Zomb-angel
echo "# Zomb-angel" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/far21cry/Zomb-angel.git
git push -u origin master
git remote add origin https://github.com/far21cry/Zomb-angel.git
git push -u origin master
https://github.com/far21cry/Zomb-angel.git

#include <iostream>
#include <string>
using namespace std;
int main () {
	bool continua=true;
	while (continua){
	string resp=" ";
	while (resp!="si" or resp!="s"){
	cout<<"bienvenido, por favor introdusca los siguentes datos"<<endl;
	string Nombre ;
	string Apellido ;
	cout<<"Nombre: ";cin>>Nombre ;cout<<"apellido: ";cin>>Apellido ;cout<<endl;
	cout<<"Muy bien, por favor proceda a ingresar las notas de "<<Nombre<<" "<<Apellido<<endl;
	cout<<"		"<<"Notas de evaluciones en ponderacion base a '20' "<<endl;
	double a=10/100 , b=20/100 , c=15/100 , d=15/100 , e=20/100 , f=20/100 ;
	cout<<" 10% : ";cin>>a;cout<<" 20% : ";cin>>b;cout<<" 15% : ";cin>>c;cout<<" 15% : ";cin>>d;cout<<" 20% : ";cin>>e;cout<<" 20% : ";cin>>f;cout<<endl;
	double re;
	cout<<a+b+c+d+e+f<<"% "<<endl;
	cout<<"muy bien ya esta completado la carga de notas, deasea realizar otra carga de notas, responda 'si(s)' o 'no(n)' "<<endl;
	cin>>resp;
		
		if (resp>="no")continua=false;	}
			}
	}
