# WikiTest

# Meilleurs pratiques




### Documentation d’aide utilisateur
**Besoins :**
- Facile à maintenir
- Version control
- Accessible à l’extérieur du REOCC?
- Recherche
- Exportable PDF,doc etc?
- Localisation
- Hosted or local ??
- Le créateur de la documentation doit être autonome.

**Solutions :**
- Wiki custom
- Word/Sharepoint
- Wiki dans SharePoint (pas accessible du web??)
- Solutions open source
- Outils commerical
    - [Robo Help $$](https://www.adobe.com/ca/products/robohelp.html)
    - [Help and manual $](https://www.helpandmanual.com/products_hm_overview.html)
    - [Click help $$$](https://clickhelp.co/online-documentation-tool/)
- Site web fait maison


### HAT (Help Authoring TOOLS)
(list) https://www.g2crowd.com/categories/help-authoring-tool-hat

**READ THE DOCS**
https://docs.readthedocs.io/en/latest/getting_started.html#in-markdown

Markdown doesn’t support a lot of the features of Sphinx, like inline markup and directives. However, it works for basic prose content. reStructuredText is the preferred format for technical documentation, please read this blog post for motivation.

Ex: Doc pickles http://docs.picklesdoc.com/en/latest/IntegratingTestResultsFromSpecRun/ 



### Documentation interne
Le point d’entrée d’un projet est le fichier readme.md

“provides basic information about your code or project, how to build or invoke it (if executable), and license or copyright details.” 
https://visualstudiomagazine.com/articles/2017/02/21/vs-dotnet-code-documentation-tools-roundup.aspx


https://github.com/jehna/readme-best-practices
https://github.com/noffle/art-of-readme



Mark Down 
+ S’intègre bien dans Visual studio dans le Dashboard TFS et sur les sites come GitHub.

- Le dashboard the TFS ne semble pas se mettre à jour même si on pointe directement sur un Document .md dans TFS.
- Plus ou moins lisible si le markdown n’est pas interprété.
- Plus difficile à imprimer
..