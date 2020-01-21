#include<stdio.h>
#include<stdlib.h>



typedef struct robot
{info*zone0;
 struct robot*suivant}*robot;
 

int Avance(robot*info, int z1 , int z2){
	int D, i , j ; 
	int zone0=0;
	D=max(z1,z2);
	
	for(i=0;i<D;i++)
	{
		robot->suivant=z1+i;
		
	}
	return robot->suivant
    	
}		
	
int recule(Robot*info , int z2)
{int zone0;
 while (robot->suivant!=zone0)
    robot->suivant=z2-1 ;
  return zone0
}

void Droite(robot*info)
{ int D,zone0,zone1;
  D=max(zone0,zone1);
  robot->suivant= (robot->suivant +1)%D;
}


void gauche(robot*info)
{ int D,zone0,zone1;
  D=max(zone0,zone1);
  robot->suivant= (robot->suivant -1)%D;
}
	
void verifier(robot*info)
{ int cercle , other ; //other : une autre forme
  if(robot=other)
   other=other;
  elseif(robot=cercle)
   gauche(robot*info);
 }
 
