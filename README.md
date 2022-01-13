# e-x-yes
float fact(float num1) {
    float f = 1;
      for (float c = 1; c <= num1; c++) {
        f = f * c;

        }
        return f;

}

int main() {
  int n;
  float x;
  printf("Skriv dit n: \n");
  scanf("%d", &n);
  printf("Skriv dit x: \n");
  scanf("%f", &x);

  float result;
  for (float i = 0; i < n; i++) {
    result += (pow(x, i)/fact(i));

  }
  printf("%f \n", result);
  return 0;
}
