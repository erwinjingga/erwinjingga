#include <stdio.h>
int main(){
    printf("Program C Untuk Menghitung Volume Tabung\n");
    printf("----------------------------------------\n");
  
  const float PI = 3.14159; // define constant pi = 3.14
  float v, r, t; // init variable
  
  printf("Masukkan jari-jari dari tabung \t: ");
  scanf("%f", &r);
  printf("Masukkan tinggi dari tabung \t: ");
  scanf("%f", &t);
  v = PI * r * r * t; // rumus volume tabung
  printf("----------------------------------------\n");
  printf("Hasil perhitungan volume tabung adalah %.2f", v);
  printf("\n\n\n");
  return 0;
}
