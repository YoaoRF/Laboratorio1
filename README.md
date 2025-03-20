void main() {
  List<int> numeros = [1, 2, 3, 40, 15, 6, 7, 8, 9, 10];

  int suma = 0;
  int mayor = numeros[0];
  int menor = numeros[0];

  for (int num in numeros) {
    suma += num;
    if (num > mayor) mayor = num;
    if (num < menor) menor = num;
  }

  double promedio = suma / numeros.length;

  print("Lista de números: $numeros");
  print("Suma: $suma");
  print("Mayor: $mayor");
  print("Menor: $menor");
  print("Promedio: ${promedio}");
}
