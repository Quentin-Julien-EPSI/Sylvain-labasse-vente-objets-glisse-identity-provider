# Sylvain-labasse-vente-objets-glisse-identity-provider


## API de connection pour les administrateurs : 

Pour utiliser notre API de création et de gestion des utilisateurs nous avons utilisé KeyCloak, KeyCloak est hébergé sur un conteneur docket et est exposé sur : 
> https://keycloak_epsi.flusin.fr/admin/epsi_sylvain_labasse/console/

Pour vous connecter à l'interface d'administrateurs il vous faut utiliser le compte :

- Username : admin_epsi
- PassWord : admin_epsi_password

Sinon vous pouvez vous créer un compte directement en vous connectant via Github ou en vous créant un compte.

### Information de connexion

Une fois connecté à l'interface utilisateurs vous pourrez créer des utilisateurs de test pour votre application.

#### L'API

> La doc de l'API complète de KeyCloak se trouve ici : https://www.keycloak.org/documentation

Grâce à l'application vous pouvez créer des utilisateurs, créer des groupes, lié des utilisateurs à des groupes et autre fonctionnalités pour gérer les droits des utilisateurs et leur place dans votre application.

Pour utiliser l'API dans votre application voici quelques liens utile : 

> https://www.keycloak.org/docs-api/21.0.0/rest-api/index.html#_users_resource

Le realm étant : 
> epsi_sylvain_labasse
