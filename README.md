
# Generation d'image de stabilité(SDXL)
![001_with_eval](https://github.com/Ulrich75/Hackathon-AI/assets/127865109/b262ba68-b099-43fb-b772-d3f06ce98745)

# Installation:

1. Culne le repo

<pre class="python">
git clone https://github.com/Stability-AI/generative-models.git
cd generative-models
</pre>


2. Mise en place du virtualenv

Cela suppose que vous avez navigué vers le generative-modelsracine après le clonage.

NOTA: Cet essai est soumis à l'essai dans le cadre de python3.10. Pour d'autres versions de python, vous pourriez rencontrer des conflits de version.

PyTorch 2.0

<pre class="python">
# install required packages from pypi
python3 -m venv .pt2
source .pt2/bin/activate
pip3 install -r requirements/pt2.txt
</pre>


3. Install sgm

<pre class="python">
pip3 install .
</pre>

4. Install sdatapour la formation

<pre class="python">
pip3 install -e git+https://github.com/Stability-AI/datapipelines.git@main#egg=sdata
</pre>

![01](https://github.com/Ulrich75/Hackathon-AI/assets/127865109/4c9b4353-8259-4e31-a795-037e739f0728)



# Utilisations
# Utilisation directe

Le modèle est destiné uniquement à la recherche. Les domaines de recherche et les tâches possibles comprennent:

    Génération d'œuvres d'art et utilisation dans le design et d'autres processus artistiques.
    Applications dans les outils éducatifs ou créatifs.
    Recherche sur les modèles générateurs.
    Déploiement sûr de modèles susceptibles de générer des contenus préjudiciables.
    Probition et compréhension des limites et des biais des modèles génératifs.

# Les utilisations exclues sont décrites ci-après.
# Utilisation hors de la portée du champ de la consommation

Le modèle n'a pas été formé pour être des représentations factuelles ou réelles de personnes ou d'événements, et par conséquent, l'utilisation du modèle pour générer un tel contenu est hors de portée pour les capacités de ce modèle.

#Limites et préjugés
#Limites

    Le modèle n'obt Séance pas de photoréalisme parfait
    Le modèle ne peut pas rendre le texte lisible
    Le modèle est en difficulté avec des tâches plus difficiles qui impliquent la compositionnalité, comme le rendu d'une image correspondant à « un cube rouge au-dessus d'une sphère bleue ».
    Les visages et les personnes en général ne peuvent pas être correctement générés.
    La partie auto-codante du modèle est perdant.

# Les préjugés

Si les capacités des modèles de génération d'images sont impressionnantes, elles peuvent également renforcer ou exacerber les préjugés sociaux.


