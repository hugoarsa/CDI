# Codificación Aritmética Entera

Este proyecto implementa la codificación y decodificación aritmética entera para una secuencia de genoma con alfabeto {'A', 'C', 'G', 'T'}. Incluye funcionalidad para comprimir y escribirlo en un archivo, así como para descomprimir un archivo y recuperar el mensaje original.

## Requisitos para Compilar

Para compilar esta aplicación, necesitas tener instalado:

- Un compilador de C++ compatible con C++11 o superior (como g++, clang++)

## Instrucciones para Compilar y Ejecutar

### Usando `g++`

1. **Compilar el programa:**

   ```bash
   g++ -O2 compress.src -o compress
   ```

2. **Ejecutar el programa:**

   - Para **comprimir** un archivo:
     
     ```bash
     ./compress.cdi -c <path>
     ```

   - Para **descomprimir** un archivo:
     
     ```bash
     ./compress.cdi -d <path>
     ```

## Ejemplos de Uso

### Compresión

Para comprimir un archivo de texto en el path `./DNACorpus/DrMe`:

```bash
./compress.cdi -c ./DNACorpus/DrMe
```

Esto generará un archivo comprimido en el path `./DNACorpus/DrMe.cps`.

### Descompresión

Para descomprimir un archivo en el path `./DNACorpus/DrMe.cps`:

```bash
./compress.cdi -d ./DNACorpus/DrMe.cps
```

Esto generará un archivo llamado `decompressed.out` con el contenido original.

## Notas

- Asegúrate de que los archivos de entrada existen y tienen los permisos adecuados antes de ejecutar el programa.