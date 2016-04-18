
Detailed instructions can be found in our [workshop-resources](https://github.com/ContentMine/workshop-resources/tree/master/software-tutorials/getpapers).

To get started and download a set of FullText XML files of OpenAccess papers from EuropePMC just run:

You might get back many thousands of results, you can cancel with Ctrl-C.

```getpapers -q <your query> -o <a folder to save them in> -x```

If you look inside the folder you'll see there are many more folders; each of which contain a fulltext.xml file which is the contents of that paper.

For example if you run `getpapers -q -aardvark  -o aardvark -x` You'll get ca. 110 XML files.
