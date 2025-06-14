# BMP2PAS
Cette commande, écrit en Pascal (Turbo Pascal ou Free Pascal), permet de convertir une image BitMap (.BMP) en fichier de code source Pascal.

<h3>Syntaxe</h3>

BMP2PAS [option] [fichier]

<h3>Paramètres</h3>

<table>
  <tr>
    <th>Nom</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><i>fichier</i>
    <td>Ce paramètre permet d'indiquer le nom du fichier .BMP</td>
  </tr>
  <tr>
    <td><b>/CROP</b>:<i>x1</i>,<i>y1</i>,<i>x2</i>,<i>y2</i></td> 
    <td>Ce paramètre permet de récupérer seulement une partie de l'image.</td>
  </tr>
  <tr>
    <td><b>--help</b></td>
    <td>Ce paramètre permet d'afficher l'aide de cette commande.</td>
  </tr>
  <tr>
    <td><b>--version</b></td>
    <td>Ce paramètre permet de demander la version de la commande.</td>
  </tr>
</table>


<h2>Quoi de neuf</h2>

<h4>Verion 1.1</h4>
<ul>
  <li>Ajout des paramètres /CROP permettant d'exporter seulement une partie de l'image dans un fichier de code source Pascal.</li>
  <li>Ajout du paramètre --version afin de fournir la version de la commande.</li>
</ul>

<h4>Verion 1.0</h4>
<ul>
  <li>Première version</li>
</ul>

<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> BMP2PAS.PAS</pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> BMP2PAS.PAS</pre>
	
<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/BMP2PAS/blob/main/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/BMP2PAS/blob/main/LICENSE">MIT</a>.</li>
</ul>

