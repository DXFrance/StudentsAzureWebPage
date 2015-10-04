# Tutoriel : première page web dans Microsoft Azure !

Le but de ce tutoriel est de vous permettre, en quelques minutes seulements, de déployer votre première page web dans Microsoft Azure, l'offre de Cloud Computing de Microsoft !

Ce tutoriel est disponible en deux niveaux :

* <a href="#scénario-débutant">Débutant</a>
* <a href="#scénario-avancé">Avancé</a>

En prérequis, vous devez avoir activé votre compte Microsoft Azure pour DreamSpark depuis <a href="https://www.dreamspark.com/Product/Product.aspx?productid=99" target="_blank">cette page</a> ou en suivant les explications fournies dans <a href="https://channel9.msdn.com/Blogs/Students/Microsoft-Azure-pour-DreamSpark" target="_blank">cette vidéo</a>.

### Scénario Débutant

Pour ce scénario, vous n'avez pas à connaître HTML, CSS ou JavaScript, ni même avoir déjà utilisé Microsoft Azure ! Pour déployer votre première page web, il vous suffit de cliquer sur le bouton ci-dessous, et de vous laisser guider !

<a href="https://azuredeploy.net/" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>

Lorsque cela vous est demandé, connectez-vous avec le compte Microsoft sur lequel vous avez activé votre offre Microsoft Azure pour DreamSpark.

Une fois connecté, il vous faut renseigner les informations suivantes :

<img src="http://blogs.microsoft.fr/azure/files/2015/10/Tuto_Students_WebPage_001.png" />

Avec : 

* Directory : laisser la valeur par défault
* Subscription : laisser DreamSpark sélectionné
* Resource Groupe : Create New, pour créer un nouveau groupe de ressource
* Resource Group Name : le nom par défaut ou le nom que vous souhaitez donner au groupe (ex : MaPageWeb-Groupe)
* Site Name : le nom de votre site Microsoft Azure. C'est le nom sur lequel votre site sera accessible à l'adresse : http://nom_choisi.azurewebsites.net
* Site Location : le data center dans lequel vous souhaitez créer le site. Vous pouvez choisir West Europe, si vous êtes en France
* Sku : laisser "Free" pour créer un site web gratuit

Cliquez ensuite sur le bouton Next et patientez pendant la validation des paramètres que vous avez saisis :

<img src="http://blogs.microsoft.fr/azure/files/2015/10/Tuto_Students_WebPage_002.png" />

Cliquez ensuite sur le bouton Deploy et patientez pendant la création de votre site web dans Microsoft Azure !

<img src="http://blogs.microsoft.fr/azure/files/2015/10/Tuto_Students_WebPage_003.png" />

Une fois créé, il ne vous reste plus qu'à cliquer sur l'adresse affichée pour visualiser votre première page web !

<img src="http://blogs.microsoft.fr/azure/files/2015/10/Tuto_Students_WebPage_004.png" />

Si vous avez envie de personnaliser cette page pour apprendre à manipuler HTML / CSS et JavaScript, vous pouvez passer au scénario avancé.
Un cours sur la création de site web est également disponible sur <a href="https://www.microsoftvirtualacademy.com/fr-fr/training-courses/crer-un-site-web-quand-on-est-un-vrai-dbutant-12670" target="_blank">Microsoft Virtual Academy</a>.

### Scénario avancé

Dans ce scénario un peu plus avancé, nous vous proposons de réaliser un "fork" du projet GitHub afin de pouvoir modifier le code source de la page web que vous allez déployer et ainsi la personnaliser !

Pour commencer, vous devez posséder un compte sur GitHub. Il est possible d'en créer un en vous rendant sur <a href="https://github.com/join" target="_blank">cette page</a>.
Une fois connecté sur GitHub, retournez sur <a href="https://github.com/DXFrance/StudentsAzureWebPage" target="_blank">le projet de page web</a>, cliquez sur le bouton Fork, en haut à droite de la page :

<img src="http://blogs.microsoft.fr/azure/files/2015/10/Tuto_Students_WebPage_005.png" />

Cela a pour effet de dupliquer le projet dans votre compte GitHub, afin de vous permettre de le modifier librement :

<img src="http://blogs.microsoft.fr/azure/files/2015/10/Tuto_Students_WebPage_006.png" />

Pour modifier la page web, deux solutions s'offrent à vous. La première est d'utiliser l'édtieur en ligne de GitHub. Pour cela, cliquez sur le fichier index.html dans la liste des fichiers, puis cliquez sur le bouton éditer, représenté par un crayon :

<img src="http://blogs.microsoft.fr/azure/files/2015/10/Tuto_Students_WebPage_007.png" />

Vous pouvez alors modifier librement le HTML de la page, puis l'enregistrer. Une fois toutes vos modifications effectées, il vous suffit de cliquer sur le bouton Deploy to Azure situé dans <a href="#scénario-débutant">le scénario Débutant</a> et de suivre les instructions pour déployer votre page web !

Si vous souhaitez aller plus loin dans la personnalisation, vous pouvez cloner votre nouveau repository sur votre ordinateur, effectuer les modifications que vous souhaitez à l'aide d'un éditeur de code tel que <a href="https://code.visualstudio.com/" target="_blank">Visual Studio Code</a>, par exemple.