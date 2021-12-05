//Initialisation des variables d'environnement1.1 : 
target="srv2"  // serveur 2
type="$target-bp28m-before" data_stream="/usr/share/xml/scap/ssg/content/ssg-rhel7-ds-1.2.xml" profile="xccdf_org.ssgproject.content_profile_anssi_nt28_minimal" cpe_dict="/usr/share/xml/scap/ssg/content/ssg-rhel7-cpe-dictionary.xml
ssh $target "yum -y install scap-security-guide"
curl -L https://git.io/JMPci \-o /usr/share/xml/scap/ssg/content/ssg-rhel7-ds-1.2.xml // station de contrôler
//new type="$target-bpm28-before"
profile="xccdf_org.ssgproject.content_profile_anssi_nt28_minimal" 
ls -l srv2* ls -l ssg* // verification des fichiers générés
