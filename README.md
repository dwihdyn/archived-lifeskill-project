===== Prep =====

step1 :
`git clone https://github.com/dwihdyn/lifeskill-project.git`

step2 :
backend prep

<ul>
  <li>`conda create -n lifeskill-be python=3.7`</li>
  <li>`source activate lifeskill-be`</li>
  <li>`pip install -r requirements.txt`</li>
  <li>`pip freeze > requirements.txt`</li>
</ul>

===== Working =====

step1 :
branch out
`git checkout -b whateverFeatureYouAreBuilding`

step2 :
build your feature

step3 :
merge your work (ask mentor if you're not sure about this)
`git merge whateverFeatureYouAreBuilding master`
