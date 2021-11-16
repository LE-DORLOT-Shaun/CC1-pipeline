# CC1-pipeline

#1 Création du pipeline de traitement de données avec Terraform
1. Il manque le fichier "destination_s3_bucket.tf" et le fichier "kinesis_datastream.tf".
2. 
3. L'application récupère des fichiers financiers et trie de façon à ne conserver que ceux dans lesquels l'action d'ibm est supérieure à 50.
4. 
5. La partie user_data du fichier ec2.tf sert à lancer des configurations automatisées après le démarrage de l'instance avec des données utilisateurs pour que la machine soit bien paramétrée.
6. L'agent Kinesis est un ensemble de 3 services de gestion de flux des données, de stream. Kinesis permet d'analyser ces flux  


#2 
1. Ingestion : Amazon kinesis data firehorse
2. Stockage : Amazon kinesis data analytics
3. Transformation : Amazon kinesis data stream
4. Exposition : Amazon cloud front


#3
