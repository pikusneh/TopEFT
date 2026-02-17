# TopEFT
Cards for gridpack generation in MadGraph

## Naming
 

## Creation of reweight card including decay:

python3 make_reweight_card.py --couplings 2 ctWRe 1 ctBRe 1 --filename reweight_card.dat


## For Gridpack production in CMSSW

In gridpack_generation.sh script, change 'wget --no-check-certificate https://cms-project-generators.web.cern.ch/cms-project-generators/$model'
to 'wget --no-check-certificate https://chatterj.web.cern.ch/chatterj/models/$model'

