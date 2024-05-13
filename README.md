
# Generation d'image de stabilité(SDXL)
![001_with_eval](https://github.com/Ulrich75/Hackathon-AI/assets/127865109/b262ba68-b099-43fb-b772-d3f06ce98745)

# Installation:

1. Culne le repo

<pre class="python">
git clone https://github.com/Stability-AI/generative-models.git
</pre>
cd generative-models

2. Mise en place du virtualenv

Cela suppose que vous avez navigué vers le generative-modelsracine après le clonage.

NOTA: Cet essai est soumis à l'essai dans le cadre de python3.10. Pour d'autres versions de python, vous pourriez rencontrer des conflits de version.

PyTorch 2.0

# install required packages from pypi
python3 -m venv .pt2
source .pt2/bin/activate
pip3 install -r requirements/pt2.txt

3. Install sgm

pip3 install .

4. Install sdatapour la formation

pip3 install -e git+https://github.com/Stability-AI/datapipelines.git@main#egg=sdata



