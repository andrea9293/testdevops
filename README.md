# Salesforce DX Project: DEV OPS CENTER

# INSTALLAZIONE DEVOPS CENTER
https://help.salesforce.com/s/articleView?id=sf.devops_center_setup_install.htm&type=5
non c'è rollback degli item

non c'è gestione hotfix quindi un item hotfix si deve fare obbligatoriamente tutta la catena. il problema è che una volta arrivato in uat (o comunque nello stage building) non si può avanzare un solo item

quando si vogliono veriricare le modifiche in WI senza collegare l'env si deve cliccare su change... (molto poco intuitivo)

# COMANDI SCRATCH
posizionarsi già sulla devhub
sf org create scratch --edition developer --alias DevOpstest_DEV

sf org generate password --target-org username or alias

DevOpstest_DEVENV
test-vt0aasuta7mz@example.com
Yqqdbsz4cb]ns

DevOpstest_DEV
test-jjoz8ieb6cnm@example.com
y-uD7zrkiomko

DevOpstest_UAT
test-ddr3ksubaofl@example.com
o4ih!hzvyRngr