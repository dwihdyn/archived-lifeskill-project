==================================================== MOVED TO LIFESKILL-FE & LIFESKILL-BE REPOSITORY ====================================================













===== Prep =====

step1 :
`git clone https://github.com/dwihdyn/lifeskill-project.git`

step2 :
backend prep
`conda create -n lifeskill-be python=3.7`
`source activate lifeskill-be`
`pip install -r requirements.txt`
`pip freeze > requirements.txt`

===== Working =====

step1 :
branch out
`git checkout -b whateverFeatureYouAreBuilding`

step2 :
build your feature

step3 :
merge your work (ask mentor if you're not sure about this)
`git merge whateverFeatureYouAreBuilding master`
