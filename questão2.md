#include <stdio.h>
    
  int main(void)
  {
  int a, b, c, aa, bb;
  printf("Digite um valor positivo: ");
  scanf("%d", &a);
  printf("Digite um valor negativo: ");
  scanf("%d", &b);

  aa = a + a;
  bb = b + b;
  c = a * b;
  
  printf("o dobro do primeiro valor: %d\n", aa);
  printf("o dobro do segundo valor: %d\n", bb);
  printf("multiplicação dos valores: %d\n", c);
  
  if (c > 1)
  {
  printf("valor positivo");
  }
  else
  {
  printf("valor negativo");
  }
  return 0;
    }
