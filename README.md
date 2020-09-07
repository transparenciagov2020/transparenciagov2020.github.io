<meta property="og:title" content="Manifiesto en favor de la transparencia en desarrollos de software públicos">

# Manifiesto en favor de la transparencia en desarrollos de software públicos

* [Resumen](#resumen)
* [Manifiesto](#manifiesto)
* [Firmas](#firmas)
* [Súmate al manifiesto ](#súmate-al-manifiesto)


## Resumen

Este manifiesto expone la necesidad de seguir una serie de pautas en desarrollos de software destinados a servir al público, con Radar COVID como ejemplo. Radar COVID es uno de los primeros ejemplos de la nueva generación de infraestructura pública. Estas pautas describen elementos imprescindibles para implementar procesos abiertos que permitan a la sociedad participar en la integración de nuevas tecnologías en la administración desarrolladas con dinero público. Entre otros, la publicación de documentación y código que provean a la comunidad científica y la sociedad civil de la capacidad de escrutinio necesaria para identificar puntos a mejorar y contribuir a desarrollar y desplegar soluciones digitales democráticas, inclusivas y conformes a los más altos estándares. La infraestructura pública es parte del bien común de una sociedad. Mediante ella se ordena y estructura la sociedad, creando las reglas de acceso y disponibilidad a servicios sociales. Su legitimidad depende de su grado de inclusividad y democratización. La implantación de este tipo de estándares es especialmente importante en estos momentos en que se están automatizando y dejando en manos de programas informáticos procesos que afectan directamente a las personas y a la sociedad. Éstos deben ser monitorizados para evitar resultados no deseados.

<hr>

## Manifiesto

Los abajo firmantes, miembros de la comunidad académica española, manifiestan:

La propagación del virus causante de la COVID-19 ha provocado que gobiernos de todo el mundo desplieguen medidas excepcionales y busquen soluciones tecnológicas que ayuden a la contención de la pandemia. Entre estas soluciones, las llamadas "aplicaciones móviles de trazabilidad de contactos" parecen una de las más prometedoras. Estas aplicaciones se han desplegado ya en distintos países  con resultados preliminares que invitan al optimismo, y poniendo su código disponible para escrutinio público. Entre otros: [Alemania](https://github.com/corona-warn-app/cwa-app-android), [Austria](https://github.com/austrianredcross/stopp-corona-android), [Canada](https://github.com/cds-snc/covid-alert-app), [Ecuador](https://minka.gob.ec/asi-ecuador), [Estonia](https://koodivaramu.eesti.ee/tehik/hoia), [Holanda](https://github.com/minvws/nl-covid19-notification-app-design), [Irlanda](https://github.com/HSEIreland/covid-tracker-app), [Italia](https://github.com/immuni-app/immuni-app-android), [Portugal](https://github.com/stayawayinesctec), y [Suiza](https://github.com/DP-3T/dp3t-app-android-ch).

En España, la Secretaría de Estado de Digitalización e Inteligencia Artificial (SEDIA) ha lanzado la aplicación Radar COVID, desarrollada en colaboración con Indra Sistemas, S.A. La aplicación se lanzó en Google Play el 29 de Junio, y se inició una prueba piloto en La Gomera. Tras analizar los resultados del piloto, considerados positivos, la SEDIA ha puesto la aplicación a disposición de todos los españoles, supeditada a su previa integración por parte de los servicios de salud de las Comunidades Autónomas.

La aplicación ha sido descargada ya por más de 3,4 millones de españoles, y está integrada en más de la mitad de las Comunidades Autónomas. Radar COVID es ya parte de la nueva generación de infraestructura de sanidad pública. La aplicación marca un hito no sólo como innovación digital, sino también por su carácter cooperativo. Radar COVID precisa de la cooperación de toda la sociedad, y para maximizar su utilidad necesita ser descargada y activada por una cantidad sustancial de usuarios. Esto la convierte en una tecnología de carácter masivo y de alto impacto social. A lo largo de la Historia europea, los gobiernos han respondido a epidemias democratizando las infraestructuras de salud pública. Democratizar no sólo implica permitir a la ciudadanía el acceso a la infraestructura, sino la co-creación de dichas infraestructuras junto con la sociedad.

En una sociedad tan heterogénea como la española, esta co-creación únicamente tendrá éxito con la ayuda de expertos de diversas disciplinas. No hay tecnología sin fallos y por lo tanto es necesario un escrutinio multidisciplinar para conseguir el mejor resultado. Únicamente el esfuerzo conjunto interdisciplinario y con la sociedad civil puede identificar de forma eficiente sesgos potenciales y errores en la conceptualización e implementación de la aplicación que puedan dar lugar a efectos indeseados en términos de discriminación y vulneración de derechos.

A día de hoy, no se ha publicado ninguna documentación sobre el diseño de Radar COVID, sobre su implementación ni sobre el proceso de integración de las Comunidades Autónomas. El 1 de Septiembre, la Secretaría de Estado de Digitalización e Inteligencia Artificial anunció que el código de la aplicación se abrirá al público el día 9 de Septiembre. Con su decisión, la SEDIA ha iniciado una democratización de las infraestructuras digitales públicas. Los abajo firmantes aplauden esta decisión, que sin duda es un paso importante de cara a fortalecer la confianza de la ciudadanía en la app, maximizando así su impacto. La apertura del código debe ir acompañada de la documentación e información completas, a fin de que la comunidad científica y la sociedad civil tengan la capacidad de escrutinio necesaria para identificar puntos a mejorar y contribuir a desarrollar y desplegar Radar COVID conforme a los más altos estándares.

Los abajo firmantes hacemos un llamamiento a la comunidad científica, sociedad civil y sector privado a contribuir a este hito en la historia de la digitalización. Para que esta colaboración tenga la mayor efectividad, es preciso que se hagan públicos los siguientes elementos relativos al desarrollo de Radar COVID:

- Un repositorio con el código que permita analizar la versión de todos los elementos del sistema el día que se haga público así como futuros cambios, incluyendo aplicación y servidores junto con los detalles de su despliegue y gobernanza: dónde se hallan, quién los administra, y qué medidas de seguridad se han adoptado tanto para el despliegue a nivel nacional como el relativo a las Comunidades Autónomas.

- El repositorio de código utilizado durante el desarrollo, incluyendo el historial desde el inicio del desarrollo, detallando los cambios desde que la primera versión se hace disponible en las tiendas de las plataformas móviles y por lo tanto descargadas por los usuarios. La revisión de las versiones anteriores es necesaria debido a que no todos los usuarios actualizan periódicamente sus móviles.

- Informe de diseño del sistema (aplicación y servidores), detallando los análisis que han llevado a decidir los parámetros de configuración y uso de la API de Exposición de Notificaciones de Google y Apple, los mecanismos implementados y las librerías y servicios utilizados para evaluar la seguridad y privacidad de los datos, así como la evaluación de la inclusión y accesibilidad del diseño.

- Informe detallado de los mecanismos de monitorización de la aplicación y mecanismos asociados para asegurar la privacidad y el cumplimiento de la normativa de protección de datos, referido a los datos recogidos tanto durante el piloto como en la fase de producción.

- La evaluación de impacto en la protección de datos basada en el informe de diseño y los análisis de riesgo asociados a la aplicación y su uso en las plataformas Android y iOS.

La liberación del código y su adecuada documentación es necesaria también para la materialización del principio de privacidad basada en el diseño así como de los restantes principios de protección de datos contenidos en el RGPD, singularmente el de responsabilidad proactiva. La actual coyuntura constituye una oportunidad histórica para hacer realidad estos principios y para que la app, diseñada bajo la dirección de la SEDIA, sea un éxito. Sin un procedimiento abierto que posibilite la implicación de toda la comunidad y de los destinatarios de la app, esta no gozará de la confianza necesaria para su adopción masiva.

En complemento a lo anterior, a efectos de transparencia, es deseable la máxima información sobre el sistema de gobernanza y toma de decisiones en el diseño de la aplicación. En este sentido, es importante que la involucración de entidades privadas, y su rol y sus responsabilidades en el proyecto se identifiquen de manera clara.

Finalmente, queremos destacar que Radar COVID es un elemento esencial dentro de un complejo plan de contención de los contagios, pero no es la única medida con la que detener las cadenas de contagio. Es una medida de apoyo y no sustituye a rastreadores manuales de contacto, sino que necesita desplegarse en coordinación con los procesos manuales ya existentes. Su uso, incluso a nivel masivo, no excluye la necesidad del establecimiento de otras medidas de contención de la pandemia. Entre otras medidas ya conocidas, como el uso de máscaras o distanciamiento en el lugar de trabajo, para garantizar el impacto de Radar COVID es necesaria la adopción de medidas legales y presupuestarias de apoyo social que permitan a los usuarios seguir las recomendaciones de la app sin sufrir perjuicios económicos, laborales o sociales. Teniendo en cuenta las asimetrías sociales del país, por las que no todos disponen de móviles o de acceso a la infraestructura digital, es importante recalcar el carácter voluntario de la app. Es necesario también monitorizar e identificar potenciales abusos discriminatorios en ámbitos como el de la vivienda, el mercado de trabajo, la educación y, en general, en el acceso a servicios públicos y privados, en toda la amplitud reconocida por la legislación actual o futura.

<hr>

## Firmas

1. Prof. Dr. Ignacio Aedo, Universidad Carlos III de Madrid

2. Dr. Miguel Aguilera, University of Sussex (Reino Unido)

3. Dr. Ignacio Alamillo-Domingo, Universidad de Murcia

4. Prof. Dr. José María del Álamo, Universidad Politécnica de Madrid

5. Prof. Dra. Gloria Alarcon García, Universidad de Murcia

6. Prof. Dr. José Luis Alba Castro, Universidade de Vigo

7. Prof. Dra. Mª Belén Andreu Martínez, Universidad de Murcia

8. Prof. Dr. Antonio Alonso Ayuso, Universidad Rey Juan Carlos

9. Prof. Dra. María Alpuente, Universidad Politécnica de Valencia

10. Prof. Dr. Juan Antonio Álvarez García, Universidad de Sevilla

11. Dr. Pablo Aragón, Universitat Pompeu Fabra

12. Prof. Dra. Mª Aránzazu Moretón Toquero, Universidad de Valladolid

13. Javier Armentia Fructuoso, Planetario de Pamplona

14. Dr. David Arroyo Guardeño, Instituto de Tecnologías Físicas y de la Información - CSIC

15. Prof. Dr. David Atienza Alonso, École Polytechnique Fédérale de Lausanne (Suiza)

16. Prof. Dra. Nieves Atienza Martínez, Universidad de Sevilla

17. Prof. Dra. Mónica Arenas Ramiro, Universidad de Alcalá 

18. Prof. Dr. Txetxu Ausín, Instituto de Filosofía - CSIC

19. Prof. Dr. José L. Aznarte, Universidad Nacional de Educación a Distancia - UNED

20. Prof. Dr. Ricardo Baeza-Yates, Northeastern University - Silicon Valley (Estados Unidos) & Universitat Pompeu Fabra

21. Prof. Dr. Santiago Bello Paredes, Universidad de Burgos

22. Prof. Dra. Marta Beltrán Pardo, Universidad Rey Juan Carlos

23. Dra. Juani Bermejo-Vega, Universidad de Granada

24. Prof. Dra. María Bermudez-Edo, Universidad de Granada

25. Prof. Dr. Josep Blat, Universitat Pompeu Fabra

26. Prof. Dr. Federico Botella, Universidad Miguel Hernández de Elche

27. Prof. Dr. Vicent Botti, Universidad Politécnica de Valencia

28. Prof. Dr. Andrés Boix Palop, Universitat de València

29. Prof. Uwe Brauer, Universidad Complutense de Madrid

30. Dr. Vanni Brusadin, Universitat de Barcelona 

31. Prof. Dr. Antonio J. Caamaño, Universidad Rey Juan Carlos

32. Prof. Dr. Juan Caballero, Instituto IMDEA Software

33. Prof. Dr. Jordi Cabot, Universitat Oberta de Catalunya

34. Prof. Dr. Stefano Cabras, Universidad Carlos III de Madrid 

35. Prof. Dr. Daniel Cagigas Muñiz, Universidad de Sevilla

36. Prof. Dr. Patrici Calvo, Universitat Jaume I

37. Dr. Cédric M. Campos, Universidad Rey Juan Carlos

38. Prof. Dr. Javier Campos Laclaustra, Universidad de Zaragoza

39. Prof. Dr. Antonio Cañabate Carmona, Universitat Politècnica de Catalunya

40. Prof. Dr. Josep Cañabate Pérez, Universitat Autònoma de Barcelona

41. Prof. Dra. Maria Casado, Observatori de Bioètica i Dret, Càtedra Unesco de Bioètica, Universitat de Barcelona

42. Prof. Dr. Ignacio Cascos Fernández, Universidad Carlos III de Madrid

43. Prof. Dr. Ignacio Cascudo Pueyo, Instituto IMDEA Software

44. Prof. Dra. Cecilia Castaño Collado, Universidad Complutense de Madrid

45. Prof. Dr. Jorge Castellanos Claramunt. Universidad de Valencia

46. Prof. Dra. Eva M. Castro Barbero, Universidad Rey Juan Carlos

47. Prof. Dr. Manuel Carro, Instituto IMDEA Software & Universidad Politécnica de Madrid

48. Prof. Dra. María Eugenia Castellanos Nueda, Universidad Rey Juan Carlos.

49. Prof. Dr. Agustí Cerrillo i Martínez, Universitat Oberta de Catalunya

50. Prof. Dr. Oscar Corcho, Universidad Politécnica de Madrid

51. Prof. Dr. Alberto Corsín Jiménez, Consejo Superior de Investigaciones Científicas - CSIC

52. Prof. Dr. Ulises Cortés, Universitat Politècnica de Catalunya

53. Prof. Dr. Enrique Costa Montenegro, Universidade de Vigo

54. Prof. Dr. Lorenzo Cotino Hueso, Universidad de Valencia

55. Prof. Dr. J. Ignacio Criado, Universidad Autónoma de Madrid

56. Prof. Dr. Iñigo Cuiñas, Universidade de Vigo

57. Prof. Dra. Vanesa Daza, Universitat Pompeu Fabra

58. Prof. Dra. Itziar de Lecuona, Observatori de Bioètica i Dret, Càtedra Unesco de Bioètica, Universitat de Barcelona

59. Prof. Dra. Claudia Díaz, KU Leuven (Bélgica)

60. Prof. Dra. Paloma Díaz Pérez, Universidad Carlos III de Madrid

61. Prof. Dr. Juan Manuel Dodero Beardo, Universidad de Cádiz

62. Prof. Dr.. Antonio Domínguez Vila,  Universidad de La Laguna

63. Prof. Dr. Josep Domingo-Ferrer, Universitat Rovira i Virgili

64. Prof. Dr. Juan Carlos Dueñas López, Universidad Politécnica de Madrid

65. Prof. Dr. Guillermo Escobar Roca, Universidad de Alcalá

66. Prof Dr. Salvador España Boquera, Universitat Politècnica de València

67. Prof. Dr. Pere Fabra Abat, Universitat Oberta de Catalunya

68. Prof. Dr. Manuel José Fernández Iglesias, Universidade de Vigo 

69. Prof. Dr. Jesus Fernandez-Villaverde, University of Pennsylvania

70. Prof. Dra. Antonia Ferrer Sapena, Universitat Politècnica de València

71. Prof. Dr. Dario Fiore, Instituto IMDEA Software

72. Prof. Dr. José Fortes Gálvez, Universidad de Las Palmas de Gran Canaria

73. Prof. Dr. José María de Fuentes , Universidad Carlos III de Madrid

74. Prof. Dr. Ramón Galindo Caldés, Universitat Oberta de Catalunya

75. Prof. Dr. Domingo Gallardo López, Universidad de Alicante

76. Prof. Dr. Eduardo Gamero Casado, Universidad Pablo de Olavide

77. Almudena García, Universidad de Huelva

78. Helena García Cebollada, Instituto de Biocomputación y Física de Sistemas Complejos - Universidad de Zaragoza

79. Prof. Dra. María del Rosario García Mahamut - Universitat Jaume I

80. Dr. Pablo Garcia Molina, Georgetown University (Estados Unidos)

81. Prof. Dr. Joaquín García-Alfaro, Institut Polytechnique de Paris (Francia) & Carleton University (Canadá)

82. Prof. Dr. Hector Geffner, Universitat Pompeu Fabra

83. Dr. Xavier Gironès García, Fundación Universitaria del Bages

84. Prof. Dr. Vicenç Gómez, Universitat Pompeu Fabra

85. Prof. Dr. Juan Antonio Gómez Pulido, Universidad de Extremadura

86. Dr. David Gómez-Ullate Oteiza, Universidad de Cádiz

87. Prof. Dr. Jesús M. González Barahona, Universidad Rey Juan Carlos

88. Prof. Dr. Luis Miguel González de la Garza, Universidad Nacional de Educación a Distancia - UNED

89. Prof. Dra. Gloria González Fuster, Vrije Universiteit Brussel (Bélgica)

90. Prof. Dra. Lorena González Manzano, Universidad Carlos III de Madrid

91. Prof. Dra. Maria Isabel González Vasco, Universidad Rey Juan Carlos

92. Prof. Dra. Alessandra Gorla, Instituto IMDEA Software

93. Prof. Dr. Juan José Guardia Hernández, Universitat Internacional de Catalunya

94. Dr, Ariel Guersenzvaig, ELISAVA Escuela de Diseño e Ingeniería de Barcelona

95. Prof. Benjamín Guix Melcior, Universidad de Barcelona

96. Prof. Dr. Juan Carlos Hernández, Universidad de Navarra

97. Prof. Dr. Jose Hernandez-Orallo, Universitat Politécnica de Valencia

98. Prof. Dr. Antonio Hernández Pérez, Universidad Carlos III de Madrid

99. Prof. Dr. Daniel Innerarity, Universidad del País Vasco & European University Institute of Florence

100. Hugo Jiménez Hernández, Barcelona Supercomputing Center

101. Prof. Dr. Fco. Javier Jiménez Leube, Universidad Politécnica de Madrid

102. Prof. Dr. Andrés Jiménez Ramírez, Universidad de Sevilla

103. Dr. Daniel Jiménez-González, Universitat Politècnica de Catalunya

104. Dr. Marc Juarez, University of Southern California (Estados Unidos)

105. Prof. Dr. Vicente Julian, Universitat Politècnica de València

106. Prof. Dr. Pedro Larrañaga, Universidad Politécnica de Madrid

107. Prof. Dr. Ramon López de Mántaras, Instituto de Investigación en Inteligencia Artificial - CSIC & Western Sydney University (Australia)

108. Dr. Álvaro López García, Consejo Superior de Investigaciones Científicas - CSIC

109. Prof. Dra. Maite López Sánchez, Universidad de Barcelona & Instituto de Investigación en Inteligencia Artificial - CSIC

110. Dr. Jorge Lozano Miralles, Universidad de Jaén

111. Dr. Miguel Luengo Oroz , Global Pulse ONU (Estados Unidos)

112. Prof. Dr. Javier Macías Guarasa, Universidad de Alcalá

113. Dr. Jaume Manero Font, Universitat Politécnica de Catalunya

114. Dr. David Martín de Diego, Instituto de Ciencias Matemáticas - CSIC

115. Prof. Dr. Sebastià Martín Molleví, Universitat Politècnica de Catalunya

116. Dr. José Luis Martínez Martínez, Universidad de Castilla-La Mancha

117. Prof Dra. Alejandra Martínez Monés, Universidad de Valladolid

118. Prof. Dra. Pastora Martínez Samper, Universitat Oberta de Catalunya

119. Prof. Dr. David Martínez Zorrilla. Universitat Oberta de Catalunya

120. Prof. Manuel Medina Llinàs, Universitat Politècnica de Catalunya

121. Prof. Dra. Ernestina Menasalvas Ruiz, Universidad Politécnica de Madrid

122. Dr. Juan Julián Merelo Guervós, Universidad de Granada

123. Javier Miranzo Díaz, Universitat Oberta de Catalunya 

124. Prof. Dr. Artemio Mojón Ojea, Universidade de Vigo

125. Dr. José Molina Molina, Consejo de la Transparencia de la Región de Murcia & Universidad de Murcia

126. Dr. José F. Morales, Instituto IMDEA Software

127. Prof. Dr. Yamir Moreno, Universidad de Zaragoza

128. Prof. Dra. Mª Aránzazu Moretón Toquero, Universidad de Valladolid

129. Dra. Melania Moscoso, Instituto de Filosofía - CSIC

130. Dr. Alfonso Muñoz, Universidad Politécnica de Madrid

131. Prof. Dr. Vicente J. Navarro Marchante, Universidad La Laguna

132. Prof. Dra. Susana Navas Navarro. Universitat Autònoma de Barcelona

133. Fernando Orejas, Universitat Politècnica de Catalunya

134. Prof. Dr. Juan Luis Paniagua Soto, Universidad Complutense de Madrid

135. Dr. José Antonio Parejo Maestre, Universidad de Sevilla

136. Prof. Dr. José Parra-Moyano, Copenhagen Business School (Dinamarca)

137. Prof. Dra. Encarnación Pastor Martín, Universidad Politécnica de Madrid 

138. Prof. Dr. Sergio Pastrana Portillo, Universidad Carlos III de Madrid & University of Cambridge (Reino Unido)

139. Prof. Dr. Miquel Peguera, Universitat Oberta de Catalunya 

140. Prof. Dr. Josep Perelló, Universitat de Barcelona

141. Prof. Dr. Ángel Pérez del Pozo, Universidad Rey Juan Carlos

142. Prof. Dr. Fernando Pérez González, Universidade de Vigo

143. Prof. Dr. Ernesto Pimentel, Universidad de Málaga

144. Dr. Manuel Poch, Universitat de Girona

145. Prof. Dr. Juli Ponce Solé, Universitat de Barcelona

146. Dr. Manuel Portela, Universitat Pompeu Fabra

147. Dr. José Ra. Portillo Fernández, Universidad de Sevilla

148. Dr. Alejandro Pozas Kerstjens, Universidad Complutense de Madrid

149. Prof. Dr. Joan Manuel del Pozo Álvarez, Universitat de Girona

150. Dr. Miguel Ángel Presno Linera, Universidad de Oviedo

151. Prof. Dra. Francisca Ramón Fernández, Universitat Politècnica de València

152. Dra. Leonor Rams Ramos, Universidad Rey Juan Carlos 

153. Prof. Dr. Miguel Rebollo Pedruelo. Universitat Politècnica de València

154. Prof. Dr. Josep Redon, INCLIVA Instituto de Investigación Sanitaria & Universidad de Valencia

155. Prof. Dra. Helena Rifà-Pous, Universitat Oberta de Catalunya

156. Prof. Dr. David Ríos Insua, Real Academia de Ciencias Exactas, Físicas y Naturales

157. Prof. Agustín Riscos Núñez, Universidad de Sevilla

158. Prof. Dr. Gregorio Robles, Universidad Rey Juan Carlos

159. Prof. Aníbal Rodríguez Bernal, Universidad Complutense de Madrid

160. Prof. Dr. Miguel Rodríguez Pérez, Universidade de Vigo

161. Prof. Dra. María del Carmen Romero Ternero, Universidad de Sevilla

162. Prof. Dr. Antoni Rubí Puig, Universitat Pompeu Fabra

163. Prof. Dr. Agustín Ruiz Robledo, Universidad de Granada

164. Dr. Javier Ruiz Soler, Simon Fraser University (Canadá)

165. Prof. Dra. Eva Sáenz Royo, Universidad de Zaragoza

166. Prof. Dr. Manuel Sánchez de Diego Fdez. de la Riva, Universidad Complutense de Madrid

167. Prof. Dr. Ángel J. Sánchez Navarro, Universidad Complutense

168. Dr. Javier Sánchez-Monedero. Cardiff University (Gales, Reino Unido)

169. Prof. Dr. José Miguel Santos Espino, Universidad de Las Palmas de Gran Canaria

170. Prof. Dr. Joaquín Sarrión Esteve, Universidad Nacional de Educación a Distancia - UNED

171. Prof. Dr. Sergio Segura Rueda, Universidad de Sevilla

172. Prof. Dra. Isabel Serrano Maiilo, Universidad Complutense de Madrid.

173. Prof. Dr. Carles Sierra, Instituto de Investigación en Inteligencia Artificial - CSIC

174. Prof. Dr. Javier Sierra Rodríguez, Universidad de Murcia

175. Prof. Dr. Josep Silva Galiana, Universitat Politècnica de València

176. Prof. Dr. Pere Simón Castellano, Universidad Internacional de la Rioja - UNIR

177. Prof. Dr. Enrique Soriano-Salvador, Universidad Rey Juan Carlos

178. Prof. Dr. Luc Steels, Institut de Biologia Evolutiva, UPF-CSIC

179. Prof. Dr. Guillermo Suarez-Tangil, King’s College London (Reino Unido) & Instituto IMDEA Networks

180. Prof. Dra. Sílvia Suñer Lázaro, Universitat Politècnica de Catalunya

181. Prof. Dr. Juan Tapiador, Universidad Carlos III de Madrid

182. Prof. Dr. Marc Tarrés Vives, Universitat de Barcelona

183. Prof. Dra. Carme Torras, Institut de Robòtica i Informàtica Industrial, UPC-CSIC

184. Prof. Dra. Blanca Torrubia Chalmeta, Universitat Oberta de Catalunya

185. Dr. Pablo Trinidad Martín-Arroyo, Universidad de Sevilla

186. Prof. Dra. Carmela Troncoso, École Polytechnique Fédérale de Lausanne (Suiza)

187. Dra. Ana Valdivia, King's College London (Reino Unido)

188. Prof. Dr. Gerardo Valeiras, Universidad de Sevilla

189. Prof. Dr. Narseo Vallina-Rodriguez, Instituto IMDEA Networks

190. Prof. Dr. Julián Valero Torrijos, Universidad de Murcia

191. Prof. Dr. Juan Manuel Vara Mesa, Universidad Rey Juan Carlos

192. Prof. Dra. Victoria Velasco, Universidad de Granada

193. Prof. Dra. Clara Velasco Rico, Universitat Pompeu Fabra

194. Prof. Dr. José Luis Verdegay, Universidad de Granada

195. Dr. Víctor Vicente Palacios, Universidad de Salamanca

196. Prof. Dr. Germán Vidal, Universitat Politècnica de València

197. Prof. Dra. Mònica Vilasau Solana, Universitat Oberta de Catalunya

198. Prof. Dra. Raquel Xalabarder, Universitat Oberta de Catalunya

199. Prof. Dr. Sebastià Xambó Descamps, Universitat Politècnica de Catalunya

200. Dr. Urko Zurutuza, Mondragon Unibertsitatea

<hr>

## Súmate al manifiesto

Si perteneces a la comunidad académica española y quieres sumarte a este manifiesto, comparte por favor tu nombre, apellidos e institucion académica en el siguiente formulario: [https://docs.google.com/forms/d/e/1FAIpQLSd1o_23n55D_IPeqTQmMHPxJTvx6659ALsy4ru4tBq5AQ3Vqg/viewform](https://docs.google.com/forms/d/e/1FAIpQLSd1o_23n55D_IPeqTQmMHPxJTvx6659ALsy4ru4tBq5AQ3Vqg/viewform). 

<style>
h1:nth-child(1) {
  visibility: hidden;
  line-height: 0;
}
</style>
