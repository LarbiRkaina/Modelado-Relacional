En la práctica de modelado relacional se ha tenido en cuenta los siguientes aspectos:

1- La tabla **curso**  tiene una relación de muchos a muchos con la tabla **video**. Para ello se ha creado una tabla intermedia que se llama **curso/video**. Esta última tabla tiene una relación de muchos a uno con las tablas **curso** y **video**.

2- La tabla **curso** también tiene una relación de muchos a muchos con la tabla **artículo** y para ello como en el caso de **curso/video** hemos creado una tabla intermedia llamada **curso/artículo**. Esta tabla tiene una relación de muchos a uno con las tablas **curso** y **artículo**.

3- La tabla **video** tiene una relación de uno a uno con la tabla **autor**. Es decir un video puede tener un autor y un autor puede tener un video.
	
4- La tabla **video** tiene otra relación, esta vez de uno a muchos con la tabla **temática**. Es decir un video puede tener muchas temáticas y muchas temáticas pueden estar en un video.

5- La tabla **artículo** tiene una relación de muchos a muchos con la tabla **autor**. Para ello se ha creado una tabla intermedia que se llama **artículo/autor** la cual tiene una relación de muchos a uno con las tablas **artículo** y **autor**.


![Diagrama modelado](https://user-images.githubusercontent.com/107713900/215258827-164760a7-f642-4d10-b862-2f55dc7e3692.png)
