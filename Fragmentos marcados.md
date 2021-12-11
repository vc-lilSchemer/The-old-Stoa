## Agradecimientos
Me gustaría agradecer a Patricio Garrido, Paulina Serrano y al profesor Ernesto Priani, sin los cuales este trabajo no hubiera sido posible. A Paulina por darme varios 
ejemplos de cómo utilizar las marcas de TEI y darme algunas ideas de cómo marcar mis fragmentos. A Patricio por apoyarme en distintos pasos del marcado en TEI (desde la 
configuración del editor de texto hasta compartirme su proceso en la codificación de fragmentos). Y a Ernesto por apoyarme con distintos problemas que tuve para publicar 
mi página de Github, darme un visto bueno a mis criterios de marcado y darnos una gran flexibilidad en los tiempos de entrega que me apoyaron en distintas etapas del 
semestre. Sin embargo, cualquier error o deficiencia es exclusivamente mío.

Muchas gracias a todos. 

## Notas editoriales
Notas editoriales: hago una plena identificación entre providencia y lógos, palabra, razón, recta razón, y ley común. Al hacer esto, quizá esté perdiendo algo de riqueza 
semántica en los términos utilizados. Sin embargo, al tratarse de fragmentos éticos (y siendo el telos de la ética y de la vida la felicidad), darle el enfoque de estas 
palabras desde la providencia parece apropiado.

De igual manera, utilizo en el primer fragmento a “Dios” como descripción de la “providencia” y en el segundo como “concepto filosófico” debido a los distintos contextos
en los que ocurren: en el primer fragmento puede tratarse como una descripción ya que Tertuliano dice que el lógos es llamado también  [...] Dios; en el segundo se puede 
tratar como un concepto puesto que es el sujeto al que se le están atribuyendo propiedades (e.g. extenderse a través de las cosas podridas). 

Finalmente, la mayoría o todas de mis marcas <interp> relacionadas con la ética las utilicé para señalar descripciones de la felicidad (o de cómo llegar a ella). 
Esto se debe a que para la ética helenística (y en particular la estoica) [el objetivo era encontrar el “fin” de los humanos y, siguiendo a Aristóteles, mencionan 
que este es la eudaimonía](https://plato.stanford.edu/archives/spr2019/entries/stoicism/#Eth) (una palabra que toscamente se puede traducir por “felicidad”).

## Fragmentos marcados 
  
`<?xml version="1.0" encoding="UTF-8"?>`
`<?xml-model href="http://www.tei-c.org/release/xml/tei/custom/schema/relaxng/tei_lite.rng" type="application/xml" schematypens="http://relaxng.org/ns/structure/1.0"?>`
`<?xml-model href="http://www.tei-c.org/release/xml/tei/custom/schema/relaxng/tei_lite.rng" type="application/xml"
	schematypens="http://purl.oclc.org/dsdl/schematron"?>`
`<TEI xmlns="http://www.tei-c.org/ns/1.0">`
  
  
  `<teiHeader>`
      `<fileDesc>`
         `<titleStmt>`
            `<title>`Fragmentos de ética estoica (y algo más)`</title>`
						`<editor>`Víctor Andrés Campos Chávez`</editor>`
         `</titleStmt>`
         `<publicationStmt>`
            `<authority>`Víctor Andrés Campos Chávez`</authority>`
						`<pubPlace>`Ciudad de México`</pubPlace>`
						`<date when="2021">`2021`</date>`
         `</publicationStmt>`
         `<sourceDesc>`
            `<bibl>`
						 `<title>`Los estoicos antiguos`</title>`
						 `<respStmt>`
						  	`<name>`Ángel J. Cappelletti`</name>`
							  `<resp>`Translator`</resp>`
					 	 `</respStmt>`
						 `<publisher>`Gredos`</publisher>`
						 `<pubPlace>`Madrid`</pubPlace>`
						 `<date when="1996">`1996`</date>`
						 `<series>`Biblioteca clásica Gredos`</series>`, 230
						 `<idno type="ISBN">`84-249-1843-6`</idno>`
					`</bibl>`
         `</sourceDesc>`
      `</fileDesc>`
  `</teiHeader>`
  
  
  `<text>`
      `<body>`
         `<div1 n="1" type="section">` 
					 `<div2 n="1" type="fragment">`
					   255 TERTULIANO, Apologético 21 [S. V. F. I 160]
					   Entre vuestros sabios se reconoce también que el `<term type="concepto filosófico" xml:id="Providencia">`
					   lógos`</term>`, esto es, la `<term type="concepto filosófico" xml:id="Providencia">`palabra`</term>` y la
					   `<term type="concepto filosófico" xml:id="Providencia">`razón`</term>`, aparece como artífice del `<term
					   type="concepto filosófico" xml:id="Naturaleza">`conjunto universal`</term>`. A él, en efecto, lo presenta
					   `<name type=“person” subtype=“philosopher” xml:id=“Zenón_de_Citio”>`Zenón`</name>` como `<interp
					   type="descripciòn de la Providencia">`el creador`</interp>`, el que `<interp type="descripciòn de la
					   Providencia">`todo lo dispuso ordenadamente`</interp>`, y el mismo es llamado también `<interp
					   type="descripciòn de la Providencia">`destino`</interp>`, `<interp type="descripciòn de la Providencia">`
					   Dios`</interp>`, `<interp type="descripciòn de la Providencia">`espíritu de Júpiter`</interp>` y `<interp
					   type="descripciòn de la Providencia">`necesidad de todas las cosas`</interp>`.
				   `</div2>`
  
  
					 `<div2 n="2" type="fragment">`
					   253 SEXTO EMPÍRICO, Esbozos pirrónicos III 218 [S. V. F. I 159]
             Los estoicos [creen que `<term type="concepto filosófico" xml:id="Providencia">`Dios`</term>` es] un
					   `<interp type="descripciòn de la Providencia">`soplo`</interp>` que `<interp type="descripciòn de la
					   Providencia">`se extiende aun a través de las cosas podridas`</interp>`.
				   `</div2>`
  
  
           `<div2 n="3" type="fragment">`
						 262 DIÓGENES LAERCIO, VII 88 [S. V. F. I 162]
           	 ... la `<term type="concepto filosófico" xml:id="Providencia">`ley común`</term>`, que es la `<term
					 	 type="concepto filosófico" xml:id="Providencia">`recta razón`</term>`, al `<interp type="descripciòn
					   de la Providencia">`marchar a través de todas las cosas`</interp>` y `<interp type="descripciòn de la
					   Providencia">`ser idéntica a Zeus`</interp>`, `<interp type="descripciòn de la Providencia">`guía del
					   ordenamiento de los entes`</interp>`.
					 `</div2>`
  
  
				 `</div1>`
				 `<div1 n="2" type="section">` Sobre cómo vivir
					 `<div2 n="1" type="fragment">`
					   286 DIÓGENES LAERCIO, VII 87 [S. V. F. I 179]
             En torno a esto, `<name type=“person” subtype=“philosopher” xml:id=“Zenón_de_Citio”>`Zenón`</name>` fue
						 el primero que en [su obra] `<title xml:id="nat-hom-Zn-Ctio">`Sobre la `<term type="concepto filosófico">`
						 naturaleza`</term>` del hombre`</title>` dijo que fin es `<interp type="descripción de la felicidad">`
						 vivir de acuerdo con la `<term type="concepto filosófico" xml:id="Naturaleza">`naturaleza`</term>`, lo
						 cual es vivir según la `<term type="concepto filosófico">`virtud`</term>` `</interp>`. A ésta, en efecto,
						 nos lleva la `<term type="concepto filosófico" xml:id="Naturaleza">`naturaleza`</term>`.
					 `</div2>`
  
  
           `<div2 n="2" type="fragment">`
						 301 AGUSTÍN, Contra los académicos III 7, 16 [S. V. F. I 186]
             Proclama `<name type=“person” subtype=“philosopher” xml:id=“Zenón_de_Citio”>`Zenón`</name>` y `<name
						 type=“person” subtype=“philosopher”>` `<interp type"estoicos antiguos">`aquel
					   Pórtico todo entero`</name>` `</interp>` grita que `<interp type="descripción de la felicidad">`el hombre
						 para nada ha nacido sino para la `<term type="concepto filosófico">`virtud`</term>`; que ella misma con
						 su resplandor atrae las almas hacia sí,
						 sin que se ofrezca desde afuera absolutamente ningún provecho o recompensa a modo de seducción
					   `</interp>`; que el placer aquel de `<name type=“person” subtype=“philosopher” xml:id=“Epicuro”>`
						 Epicuro`</name>`sólo entre las bestias es común, en cuya compañía no es justo meter al hombre y al
						 `<term type="concepto filosófico">`sabio`</term>`.
					 `</div2>`
  
  
           `<div2 n="3" type="fragment">`
						 302 DIÓGENES LAERCIO, VII 127 [S. V. F. I 187]
             Que ella `<interp type="descripción de la felicidad">`[`<term type="concepto filosófico">`la virtud`</term>`]
						 es autosuficiente para la `<term type="concepto filosófico">`felicidad`</term>` `</interp>`, según dice `<name
						 type=“person” subtype=“philosopher” xml:id=“Zenón_de_Citio”>`Zenón`</name>`.
					 `</div2>`
  
  
					 `<div2 n="4" type="fragment">`
						 299 CICERÓN, Disputaciones tusculanas II 29 [S. V. F. I 185]
					   Nada es malo, dice [`<name type=“person” subtype=“philosopher” xml:id=“Zenón_de_Citio”>`Zenón`</name>`],
					   sino lo que es torpe y `<term type="concepto filosófico">`vicioso`</term>`... `<interp type="descripción de
						 la felicidad">`Nunca algo, dice, molesta, aunque duela, si conduce a la `<term type="concepto filosófico">`
						 vida feliz`</term>`, la cual consiste solamente en la `<term type="concepto filosófico">`virtud`</term>`.
						 [El dolor], sin embargo, se ha de rechazar. ¿Por qué? `<interp type="descripción de la Naturaleza">`
						 Es áspero, contrario a la `<term type="concepto filosófico" xml:id="Naturaleza">`naturaleza`</term>`,
						 difícil de tolerar, triste y duro`</interp>` `</interp>`.
				   `</div2>`
  
  
					 `<div2 n="5" type="fragment">`
						 329 CICERÓN, Disputaciones tusculanas IV 47 [S. V. F. 1 205]
					   La definición de la `<term type="concepto filosófico">`perturbación`</term>`, que considero bien utilizada por `<name type=“person”
						 subtype=“philosopher” xml:id=“Zenón_de_Citio”>`Zenón`</name>`. Así, en efecto, la define: `<interp
						 type="descripción de la Naturaleza">`la `<term type="concepto filosófico">`perturbación`</term>` es un
						 `<term type="concepto filosófico">`sacudimiento del alma`</term>`, desviado de la `<term type="concepto
						 filosófico">`razón`</term>`
						 y contrario a la `<term type="concepto filosófico" xml:id="Naturaleza">`naturaleza`</term>` `</interp>`, o, más
						 brevemente, `<interp type="descripción de la Naturaleza">`la `<term type="concepto filosófico">`
						 perturbación`</term>` es un `<term type="concepto filosófico">`apetito`</term>` bastante vehemente,
						 entendiéndose por «vehemente» el que está lejos de la serenidad de la `<term type="concepto
						 filosófico" xml:id="Naturaleza">`naturaleza`</term>` `</interp>`.
				   `</div2>`
  
  
					 `<div2 n="6" type="fragment">`
						 371 ESTOBEO, Églogas II 7-8, pág. 85, 13 W [S. V. F. I 230]
					   Define, pues, el `<term type="concepto filosófico">`deber`</term>`: `<interp type="descripción de la felicidad">`
						 consecuencia en la vida, que, llevada a la práctica, tiene `<term type="concepto filosófico">`justificación
						 racional`</term>` `</interp>`. Lo contrario [se llama] `<term type="concepto filosófico">`apartado del deber
					   `</term>`. `<interp type="descripción de la Naturaleza">`Esto se extiende aun a la `<term type="concepto
						 filosófico">`irracionalidad`</term>` de los animales, pues también ellos actúan en cierto modo de acuerdo
						 con su propia `<term type="concepto filosófico" xml:id="Naturaleza">`naturaleza`</term>` `</interp>`. [Pero] en
						 lo que atañe a los `<term type="concepto filosófico">`animales racionales`</term>`, así lo define:
						 consecuencia en la vida.
					 `</div2>`
  
  
					 `<div2 n="7" type="fragment">`
						 409 PLUTARCO, Sobre la fortuna o virtud de Alejandro I 6, 329 a [S.V.F I 262]
					   Y la muy admirada `<title xml:id="rep-Zn-Ctio">` `<term type="concepto filosófico">`República`</term>` `</title>`
						 de `<name type=“person” subtype=“philosopher” xml:id=“Zenón_de_Citio”>`Zenón`</name>`, fundador de la secta
						 de los estoicos, se resume en este único punto capital: que `<interp type="descripción de la felicidad">`no
						 debemos ser ciudadanos de `<term type="concepto filosófico">`Estados`</term>` y pueblos diferentes, separados
						 todos por leyes particulares, sino que hemos de considerar a todos los hombres como paisanos y
						 conciudadanos; que el modo de vida y el orden deben considerarse uno solo, como corresponde a una multitud
						 que convive alimentada por una `<term type="concepto filosófico" xml:id="Providencia">`ley común`</term>`
					   `</interp>`. Esto lo escribió `<name type=“person” subtype=“philosopher” xml:id=“Zenón_de_Citio”>`Zenón`</name>`
						 como un sueño o como una imagen del orden filosófico y del Estado ideal.
					 `</div2>`
				 `</div1>`
         `<figure>`
            `<graphic url="http://www.tei-c.org/logos/TEI-glow.png"/>`
         `</figure>`
      `</body>`
  `</text>`
`</TEI>`
