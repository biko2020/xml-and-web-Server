# xml-and-web-Server
# Projet Technologie XML et Web Services 

# On souhaite créer une application qui permet de gérer des relevés de comptes bancaires. Les données 
# sont stockées dans des fichiers XML dont le format est le suivant :
# <?xml version="1.0" encoding="UTF-8"?> 
# <releve RIB="011112222333344445555666"> 
# <dateReleve>2021-11-10</dateReleve> 
#  <solde>14500</solde> 
#  <operations dateDebut="2021-01-01" dateFin="2021-01-30"> 
#  <operation type="CREDIT" date="2021-01-01" montant="9000" description="Vers Espèce"></operation> 
#  <operation type="DEBIT" date="2021-01-11" montant="3400" desciption="Chèque Guichet"></operation> 
#  <operation type="DEBIT" date="2021-01-15" montant="120" desciption="Prélèvement Assurence"></operation> 
#  <operation type="CREDIT" date="2021-01-25" montant="70000" desciption="Virement .."></operation> 
#  </operations> 
# </releve> 
# Travail demandé : 
# A. Partie Technologie XML : 
# 1. Elaborer la structure graphique de l’arbre XML
# 2. Créer un DTD qui permet de déclarer la structure de ce document XML et créer un 
# exemple de document XML valide par ce DTD
# 3. Créer un schéma XML qui permet de déclarer la structure de ce document XML et créer 
# un exemple de document XML valide par ce schéma XML
# 4. Créer une feuille de style XSL qui permet d’afficher les toutes les données de ce document 
# XML au format HTML en affichant le total des opérations de débit et le total des 
# opérations de crédit.
# 5. Créer une feuille de style XSL qui permet d’afficher au format HTML les opérations de type 
# CREDIT d’un relevé bancaire.
# B. Partie Mapping Objet XML avec Jax Binding : 
# 1. Créer une classe Java représentant une « Operation »
# 2. Créer une classe représentant un « Releve » contenant une liste d’opérations
# 3. Créer une application Java qui permet de créer un Objet Releve avec quelques opérations 
# et de sérialiser ces données dans un fichier XML.
# 4. Créer une application Java qui permet de lire et d’afficher les données du relevé du fichier 
XML.
# 5. Créer une application Java qui permet de générer le Schéma XML représentant la 
# structure d’un relevé.
# C. Partie Web services SOAP WSDL avec JaxWS : 
# 1. Créer un Web services basé sur JaxWS qui permet de consulter un relevé.
# 2. Créer un serveur JaxWS pour déployer le Web service
# 3. Analyser le WSDL en utilisant un Browser Web
# 4. Tester les méthodes du Web services en utilisant SoapUI
# 5. Créer un Client SOAP Java.
# D. Web services RESTful avec JAXRS ou Spark : 
# 1. Créer un Web service RESTFul en utilisant la librairie Java Spark qui permet de consulter 
# un Relevé au format JSON. Les données du relevé sont à lire à partir du fichier XML.
# 2. Tester Le Web service avec un client REST (Browser Web, SoapUI, PostMan etc…)
# 3. Créer un Client REST Java (Java script, PHP, etc.)
