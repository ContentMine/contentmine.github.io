
If you're only working on papers form EuropePMC downloaded with getpapers you might not need to run norma seperately. See the ami instructions below.

Detailed instructions can be found in our [workshop-resources](https://github.com/ContentMine/workshop-resources/tree/master/software-tutorials/norma)

To convert the papers into a form we can mine use Norma.

```norma --project <your folder of papers> -i fulltext.xml -o scholarly.html --transform nlm2html```