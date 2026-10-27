# abierto-cerrado
Se utiliza una jerarquia de clases basada en herencia y polimorfismo.
La clase Producto funciona como la clase base general.
Las clases Fisico y Digital son subclases que heredan de Producto y definen su propio comportamiento.
Si se necesita agregar un nuevo tipo de producto en el futuro, como un servicio o suscripcion, solo se crea una clase nueva que herede de Producto sin necesidad de modificar ni arriesgar el codigo de las clases que ya existen.
