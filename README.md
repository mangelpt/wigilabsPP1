
# wigilabsPP1
evaluation wigilabs
=======
# Evaluación de conocimientos
El objetivo de esta prueba es evaluar las capacidades de los candidatos para resolver problemas que se presentan en el desarrollo de una aplicación.   
   
La prueba consiste en eliminar los **"Warning"** que se presentan en los tests unitarios del proyecto.  
   
El candidato tiene la libertad de hacer las modificaciones que vea convenientes para resolver el problema, y verificar que el proyecto siga funcionando al finalizar sus cambios.   
   
El candidato debe mandar el link del repositorio donde resolvio la evaluación.   
   
El tiempo utilizado para resolver la evaluación será tambien parte de la calificación.
   
   
-----------------------------------------------------------------------------

## Getting started

First, ensure that you have [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [NPM](https://www.npmjs.com/get-npm) installed. If you're unsure whether you have one or both of them installed, run the following command(s) (If you have them installed these commands will return a version number, if not, the commands won't be recognized):

```bash
git --version
npm -v
```

Next, install the [NR1 CLI](https://one.newrelic.com/launcher/developer-center.launcher) by going to [this link](https://one.newrelic.com/launcher/developer-center.launcher) and following the instructions (5 minutes or less) to install and setup your New Relic development environment.

Next, to clone this repository and run the code locally against your New Relic data, execute the following command:

```bash
nr1 nerdpack:clone -r https://github.com/GlobalsoftWigilabs/pp1.5.git
cd pp1.5
nr1 nerdpack:uuid -gf
nr1 nerdpack:serve
```

Visit [https://one.newrelic.com/?nerdpacks=local](https://one.newrelic.com/?nerdpacks=local), navigate to the Nerdpack, and test it.

