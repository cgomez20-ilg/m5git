## Java (llenguatge de programació)

El **Java** és un [llenguatge de programació](https://ca.wikipedia.org/wiki/Llenguatge_de_programaci%C3%B3) dissenyat el 1990 per James Gosling amb altres companys de Sun Microsystems a partir del llenguatge C. Des del seu naixement fou pensat com un llenguatge [**orientat a objectes**.](https://ca.wikipedia.org/wiki/Programaci%C3%B3_orientada_a_objectes) Entre el 13 de novembre de 2006 i el maig del 2007 Sun va alliberar parts de Java com a programari lliure de codi obert amb llicència GPL. És un dels llenguatges de programació més utilitzats, i s'utilitza tant per aplicacions web com per aplicacions d'escriptori.

El Java és un **llenguatge compilat** amb una màquina virtual d'intermediari i, per tant, pot semblar lent en comparació amb altres llenguatges, però ofereix un índex de re-utilització de codi molt elevat, sent possible trobar moltes llibreries lliures de _Java_. És un llenguatge flexible i potent tot i la facilitat amb la qual es programa i dels resultats que ofereix. Un dels trets que el caracteritza i que el fa una eina molt valorada a l'hora de desenvolupar aplicacions distribuïdes, és el fet que és un llenguatge multi-plataforma.

Generalment els programes de Java es compilen en un [_bytecode_](https://ca.wikipedia.org/wiki/Bytecode_(Java)) (fitxer .class) que pot córrer en una Màquina Virtual Java. Sun Microsystems disposa de tres implementacions diferents de _Java_: J2SE per a aplicacions d'escriptori; J2EE per a aplicacions distribuïdes i J2ME per a plataformes amb recursos més reduïts com ara mòbils o PDAs. Per a cada una de les tres implementacions és possible descarregar el [_JRE_][linkJRE] (_entorn d'execució Java_) per a executar [aplicacions][linkProgramari] o el SDK (_Eines per al desenvolupament d'aplicacions_) per a programar [aplicacions][linkProgramari] en _Java_, aquest últim també inclou el [_JRE_][linkJRE].

Un [**programa**][linkProgramari] desenvolupat amb Java no necessita compilar-se de nou per a poder executar-se en qualsevol de les plataformes que disposi d'una versió instal·lada de [_JRE_][linkJRE] prou actualitzada per al [programa][linkProgramari].

[linkProgramari]: https://ca.wikipedia.org/wiki/Programari
[linkJRE]: https://ca.wikipedia.org/wiki/Java_Runtime_Environment
### Contingut
* Característiques de Java
* Tipus de Dades
 * Tipus de dada primitius o variables primitives
   * BOOLEÀ (_boolean_)
   * CARÀCTER (_char_)
   * NUMÈRICS ENTERS (_byte, short, int, long_) i NUMERICS REALS (_fload, double_)
* Altres Característiques
* Sintaxi
 * Hola Món
   * Aplicacions autònomes
* Aplicacions i miniaplicacions
* Limitacions de seguretat en les miniaplicacions
* Eines de desenvolupament JAVA2
* Passos per crear un programa amb Java
* Com desenvolupar aplicacions: Entorns (_IDE_)
* Altres projectes i eines relacionades
* Programa d'exemple
* Referències
* Vegeu també
* Enllaços externs
 

#### Característiques de Java

* **Senzill**: Java s'ha creat perquè sigui un llenguatge senzill amb una sintaxi elegant. Únicament consta de tres tipus de dades primàries, eliminant els punters i l'herència múltiple
* [**Orientat a objectes**](https://ca.wikipedia.org/wiki/Programaci%C3%B3_orientada_a_objectes): Java segueix els paradigmes de la programació orientada a objectes, ja que la programació amb Java se centralitza en la manipulació, creació i construcció d'objectes.
* **Distribuït**: Java permet la construcció d'aplicacions distribuïdes per mitjà d'una col·lecció específica de classes.
* **Interpretat**: Es necessita un intèrpret per executar els programes de Java, això alenteix als programes però els hi dona flexibilitat.
* **Robust**: Java és un llenguatge robust i fiable, s'ha escrit pensant a poder verificar errors i està molt tipificat.
* **Segur**: Java té pocs problemes de seguretat, característica molt important en les aplicacions distribuïdes d'Internet.
* **[Arquitectura](https://ca.wikipedia.org/wiki/Arquitectura) neutral**: Java és independent de la plataforma final on s'executarà el programa.
* **Portable**: Java és un llenguatge d'alt nivell i de plataforma independent, això li dona portabilitat.
* **Alt rendiment**: Els compiladors Java han anat millorant les seves prestacions. Els nous compiladors
coneguts com a JIT permeten un rendiment molt semblant als llenguatges convencionals compilats.
* **Concurrent**: Java permet l'execució de múltiples fils d'execució, o diverses tasques de forma simultània.
* **Dinàmic**: En temps d'execució, l'entorn Java es pot ampliar mitjançant enllaços a classes que poden estar localitzades en servidors remots o en xarxa.

##### **Hola Món**
> _Article principal_: [Hola món](https://ca.wikipedia.org/wiki/Hola_m%C3%B3n)

##### **Aplicacions autònomes**

```
// Hola.java
import java.io.IOException;
public class Hola {
    public static void main(String[] args)throws IOException {
        System.out.println("Hola, món!"); 
    }
}
```
