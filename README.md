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

9. Dr. Bartomeu Alorda Ladaria, Universitat de les Illes Balears

10. Prof. Dra. María Alpuente, Universidad Politécnica de Valencia

11. Prof. Dr. Juan Antonio Álvarez García, Universidad de Sevilla

12. Dr. Pablo Aragón, Universitat Pompeu Fabra

13. Prof. Dra. Mª Aránzazu Moretón Toquero, Universidad de Valladolid

14. Javier Armentia Fructuoso, Planetario de Pamplona

15. Dr. David Arroyo Guardeño, Instituto de Tecnologías Físicas y de la Información - CSIC

16. Prof. Dr. David Atienza Alonso, École Polytechnique Fédérale de Lausanne (Suiza)

17. Prof. Dra. Nieves Atienza Martínez, Universidad de Sevilla

18. Prof. Dra. Mónica Arenas Ramiro, Universidad de Alcalá 

19. Prof. Dr. Txetxu Ausín, Instituto de Filosofía - CSIC

20. Prof. Dr. José L. Aznarte, Universidad Nacional de Educación a Distancia - UNED

21. Prof. Dr. Ricardo Baeza-Yates, Northeastern University - Silicon Valley (Estados Unidos) & Universitat Pompeu Fabra

22. Prof. Dra. Beatriz Barros Blanco, Universidad de Málaga

23. Prof. Dr. Santiago Bello Paredes, Universidad de Burgos

24. Prof. Dra. Marta Beltrán Pardo, Universidad Rey Juan Carlos

25. Prof. Dr. Fernando Benito Picazo, Universidad de Málaga

26. Dra. Juani Bermejo-Vega, Universidad de Granada

27. Prof. Dra. María Bermudez-Edo, Universidad de Granada

28. Prof. Dr. Josep Blat, Universitat Pompeu Fabra

29. Prof. Dr. Federico Botella, Universidad Miguel Hernández de Elche

30. Prof. Dr. Vicent Botti, Universidad Politécnica de Valencia

31. Prof. Dr. Andrés Boix Palop, Universitat de València

32. Prof. Uwe Brauer, Universidad Complutense de Madrid

33. Dr. Vanni Brusadin, Universitat de Barcelona 

34. Prof. Dr. Jacques Bulchand Gidumal, Universidad de Las Palmas de Gran Canaria

35. Prof. Dr. Antonio J. Caamaño, Universidad Rey Juan Carlos

36. Prof. Dr. Juan Caballero, Instituto IMDEA Software

37. Prof. Dr. Jordi Cabot, Universitat Oberta de Catalunya

38. Prof. Dr. Stefano Cabras, Universidad Carlos III de Madrid 

39. Prof. Dr. Daniel Cagigas Muñiz, Universidad de Sevilla

40. Prof. Dr. Patrici Calvo, Universitat Jaume I

41. Dr. Cédric M. Campos, Universidad Rey Juan Carlos

42. Prof. Dr. Javier Campos Laclaustra, Universidad de Zaragoza

43. Prof. Dr. Antonio Cañabate Carmona, Universitat Politècnica de Catalunya

44. Prof. Dr. Josep Cañabate Pérez, Universitat Autònoma de Barcelona

45. Prof. Dra. María Jose Carazo Liébana, Universidad de Jaén

46. Prof. Dr. Gabriel Cardona Juanals, Universitat de les Illes Balears

47. Prof. Dra. Maria Casado, Observatori de Bioètica i Dret, Càtedra Unesco de Bioètica, Universitat de Barcelona

48. Dr. Daniel Cascado Caballero, Universidad de Sevilla

49. Prof. Dr. Ignacio Cascos Fernández, Universidad Carlos III de Madrid

50. Prof. Dr. Ignacio Cascudo Pueyo, Instituto IMDEA Software

51. Prof. Dra. Cecilia Castaño Collado, Universidad Complutense de Madrid

52. Prof. Dr. Jorge Castellanos Claramunt. Universidad de Valencia

53. Prof. Dr. Carlos Castillo, Universitat Pompeu Fabra

54. Prof. Dra. Eva M. Castro Barbero, Universidad Rey Juan Carlos

55. Prof. Dr. Manuel Carro, Instituto IMDEA Software & Universidad Politécnica de Madrid

56. Prof. Dra. María Eugenia Castellanos Nueda, Universidad Rey Juan Carlos.

57. Dra. Rosa Catalán Campos, Universitat de Barcelona

58. Prof. Dr. Agustí Cerrillo i Martínez, Universitat Oberta de Catalunya

59. Prof. Dr. Oscar Corcho, Universidad Politécnica de Madrid

60. Dr. Adrián Cordón López, Hospital Regional Universitario de Málaga

61. Prof. Dr. Alberto Corsín Jiménez, Consejo Superior de Investigaciones Científicas - CSIC

62. Dra. Loreto Corredoira y Alfonso, Universidad Complutense de Madrid

63. Prof. Dr. Ulises Cortés, Universitat Politècnica de Catalunya

64. Prof. Dr. Enrique Costa Montenegro, Universidade de Vigo

65. Prof. Dr. Lorenzo Cotino Hueso, Universidad de Valencia

66. Dr. José M. Cotos Yáñez, Centro de Investigación en Tecnoloxías Intelixentes - Universidade de Santiago de Compostela

67. Prof. Dr. Félix Crespo Hellín, Universitat de Valencia

68. Prof. Dr. J. Ignacio Criado, Universidad Autónoma de Madrid

69. Prof. Dr. Iñigo Cuiñas, Universidade de Vigo

70. Prof. Dra. Vanesa Daza, Universitat Pompeu Fabra

71. Prof. Dra. Itziar de Lecuona, Observatori de Bioètica i Dret, Càtedra Unesco de Bioètica, Universitat de Barcelona

72. Prof. Dra. Claudia Díaz, KU Leuven (Bélgica)

73. Prof. Dra. Paloma Díaz Pérez, Universidad Carlos III de Madrid

74. Prof. Dr. Juan Manuel Dodero Beardo, Universidad de Cádiz

75. Prof. Dr.. Antonio Domínguez Vila, Universidad de La Laguna

76. Prof. Dr. Josep Domingo-Ferrer, Universitat Rovira i Virgili

77. Prof. Dr. Juan Carlos Dueñas López, Universidad Politécnica de Madrid

78. Prof. Dr. Guillermo Escobar Roca, Universidad de Alcalá

79. Prof Dr. Salvador España Boquera, Universitat Politècnica de València

80. Prof. Dr. Pere Fabra Abat, Universitat Oberta de Catalunya

81. Prof. Dr. Manuel José Fernández Iglesias, Universidade de Vigo 

82. Prof. Dr. Jesus Fernandez-Villaverde, University of Pennsylvania

83. Prof. Dra. Antonia Ferrer Sapena, Universitat Politècnica de València

84. Prof. Dr. Dario Fiore, Instituto IMDEA Software

85. Prof. Dr. José Fortes Gálvez, Universidad de Las Palmas de Gran Canaria

86. Prof. Dr. José María de Fuentes , Universidad Carlos III de Madrid

87. Prof. Dr. Ramón Galindo Caldés, Universitat Oberta de Catalunya

88. Prof. Dr. Domingo Gallardo López, Universidad de Alicante

89. Prof. Dr. Eduardo Gamero Casado, Universidad Pablo de Olavide

90. Almudena García, Universidad de Huelva

91. Helena García Cebollada, Instituto de Biocomputación y Física de Sistemas Complejos - Universidad de Zaragoza

92. Prof. Dra. María del Rosario García Mahamut - Universitat Jaume I

93. Dr. Pablo Garcia Molina, Georgetown University (Estados Unidos)

94. Prof. Dr. Joaquín García-Alfaro, Institut Polytechnique de Paris (Francia) & Carleton University (Canadá)

95. Prof. Dr. Hector Geffner, Universitat Pompeu Fabra

96. Dr. Xavier Gironès García, Fundación Universitaria del Bages

97. Prof. Dr. Vicenç Gómez, Universitat Pompeu Fabra

98. Prof. Dr. Juan Antonio Gómez Pulido, Universidad de Extremadura

99. Sergio Gómez Bachiller, Universidad de Córdoba

100. Dr. David Gómez-Ullate Oteiza, Universidad de Cádiz

101. Prof. Dr. Jesús M. González Barahona, Universidad Rey Juan Carlos

102. Prof. Dr. Luis Miguel González de la Garza, Universidad Nacional de Educación a Distancia - UNED

103. Prof. Dra. Gloria González Fuster, Vrije Universiteit Brussel (Bélgica)

104. Prof. Dra. Lorena González Manzano, Universidad Carlos III de Madrid

105. Prof. Dra. Maria Isabel González Vasco, Universidad Rey Juan Carlos

106. Prof. Dra. Alessandra Gorla, Instituto IMDEA Software

107. Prof. Dr. Juan José Guardia Hernández, Universitat Internacional de Catalunya

108. Dr, Ariel Guersenzvaig, ELISAVA Escuela de Diseño e Ingeniería de Barcelona

109. Prof. Benjamín Guix Melcior, Universidad de Barcelona

110. Prof. Dr. Juan Carlos Hernández, Universidad de Navarra

111. Prof. Dr. Jose Hernandez-Orallo, Universitat Politécnica de Valencia

112. Prof. Dr. Antonio Hernández Pérez, Universidad Carlos III de Madrid

113. Prof. Dr. Daniel Innerarity, Universidad del País Vasco & European University Institute of Florence

114. Hugo Jiménez Hernández, Barcelona Supercomputing Center

115. Prof. Dr. Fco. Javier Hormigo Aguilar, Universidad de Málaga

116. Prof. Dr. Fco. Javier Jiménez Leube, Universidad Politécnica de Madrid

117. Prof. Dr. Andrés Jiménez Ramírez, Universidad de Sevilla

118. Dr. Daniel Jiménez-González, Universitat Politècnica de Catalunya

119. Dr. Marc Juarez, University of Southern California (Estados Unidos)

120. Prof. Dr. Vicente Julian, Universitat Politècnica de València

121. Prof. Dr. Pedro Larrañaga, Universidad Politécnica de Madrid

122. Prof. Dr. Ramon López de Mántaras, Instituto de Investigación en Inteligencia Artificial - CSIC & Western Sydney University (Australia)

123. Dr. Álvaro López García, Consejo Superior de Investigaciones Científicas - CSIC

124. Prof. Dra. Maite López Sánchez, Universidad de Barcelona & Instituto de Investigación en Inteligencia Artificial - CSIC

125. Dr. Manuel López-Ibáñez, Universidad de Málaga

126. Dr. Jorge Lozano Miralles, Universidad de Jaén

127. Dr. Miguel Luengo Oroz , Global Pulse ONU (Estados Unidos)

128. Prof. Dr. Javier Macías Guarasa, Universidad de Alcalá

129. Dr. Jaume Manero Font, Universitat Politécnica de Catalunya

130. Dr. David Martín de Diego, Instituto de Ciencias Matemáticas - CSIC

131. Dr. Cristian Martín Fernández  Universidad de Málaga

132. Prof. Dr. Sebastià Martín Molleví, Universitat Politècnica de Catalunya

133. Dr. José Luis Martínez Martínez, Universidad de Castilla-La Mancha

134. Prof Dra. Alejandra Martínez Monés, Universidad de Valladolid

135. Prof. Dra. Pastora Martínez Samper, Universitat Oberta de Catalunya

136. Prof. Dr. David Martínez Zorrilla. Universitat Oberta de Catalunya

137. Prof. Manuel Medina Llinàs, Universitat Politècnica de Catalunya

138. Prof. Dra. Ernestina Menasalvas Ruiz, Universidad Politécnica de Madrid

139. Dr. Juan Julián Merelo Guervós, Universidad de Granada

140. Javier Miranzo Díaz, Universitat Oberta de Catalunya 

141. Prof. Dr. Artemio Mojón Ojea, Universidade de Vigo

142. Dr. José Molina Molina, Consejo de la Transparencia de la Región de Murcia & Universidad de Murcia

143. Dr. José F. Morales, Instituto IMDEA Software

144. Prof. Dr. Yamir Moreno, Universidad de Zaragoza

145. Prof. Dra. Mª Aránzazu Moretón Toquero, Universidad de Valladolid

146. Dra. Melania Moscoso, Instituto de Filosofía - CSIC

147. Dr. Alfonso Muñoz, Universidad Politécnica de Madrid

148. Prof. Dr. Vicente J. Navarro Marchante, Universidad La Laguna

149. Prof. Dra. Susana Navas Navarro. Universitat Autònoma de Barcelona

150. Fernando Orejas, Universitat Politècnica de Catalunya

151. Prof. Dr. Juan Luis Paniagua Soto, Universidad Complutense de Madrid

152. Dr. José Antonio Parejo Maestre, Universidad de Sevilla

153. Prof. Dr. José Parra-Moyano, Copenhagen Business School (Dinamarca)

154. Prof. Dra. Encarnación Pastor Martín, Universidad Politécnica de Madrid 

155. Prof. Dr. Sergio Pastrana Portillo, Universidad Carlos III de Madrid & University of Cambridge (Reino Unido)

156. Prof. Dr. Miquel Peguera, Universitat Oberta de Catalunya 

157. Prof. Dr. Josep Perelló, Universitat de Barcelona

158. Prof. Dr. Ángel Pérez del Pozo, Universidad Rey Juan Carlos

159. Prof. Dr. Fernando Pérez González, Universidade de Vigo

160. Prof. Dr. Ernesto Pimentel, Universidad de Málaga

161. Dr. Manuel Poch, Universitat de Girona

162. Prof. Dr. Juli Ponce Solé, Universitat de Barcelona

163. Dr. Manuel Portela, Universitat Pompeu Fabra

164. Dr. José Ra. Portillo Fernández, Universidad de Sevilla

165. Dr. Alejandro Pozas Kerstjens, Universidad Complutense de Madrid

166. Prof. Dr. Joan Manuel del Pozo Álvarez, Universitat de Girona

167. Dr. Miguel Ángel Presno Linera, Universidad de Oviedo

168. Prof. Dra. Francisca Ramón Fernández, Universitat Politècnica de València

169. Dra. Leonor Rams Ramos, Universidad Rey Juan Carlos 

170. Prof. Dr. Miguel Rebollo Pedruelo. Universitat Politècnica de València

171. Prof. Dr. Josep Redon, INCLIVA Instituto de Investigación Sanitaria & Universidad de Valencia

172. Prof. Dra. Helena Rifà-Pous, Universitat Oberta de Catalunya

173. Prof. Dr. David Ríos Insua, Real Academia de Ciencias Exactas, Físicas y Naturales

174. Prof. Agustín Riscos Núñez, Universidad de Sevilla

175. Prof. Dr. Gregorio Robles, Universidad Rey Juan Carlos

176. Prof. Aníbal Rodríguez Bernal, Universidad Complutense de Madrid

177. Dr. Pedro S. Rodríguez Hernández, Universidade de Vigo

178. Prof. Dr. Miguel Rodríguez Pérez, Universidade de Vigo

179. Prof. Dra. María del Carmen Romero Ternero, Universidad de Sevilla

180. Prof. Dr. Antoni Rubí Puig, Universitat Pompeu Fabra

181. Prof. Dr. Agustín Ruiz Robledo, Universidad de Granada

182. Dr. Javier Ruiz Soler, Simon Fraser University (Canadá)

183. Prof. Dra. Eva Sáenz Royo, Universidad de Zaragoza

184. Prof. Dr. Manuel Sánchez Angulo, Universidad Miguel Hernández de Elche

185. Prof. Dr. Manuel Sánchez de Diego Fdez. de la Riva, Universidad Complutense de Madrid

186. Prof. Dr. Ángel J. Sánchez Navarro, Universidad Complutense

187. Dr. Javier Sánchez-Monedero. Cardiff University (Gales, Reino Unido)

188. Prof. Dr. José Miguel Santos Espino, Universidad de Las Palmas de Gran Canaria

189. Prof. Dr. Joaquín Sarrión Esteve, Universidad Nacional de Educación a Distancia - UNED

190. Dra. Laura Sebastiá Tarin, Universitat Politècnica de València

191. Prof. Dra. Encarnación Segarra Soriano, Universitat Politècnica de València

192. Prof. Dr. Sergio Segura Rueda, Universidad de Sevilla

193. Prof. Dra. Isabel Serrano Maiilo, Universidad Complutense de Madrid.

194. Prof. Dr. Carles Sierra, Instituto de Investigación en Inteligencia Artificial - CSIC

195. Prof. Dr. Javier Sierra Rodríguez, Universidad de Murcia

196. Prof. Dr. Josep Silva Galiana, Universitat Politècnica de València

197. Prof. Dr. Pere Simón Castellano, Universidad Internacional de la Rioja - UNIR

198. Prof. Dr. Enrique Soriano-Salvador, Universidad Rey Juan Carlos

199. Prof. Dr. Luc Steels, Institut de Biologia Evolutiva, UPF-CSIC

200. Prof. Dr. Guillermo Suarez-Tangil, King’s College London (Reino Unido) & Instituto IMDEA Networks

201. Prof. Dra. Sílvia Suñer Lázaro, Universitat Politècnica de Catalunya

202. Prof. Dr. Juan Tapiador, Universidad Carlos III de Madrid

203. Prof. Dr. Marc Tarrés Vives, Universitat de Barcelona

204. Prof. Núria Terribas Sala, Càtedra de Bioètica - Universitat de Vic - Universitat Central de Catalunya

205. Prof. Dra. Carme Torras, Institut de Robòtica i Informàtica Industrial, UPC-CSIC

206. Prof. Dra. Blanca Torrubia Chalmeta, Universitat Oberta de Catalunya

207. Dr. Pablo Trinidad Martín-Arroyo, Universidad de Sevilla

208. Prof. Dra. Carmela Troncoso, École Polytechnique Fédérale de Lausanne (Suiza)

209. Dra. Ana Valdivia, King's College London (Reino Unido)

210. Prof. Dr. Gerardo Valeiras, Universidad de Sevilla

211. Prof. Dr. Narseo Vallina-Rodriguez, Instituto IMDEA Networks

212. Prof. Dr. Antonio Vallecillo, Universidad de Málaga

213. Prof. Dr. Julián Valero Torrijos, Universidad de Murcia

214. Prof. Dr. Juan Manuel Vara Mesa, Universidad Rey Juan Carlos

215. Prof. Dra. Victoria Velasco, Universidad de Granada

216. Prof. Dra. Clara Velasco Rico, Universitat Pompeu Fabra

217. Prof. Dr. José Luis Verdegay, Universidad de Granada

218. Dr. Víctor Vicente Palacios, Universidad de Salamanca

219. Prof. Dr. Germán Vidal, Universitat Politècnica de València

220. Prof. Dra. Mònica Vilasau Solana, Universitat Oberta de Catalunya

221. Prof. Dr. Rafael Villa Caro, Universidad de Sevilla

222. Prof. Dr. Emilio Vivancos, Rubio Universitat Politècnica de València

223. Prof. Dra. Raquel Xalabarder, Universitat Oberta de Catalunya

224. Prof. Dr. Sebastià Xambó Descamps, Universitat Politècnica de Catalunya

225. Dr. Urko Zurutuza, Mondragon Unibertsitatea

<hr>

## Súmate al manifiesto

Si perteneces a la comunidad académica española y quieres sumarte a este manifiesto, comparte por favor tu nombre, apellidos e institucion académica en el siguiente formulario: [https://docs.google.com/forms/d/e/1FAIpQLSd1o_23n55D_IPeqTQmMHPxJTvx6659ALsy4ru4tBq5AQ3Vqg/viewform](https://docs.google.com/forms/d/e/1FAIpQLSd1o_23n55D_IPeqTQmMHPxJTvx6659ALsy4ru4tBq5AQ3Vqg/viewform). 

<style>
h1:nth-child(1) {
  visibility: hidden;
  line-height: 0;
}
</style>
