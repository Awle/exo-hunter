# What is ExoHunter?

Less than a century ago, consensus was that ours was the only star with planets in the universe, but now we know there are likely billions of them in the Milky Way alone. Currently researchers analyse each star one at a time in an manual fashion so our goal is to reduce this workload by quickly identifying candidate systems in order to correctly discard as many planet-less stars as possible using a Convolutional Neural Network.
Our platform can intake light flux curve data from users and use it to return information about a star system and its likelihood of having exoplanets.

# Data analysis
- Document here the project: exo-hunter
- Description: Project Description
- Data Source: LightKurve
- Type of analysis: CNN

# Install
Clone the project and install it:

```bash
git clone git@github.com:{group}/exo-hunter.git
cd exo-hunter
pip install -r requirements.txt
make clean install test                # install and test
```
