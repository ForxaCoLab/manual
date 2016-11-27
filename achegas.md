# As achegas
Seguramente estás pensando que todo isto de Git é moi complexo e que non ten sentido usar a forxa para xestionar a documentación se podemos usar unha ferramenta convencional para almacenar arquivos na nube como Dropbox, Owncloud ou Google Drive. Pois ben, a potencia de Git baséase na capacidade de aceptar e integrar contribucións dun xeito transparente e eficaz, podendo identificar a autoría de cada unha das achegas e ter un control total do estado do repositorio, en cada unha das súas ramas.

## Tipos de achegas

### Se teño acceso ao repositorio

Se o teu usuario ten acceso de escritura no repositorio, ben porque eres a propietaria ou ben porque asignáronte o rol de colaboradora, podes facer as achegas directamente editando o arquivo que queres modificar:

![](http://forxa.colab.coruna.gal/Co-Lab/manual/raw/master/imaxes/editar.png)

Unha vez remates a edición deberás describir os cambios que realizaches para o rexistro de achegas e así poder identificar cal é o alcance dos cambios realizados por cada usuario. Se fas as achegas na interfaz web da forxa só poderás facer un cambio de vez, pero se usas a liña de comandos poderás incluir moitos cambios nunha mesma achega e pode ser complicado identificar os cambios concretos de cada achega. É por iso que esta descripción dos cambios terá que ser o máis precisa posible. Por exemplo: "engadida descripción ao arquivo XXX"

![](http://forxa.colab.coruna.gal/Co-Lab/manual/raw/master/imaxes/achegas.png)

### Se non teño acceso ao repositorio

Se non tes acceso ao repositorio deberás en primeiro lugar **[clonar](http://forxa.colab.coruna.gal/Co-Lab/manual/src/master/clonar.md)** o repositorio para crear un repositorio idéntico sobre o que ti teñas dereitos de acceso. 

Unha vez que teñas unha copia (normalmente falamos de **fork**) idéntica na que podes facer achegas procede a facer os cambios que estimes necesarios.

Unha vez que teñas unha copia do repositorio cos cambios que estimaches necesarios, ou as achegas oportunas como melloras, traduccións, documentación engadida, etc poderás solicitar a inclusión dos teus cambios no proxecto orixinal executando una solicitude de [**pull request**](http://forxa.colab.coruna.gal/Co-Lab/manual/src/master/pull_request.md).
