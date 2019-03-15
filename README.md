# cypherEX
#### ABSTRACTION BY TIME AND SIZE OF A WORD

<hr>

<div align="center" style="text-align:center"><img src ="https://github.com/Warkanlock/cypherEX/blob/master/logo_cypherX.png" /></div>

<h4>The proposed process develops an information encryption method that uses a decoy key generation algorithm to then make a relationship with the real information input in relational databases using decoy tables. Ways have been found to be able to reference real information by means of decoys allowing the ignorance of the original information in a data support entity, achieving only the possibility of accessing the true data through a main key.</h4>

For more reference about this work, you can go download the paper directly from ResearchGate:
[Link to paper](https://www.researchgate.net/publication/328615812_CIFRADO_DE_INFORMACION_MEDIANTE_GENERACION_DE_CLAVES_SENUELOS_TEMPORALES?_sg=Binv_1OHXn91ChCfhENIYD3qpBLk9KZNl2uF38o3DDNLt04Byl50-EsST7_ljvD7XA4DS2d_qPHPwgxMcvp0vHL-lpJleyEM2xVrFyQb.Ipw0Y1_20TDApNSpcOcD2Ry-Af5gcSD0MxpAlCAbIdyjXYi1-LaD7PYSVbegSqGXgx_j4iP2IB-4_LyaC9W1Qg)
<hr>

# Use case and examples

## IN ENGLISH
 An INPUT DATA is entered and the program stores that data in a record with the dependent identification.
 of the code generated by the same INPUT DATA. The same is generated by temporal and spatial issues (word space), then that unique SEED is generated and with it identifies an INPUT DATA. 
 Then,
 The time at which the transaction is recorded is stored in the database,
 With the same we can calculate the value of the SEED for thus through the time of creation of the account 
 and the code generated by the creator of unique transaction codes, 
 we look for the initial entry code (previously saved under the identification generated by the code from step 1).  
 In this way we can obtain INPUT DATA without the need of having the data itself, being able to be sencible information, etc.

#### ENCODE 
 ***INPUT DATA:*** Binary Array </br>
 ***INTERMEDIATE:*** Binary array is stored under the univocal code as main identifier </br>
 ***OUTPUT DATA:*** Univocal code, Creation time </br>
 
 #### DECODE 
 
 ***INPUT DATA:*** Univocal code, creation time </br>
 ***INTERMEDIATE:*** Binary Array identified under the univocal code </br>
 ***OUTPUT DATA:*** Binary Array </br>
 
 
 >Let's suppose a box without importance of order, the same identified under univocal codes,
 only possible to open under the output key generated under an algorithm, that algorithm would be this generator,
 it would only take a univocal code generated and the creation time to obtain the initial position. 
 

 #### Example: 

 ***ENTERED***: "THIS PDF is encrypted" </br>
 ***OUTPUT***: CC@C=@D?ECABB@D<AC<@B?@AC </br>
 
 <h4>To then search for the original text in the database (which was previously saved in the OUTPUT position (i.e., the SEED)) 
is positioned at the base and the SEED is generated with respect to time, and then compared if the code we are looking for is the same as the one entered.
 
As a conclusion it could be said that to obtain the initial text, it is necessary a physical support of the data, with the advantage that we would not have direct reference to the content, this is an abstract identification of information where sencible information could be hidden without the need to assign it to proper names or encrypted by Hash, in this case there would only be a code, which under comparison (with the code that we had, for example in a digital conversation) and with the essential requirement of the time of creation, the sencible information could be obtained.</h4>.

 <b> POSSIBLE UTILITIES: </b> Sensitive economic transactions, Blockchain, Cryptography, Abstraction of information, Optimization of deliveries, Long distance trips, Education, Encryption of passwords (without passwords).
 
>It should be clarified that this is not A CONCEPT OF ENCRYPTED as such, since it is IMPOSSIBLE to obtain with certainty the original word, since only the length and weight of the word is used and not the content itself, that is why it is useful to abstract things.
 
<hr> 

## IN SPANISH
 Se ingresa un DATO DE ENTRADA y el programa almacena ese dato en un registro con la identificación dependiente
 del codigo generado mediante el mismo DATO DE ENTRADA. El mismo es generado por cuestiones temporales y espaciales(espacio de la palabra), entonces se genera ese SEED unico y con el mismo identifica un DATO ENTRADA. 
 Luego,
 Se almacena en la base de datos el tiempo en el que se registro la transacción,
 Con la misma podemos calcular el valor del SEED para así mediante el tiempo de creación de la cuenta 
 y el codigo generado por el creador de codigos univocos de transacciónes, 
 buscamos el codigo de ingreso inicial (previamente guardado bajo la identificación generada por el codigo del paso 1).  
 Asi podemos obtener DATO DE ENTRADA sin necesidad de tener el dato en sí, pudiendo ser información sensible, etc.

#### ENCODE 
 ***DATOS DE ENTRADA:*** Array binario </br>
 ***INTERMEDIO:*** Array binario es almacenado bajo el codigo univoco como identificador principal </br>
 ***DATOS DE SALIDA:*** Codigo univoco, Tiempo de creación </br>
 
 #### DECODE 
 
 ***DATOS DE ENTRADA:*** Codigo univoco, tiempo de creación </br>
 ***INTERMEDIO:*** Array Binario identificado bajo el codigo univoco </br>
 ***DATO DE SALIDA:*** Array binario </br>
 
 
 >Supongamos un casillero sin importancia de orden, los mismos identificados bajo codigos univocos,
 solo posibles de abrir bajo la clave de salida generada bajo un algoritmo, ese algoritmo sería este generador,
 se necesitaria solamente un codigo univoco generado y el tiempo de creación para obtener la posición inicial. 
 

 #### Ejemplo: 
 
 <h4>Para buscar luego el texto original en la base (que fue previamente guardado en la posición de SALIDA (o sea, el SEED)) 
se posiciona en la base y se genera la SEED con respecto al tiempo, y luego se compara si el codigo que nosotros estamos buscando es igual al ingresado.
 
Como conclusión se podría decir que para la obtención del texto inicial, es necesario un soporte fisico de los datos, con la ventaja de que no tendríamos referencia directa al contenido,esto es una identificación abstracta de información donde se podría ocultar información sencible sin necesidad de asignarla a nombres propios o encriptados por Hash, en este caso solo se tendría un codigo, el cual bajo comparación (con el codigo que dispondriamos, por ejemplo en una conversación digital) y con el requisito escencial del tiempo de creación, se podría obtener la información sencible.</h4>

 <b>UTILIDADES POSIBLES: </b> Transacciónes sencibles economicas, Blockchain, Criptografía, Abstracción de información, Optimización de entregas, Viajes de largas distancias, Educación, Encriptado de contraseñas (sin contraseñas).
 
>Cabe aclarar que esto no es UN CONCEPTO DE ENCRIPTADO como tal, ya que es IMPOSIBLE obtener con certeza la palabra original, dado que solo se utiliza la longitud y peso de la palabra y no el contenido en sí, es por eso que es util para abstraer cosas.
 
<hr> 

#### Want a pull request?
Send me an email nanobrasca96@gmail.com or try to push it into the repo! 

