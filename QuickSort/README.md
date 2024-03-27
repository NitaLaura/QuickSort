# QuickSort

- O QuickSort é um algoritmo de ordenação muito eficiente e amplamente usado.
- Funciona com o princípio de dividir para conquistar.

## É criado com 3 passos básicos:

- Escolher um elemento do array para ser o pivô (nessa implementação vou sempre escolher o último elemento do subarray como pivô).
- Particionar: Reorganizar o array de forma que todos os elementos com valores menores que o pivô venham antes dele, e todos os elementos com valores maiores venham após ele. Após a partição, o pivô estará em sua posição final.
- Recursivamente ordenar os subarrays de elementos menores e maiores.