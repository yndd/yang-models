

pyang yndd/models/yndd-system/yndd-system.yang -f tree

cp yndd/models/*/*.yang combined 
pyang combined/*.yang -f tree