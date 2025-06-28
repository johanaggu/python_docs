# python docs

<!-- ## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files. -->

## Lista de metodos utiles con strings
- ***upper()*** : convierte todos los caracteres a mayúsculas;
- ***lower()*** : convierte todos los caracteres a minúsculas;
- ***replace(from, to)*** reemplaza partes de un string por otro string;
- ***strip()*** elimina los espacios al principio y al final del string.

### ***func*** (*str*) **islower**() *bool*
Returns boolean and indicate if a string contains only lowercase letters
```py
hello = 'hello'
hello.islower() # Return false
```
### ***func*** (*str*) **isdigit**() *bool*
Returns boolean and indicates if a string contains only numbers. 
```py
num = '5642'
num.isdigit() # return True 
```

### ***func*** (*str*) **isalpha()** *bool*
Return `True`

### Lista de metodos utiles con listas
> my_list = [1, 2, 3]

- ***my_list.append(4)*** : [1,2,3, 4]
    - agrega un elemento al final
- ***my_list.extend([4, 5, 6])*** : [1, 2, 3, 4, 5, 6]
    - gregar varios elementos
- ***my_list.insert(1, [1.2, 1.5])*** : [1, [1.2, 1.5], 2, 3]
    - inserta un elemento en un indice especifico
- ***my_list.remove(3)*** : [1,2]
    - elimina la primera aparición de un valor específico
- ***my_list.pop(1)***:[1,3]
    -  elimina el elemento en el índice *1* y si no especifica ningún argumento, este método eliminará el último elemento de la lista. 

