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

1. Prof. Dr. Leopoldo Abad Alcalá, Universidad CEU San Pablo

2. Dr. Unai Aberasturi Gorriño, Euskal Herriko Unibertsitatea - Universidad del País Vasco

3. Prof. Dr. Ignacio Aedo, Universidad Carlos III de Madrid

4. Dr. Miguel Aguilera, University of Sussex (Reino Unido)

5. Dr. Ignacio Alamillo-Domingo, Universidad de Murcia

6. Prof. Dr. José María del Álamo, Universidad Politécnica de Madrid

7. Prof. Dra. Gloria Alarcon García, Universidad de Murcia

8. Prof. Dr. José Luis Alba Castro, Universidade de Vigo

9. Prof. Dra. Mª Belén Andreu Martínez, Universidad de Murcia

10. Prof. Dr. Antonio Alonso Ayuso, Universidad Rey Juan Carlos

11. Dr. Bartomeu Alorda Ladaria, Universitat de les Illes Balears

12. Prof. Dra. María Alpuente, Universidad Politécnica de Valencia

13. Prof. Dr. Juan Antonio Álvarez García, Universidad de Sevilla

14. Dr. Pablo Aragón, Universitat Pompeu Fabra

15. Prof. Dra. Mª Aránzazu Moretón Toquero, Universidad de Valladolid

16. Javier Armentia Fructuoso, Planetario de Pamplona

17. Dr. David Arroyo Guardeño, Instituto de Tecnologías Físicas y de la Información - CSIC

18. Prof. Dr. David Atienza Alonso, École Polytechnique Fédérale de Lausanne (Suiza)

19. Prof. Dra. Nieves Atienza Martínez, Universidad de Sevilla

20. Prof. Dra. Mónica Arenas Ramiro, Universidad de Alcalá 

21. Prof. Dr. Txetxu Ausín, Instituto de Filosofía - CSIC

22. Prof. Dr. José L. Aznarte, Universidad Nacional de Educación a Distancia - UNED

23. Prof. Dr. Ricardo Baeza-Yates, Northeastern University - Silicon Valley (Estados Unidos) & Universitat Pompeu Fabra

24. Prof. Dra. Beatriz Barros Blanco, Universidad de Málaga

25. Prof. Dr. Santiago Bello Paredes, Universidad de Burgos

26. Prof. Dra. Marta Beltrán Pardo, Universidad Rey Juan Carlos

27. Prof. Dr. Fernando Benito Picazo, Universidad de Málaga

28. Dra. Juani Bermejo-Vega, Universidad de Granada

29. Prof. Dra. María Bermudez-Edo, Universidad de Granada

30. Prof. Dr. Josep Blat, Universitat Pompeu Fabra

31. Prof. Dr. Federico Botella, Universidad Miguel Hernández de Elche

32. Prof. Dr. Vicent Botti, Universidad Politécnica de Valencia

33. Prof. Dr. Andrés Boix Palop, Universitat de València

34. Prof. Uwe Brauer, Universidad Complutense de Madrid

35. Dr. Vanni Brusadin, Universitat de Barcelona 

36. Prof. Dr. Jacques Bulchand Gidumal, Universidad de Las Palmas de Gran Canaria

37. Prof. Dr. Antonio J. Caamaño, Universidad Rey Juan Carlos

38. Prof. Dr. Juan Caballero, Instituto IMDEA Software

39. Prof. Dr. Jordi Cabot, Universitat Oberta de Catalunya

40. Prof. Dr. Stefano Cabras, Universidad Carlos III de Madrid 

41. Prof. Dr. Daniel Cagigas Muñiz, Universidad de Sevilla

42. Prof. Dr. Patrici Calvo, Universitat Jaume I

43. Dr. Cédric M. Campos, Universidad Rey Juan Carlos

44. Prof. Dr. Javier Campos Laclaustra, Universidad de Zaragoza

45. Prof. Dr. Antonio Cañabate Carmona, Universitat Politècnica de Catalunya

46. Prof. Dr. Josep Cañabate Pérez, Universitat Autònoma de Barcelona

47. Prof. Dra. María Jose Carazo Liébana, Universidad de Jaén

48. Prof. Dr. Gabriel Cardona Juanals, Universitat de les Illes Balears

49. Prof. Dra. Maria Casado, Observatori de Bioètica i Dret, Càtedra Unesco de Bioètica, Universitat de Barcelona

50. Dr. Daniel Cascado Caballero, Universidad de Sevilla

51. Prof. Dr. Ignacio Cascos Fernández, Universidad Carlos III de Madrid

52. Prof. Dr. Ignacio Cascudo Pueyo, Instituto IMDEA Software

53. Prof. Dra. Cecilia Castaño Collado, Universidad Complutense de Madrid

54. Prof. Dr. Jorge Castellanos Claramunt. Universidad de Valencia

55. Prof. Dr. Carlos Castillo, Universitat Pompeu Fabra

56. Prof. Dra. Eva M. Castro Barbero, Universidad Rey Juan Carlos

57. Prof. Dr. Manuel Carro, Instituto IMDEA Software & Universidad Politécnica de Madrid

58. Prof. Dra. María Eugenia Castellanos Nueda, Universidad Rey Juan Carlos.

59. Dra. Rosa Catalán Campos, Universitat de Barcelona

60. Prof. Dr. Agustí Cerrillo i Martínez, Universitat Oberta de Catalunya

61. Prof. Dr. Ricardo Conejo, Universidad de Malaga

62. Prof. Dr. Oscar Corcho, Universidad Politécnica de Madrid

63. Dr. Adrián Cordón López, Hospital Regional Universitario de Málaga

64. Prof. Dr. Alberto Corsín Jiménez, Consejo Superior de Investigaciones Científicas - CSIC

65. Dra. Loreto Corredoira y Alfonso, Universidad Complutense de Madrid

66. Prof. Dr. Ulises Cortés, Universitat Politècnica de Catalunya

67. Prof. Dr. Enrique Costa Montenegro, Universidade de Vigo

68. Prof. Dr. Lorenzo Cotino Hueso, Universidad de Valencia

69. Dr. José M. Cotos Yáñez, Centro de Investigación en Tecnoloxías Intelixentes - Universidade de Santiago de Compostela

70. Prof. Dr. Félix Crespo Hellín, Universitat de Valencia

71. Prof. Dr. J. Ignacio Criado, Universidad Autónoma de Madrid

72. Prof. Dr. Iñigo Cuiñas, Universidade de Vigo

73. Prof. Dra. Vanesa Daza, Universitat Pompeu Fabra

74. Prof. Dra. Itziar de Lecuona, Observatori de Bioètica i Dret, Càtedra Unesco de Bioètica, Universitat de Barcelona

75. Prof. Dra. Claudia Díaz, KU Leuven (Bélgica)

76. Prof. Dra. Paloma Díaz Pérez, Universidad Carlos III de Madrid

77. Prof. Dr. Juan Manuel Dodero Beardo, Universidad de Cádiz

78. Prof. Dr.. Antonio Domínguez Vila, Universidad de La Laguna

79. Prof. Dr. Josep Domingo-Ferrer, Universitat Rovira i Virgili

80. Prof. Dr. Juan Carlos Dueñas López, Universidad Politécnica de Madrid

81. Prof. Dr. Guillermo Escobar Roca, Universidad de Alcalá

82. Prof Dr. Salvador España Boquera, Universitat Politècnica de València

83. Prof. Dr. Pere Fabra Abat, Universitat Oberta de Catalunya

84. Prof. Dr. Manuel José Fernández Iglesias, Universidade de Vigo 

85. Prof. Dr. José Julio Fernández Rodríguez, Universidad de Santiago de Compostela

86. Prof. Dr. Jesus Fernandez-Villaverde, University of Pennsylvania

87. Prof. Dra. Antonia Ferrer Sapena, Universitat Politècnica de València

88. Prof. Dr. Dario Fiore, Instituto IMDEA Software

89. Prof. Dr. José Fortes Gálvez, Universidad de Las Palmas de Gran Canaria

90. Prof. Dr. José María de Fuentes , Universidad Carlos III de Madrid

91. Prof. Dr. Ramón Galindo Caldés, Universitat Oberta de Catalunya

92. Dr. José Galindo Gómez, Universidad de Málaga

93. Carlos Galindo Jiménez, Universitat Politècnica de València

94. Prof. Dr. Domingo Gallardo López, Universidad de Alicante

95. Prof. Dr. Eduardo Gamero Casado, Universidad Pablo de Olavide

96. Almudena García, Universidad de Huelva

97. Helena García Cebollada, Instituto de Biocomputación y Física de Sistemas Complejos - Universidad de Zaragoza

98. Prof. Dra. María del Rosario García Mahamut - Universitat Jaume I

99. Dr. Pablo Garcia Molina, Georgetown University (Estados Unidos)

100. Prof. Dr. Joaquín García-Alfaro, Institut Polytechnique de Paris (Francia) & Carleton University (Canadá)

101. Prof. Dr. Hector Geffner, Universitat Pompeu Fabra

102. Dr. Xavier Gironès García, Fundación Universitaria del Bages

103. Prof. Dr. Vicenç Gómez, Universitat Pompeu Fabra

104. Prof. Dr. Juan Antonio Gómez Pulido, Universidad de Extremadura

105. Sergio Gómez Bachiller, Universidad de Córdoba

106. Dr. David Gómez-Ullate Oteiza, Universidad de Cádiz

107. Prof. Dr. Jesús M. González Barahona, Universidad Rey Juan Carlos

108. Prof. Dr. Luis Miguel González de la Garza, Universidad Nacional de Educación a Distancia - UNED

109. Prof. Dra. Gloria González Fuster, Vrije Universiteit Brussel (Bélgica)

110. Prof. Dra. Lorena González Manzano, Universidad Carlos III de Madrid

111. Prof. Dra. Maria Isabel González Vasco, Universidad Rey Juan Carlos

112. Prof. Dra. Alessandra Gorla, Instituto IMDEA Software

113. Prof. Dr. Juan José Guardia Hernández, Universitat Internacional de Catalunya

114. Dr, Ariel Guersenzvaig, ELISAVA Escuela de Diseño e Ingeniería de Barcelona

115. Prof. Benjamín Guix Melcior, Universidad de Barcelona

116. Prof. Dr. Juan Carlos Hernández, Universidad de Navarra

117. Prof. Dr. Jose Hernandez-Orallo, Universitat Politécnica de Valencia

118. Prof. Dr. Antonio Hernández Pérez, Universidad Carlos III de Madrid

119. Prof. Dr. Daniel Innerarity, Universidad del País Vasco & European University Institute of Florence

120. Hugo Jiménez Hernández, Barcelona Supercomputing Center

121. Prof. Dr. Fco. Javier Hormigo Aguilar, Universidad de Málaga

122. Prof. Dr. Fco. Javier Jiménez Leube, Universidad Politécnica de Madrid

123. Prof. Dr. Andrés Jiménez Ramírez, Universidad de Sevilla

124. Dr. Daniel Jiménez-González, Universitat Politècnica de Catalunya

125. Dr. Marc Juarez, University of Southern California (Estados Unidos)

126. Prof. Dr. Vicente Julian, Universitat Politècnica de València

127. Prof. Dr. Pedro Larrañaga, Universidad Politécnica de Madrid

128. Prof. Dr. Ramon López de Mántaras, Instituto de Investigación en Inteligencia Artificial - CSIC & Western Sydney University (Australia)

129. Dr. Álvaro López García, Consejo Superior de Investigaciones Científicas - CSIC

130. Prof. Dra. Maite López Sánchez, Universidad de Barcelona & Instituto de Investigación en Inteligencia Artificial - CSIC

131. Dr. Manuel López-Ibáñez, Universidad de Málaga

132. Dr. Jorge Lozano Miralles, Universidad de Jaén

133. Dr. Miguel Luengo Oroz , Global Pulse ONU (Estados Unidos)

134. Prof. Dr. Javier Macías Guarasa, Universidad de Alcalá

135. Dr. Jaume Manero Font, Universitat Politécnica de Catalunya

136. Dr. David Martín de Diego, Instituto de Ciencias Matemáticas - CSIC

137. Dr. Cristian Martín Fernández  Universidad de Málaga

138. Prof. Dr. Sebastià Martín Molleví, Universitat Politècnica de Catalunya

139. Dra. Beatriz del Carmen Martínez Isidoro, Universidad Complutense de Madrid

140. Dr. José Luis Martínez Martínez, Universidad de Castilla-La Mancha

141. Prof Dra. Alejandra Martínez Monés, Universidad de Valladolid

142. Prof. Dra. Pastora Martínez Samper, Universitat Oberta de Catalunya

143. Prof. Dr. David Martínez Zorrilla. Universitat Oberta de Catalunya

144. Prof. Manuel Medina Llinàs, Universitat Politècnica de Catalunya

145. Prof. Dra. Ernestina Menasalvas Ruiz, Universidad Politécnica de Madrid

146. Dr. Juan Julián Merelo Guervós, Universidad de Granada

147. Javier Miranzo Díaz, Universitat Oberta de Catalunya 

148. Prof. Dr. Artemio Mojón Ojea, Universidade de Vigo

149. Dr. José Molina Molina, Consejo de la Transparencia de la Región de Murcia & Universidad de Murcia

150. Dr. José F. Morales, Instituto IMDEA Software

151. Prof. Dr. Yamir Moreno, Universidad de Zaragoza

152. Prof. Dra. Mª Aránzazu Moretón Toquero, Universidad de Valladolid

153. Dra. Melania Moscoso, Instituto de Filosofía - CSIC

154. Dr. Alfonso Muñoz, Universidad Politécnica de Madrid

155. Prof. Dr. Vicente J. Navarro Marchante, Universidad La Laguna

156. Prof. Dra. Susana Navas Navarro. Universitat Autònoma de Barcelona

157. Fernando Orejas, Universitat Politècnica de Catalunya

158. Prof. Dr. Juan Luis Paniagua Soto, Universidad Complutense de Madrid

159. Dr. José Antonio Parejo Maestre, Universidad de Sevilla

160. Prof. Dr. José Parra-Moyano, Copenhagen Business School (Dinamarca)

161. Prof. Dra. Encarnación Pastor Martín, Universidad Politécnica de Madrid 

162. Prof. Dr. Sergio Pastrana Portillo, Universidad Carlos III de Madrid & University of Cambridge (Reino Unido)

163. Prof. Dra. Marta Patiño Martínez, Universidad Politécnica de Madrid

164. Prof. Dr. Miquel Peguera, Universitat Oberta de Catalunya 

165. Prof. Dr. Ricardo Peña Marí, Universidad Complutense de Madrid

166. Prof. Dr. Josep Perelló, Universitat de Barcelona

167. Prof. Dr. Ángel Pérez del Pozo, Universidad Rey Juan Carlos

168. Prof. Dr. Fernando Pérez González, Universidade de Vigo

169. Prof. Dr. Ernesto Pimentel, Universidad de Málaga

170. Dr. Manuel Poch, Universitat de Girona

171. Prof. Dr. Juli Ponce Solé, Universitat de Barcelona

172. Dr. Manuel Portela, Universitat Pompeu Fabra

173. Dr. José Ra. Portillo Fernández, Universidad de Sevilla

174. Dr. Alejandro Pozas Kerstjens, Universidad Complutense de Madrid

175. Prof. Dr. Joan Manuel del Pozo Álvarez, Universitat de Girona

176. Dr. Miguel Ángel Presno Linera, Universidad de Oviedo

177. Prof. Dra. Francisca Ramón Fernández, Universitat Politècnica de València

178. Dra. Leonor Rams Ramos, Universidad Rey Juan Carlos 

179. Prof. Dr. Miguel Rebollo Pedruelo. Universitat Politècnica de València

180. Prof. Dr. Josep Redon, INCLIVA Instituto de Investigación Sanitaria & Universidad de Valencia

181. Prof. Dra. Helena Rifà-Pous, Universitat Oberta de Catalunya

182. Prof. Dr. David Ríos Insua, Real Academia de Ciencias Exactas, Físicas y Naturales

183. Prof. Agustín Riscos Núñez, Universidad de Sevilla

184. Prof. Dr. Gregorio Robles, Universidad Rey Juan Carlos

185. Prof. Aníbal Rodríguez Bernal, Universidad Complutense de Madrid

186. Dr. Pedro S. Rodríguez Hernández, Universidade de Vigo

187. Prof. Dr. Miguel Rodríguez Pérez, Universidade de Vigo

188. Prof. Dra. María del Carmen Romero Ternero, Universidad de Sevilla

189. Prof. Dr. Antoni Rubí Puig, Universitat Pompeu Fabra

190. Prof. Dr. Agustín Ruiz Robledo, Universidad de Granada

191. Dr. Javier Ruiz Soler, Simon Fraser University (Canadá)

192. Prof. Dra. Eva Sáenz Royo, Universidad de Zaragoza

193. Prof. Dr. Manuel Sánchez Angulo, Universidad Miguel Hernández de Elche

194. Prof. Dr. Manuel Sánchez de Diego Fdez. de la Riva, Universidad Complutense de Madrid

195. Prof. Dr. Ángel J. Sánchez Navarro, Universidad Complutense

196. Dr. Javier Sánchez-Monedero. Cardiff University (Gales, Reino Unido)

197. Prof. Dr. José Miguel Santos Espino, Universidad de Las Palmas de Gran Canaria

198. Prof. Dr. Joaquín Sarrión Esteve, Universidad Nacional de Educación a Distancia - UNED

199. Dra. Laura Sebastiá Tarin, Universitat Politècnica de València

200. Prof. Dra. Encarnación Segarra Soriano, Universitat Politècnica de València

201. Prof. Dr. Sergio Segura Rueda, Universidad de Sevilla

202. Dr José Sepúlveda Sanchis, Universidad Politecnica

203. Prof. Dra. Isabel Serrano Maiilo, Universidad Complutense de Madrid.

204. Prof. Dr. Carles Sierra, Instituto de Investigación en Inteligencia Artificial - CSIC

205. Prof. Dr. Javier Sierra Rodríguez, Universidad de Murcia

206. Prof. Dr. Josep Silva Galiana, Universitat Politècnica de València

207. Prof. Dr. Pere Simón Castellano, Universidad Internacional de la Rioja - UNIR

208. Prof. Dr. Enrique Soriano-Salvador, Universidad Rey Juan Carlos

209. Prof. Dr. Luc Steels, Institut de Biologia Evolutiva, UPF-CSIC

210. Prof. Dr. Guillermo Suarez-Tangil, King’s College London (Reino Unido) & Instituto IMDEA Networks

211. Prof. Dra. Sílvia Suñer Lázaro, Universitat Politècnica de Catalunya

212. Prof. Dr. Juan Tapiador, Universidad Carlos III de Madrid

213. Prof. Dr. Marc Tarrés Vives, Universitat de Barcelona

214. Prof. Núria Terribas Sala, Càtedra de Bioètica - Universitat de Vic - Universitat Central de Catalunya

215. Prof. Dra. Carme Torras, Institut de Robòtica i Informàtica Industrial, UPC-CSIC

216. Prof. Dra. Blanca Torrubia Chalmeta, Universitat Oberta de Catalunya

217. Dr. Pablo Trinidad Martín-Arroyo, Universidad de Sevilla

218. Prof. Dra. Carmela Troncoso, École Polytechnique Fédérale de Lausanne (Suiza)

219. Dra. Ana Valdivia, King's College London (Reino Unido)

220. Prof. Dr. Gerardo Valeiras, Universidad de Sevilla

221. Prof. Dr. Narseo Vallina-Rodriguez, Instituto IMDEA Networks

222. Prof. Dr. Antonio Vallecillo, Universidad de Málaga

223. Prof. Dr. Julián Valero Torrijos, Universidad de Murcia

224. Prof. Dr. Juan Manuel Vara Mesa, Universidad Rey Juan Carlos

225. Prof. Dra. Victoria Velasco, Universidad de Granada

226. Prof. Dra. Clara Velasco Rico, Universitat Pompeu Fabra

227. Prof. Dr. José Luis Verdegay, Universidad de Granada

228. Dr. Víctor Vicente Palacios, Universidad de Salamanca

229. Prof. Dr. Germán Vidal, Universitat Politècnica de València

230. Prof. Dra. Mònica Vilasau Solana, Universitat Oberta de Catalunya

231. Prof. Dr. Rafael Villa Caro, Universidad de Sevilla

232. Prof. Dr. Emilio Vivancos, Rubio Universitat Politècnica de València

233. Prof. Dra. Raquel Xalabarder, Universitat Oberta de Catalunya

234. Prof. Dr. Sebastià Xambó Descamps, Universitat Politècnica de Catalunya

235. Dr. Urko Zurutuza, Mondragon Unibertsitatea

<hr>

## Súmate al manifiesto

Si perteneces a la comunidad académica española y quieres sumarte a este manifiesto, comparte por favor tu nombre, apellidos e institucion académica en el siguiente formulario: [https://docs.google.com/forms/d/e/1FAIpQLSd1o_23n55D_IPeqTQmMHPxJTvx6659ALsy4ru4tBq5AQ3Vqg/viewform](https://docs.google.com/forms/d/e/1FAIpQLSd1o_23n55D_IPeqTQmMHPxJTvx6659ALsy4ru4tBq5AQ3Vqg/viewform). 

<style>
h1:nth-child(1) {
  visibility: hidden;
  line-height: 0;
}
</style>
