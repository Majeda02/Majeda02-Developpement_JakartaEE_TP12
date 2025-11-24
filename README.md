### "# Developpement_JakartaEE_TP12" 

#### Objectif
L’objectif de ce TP est de comprendre comment déléguer l’authentification d’une application Spring Boot à un fournisseur externe tel que Google ou Keycloak en utilisant le protocole OAuth2 et la norme OpenID Connect (OIDC).
L’utilisateur ne s’authentifie plus directement auprès de l’application, mais auprès d’un service d’identité de confiance, qui délivre un token d’accès (Access Token) et un token d’identité (ID Token).
Cette approche correspond aux pratiques modernes utilisées dans les architectures distribuées, les API sécurisées, et les systèmes Single Sign-On (SSO).

#### Compétences développées
* Expliquer les principes et acteurs du protocole OAuth2.
* Configurer une application Spring Boot en tant que client OAuth2.
* Mettre en place une authentification avec Google ou Keycloak .
* Extraire et afficher les informations du profil utilisateur à partir du token d’identité.
* Comprendre le flux complet d’autorisation et les notions de redirection et scopes.

#### Notions clés
<img width="1251" height="519" alt="image" src="https://github.com/user-attachments/assets/4939bb1c-ccbd-4402-ba93-5110cc466bba" />

#### Création du projet
<img width="959" height="503" alt="CréationProjet" src="https://github.com/user-attachments/assets/2699183a-2c5d-4894-ad08-5467040ab03b" />

#### Structure du projet
<img width="1106" height="1007" alt="image" src="https://github.com/user-attachments/assets/4cc74307-e980-4812-a1f8-77801679f984" />


#### Configuration de l’application avec Google OAuth2
<img width="959" height="500" alt="ConsoleCloud" src="https://github.com/user-attachments/assets/90d82933-1a23-4468-af65-84ef1a3f3eeb" />
<img width="959" height="472" alt="Creerprojet" src="https://github.com/user-attachments/assets/10341305-a148-4423-be9b-d4ea41b95e9f" />
<img width="959" height="503" alt="Creerprojet2" src="https://github.com/user-attachments/assets/785af795-1414-4802-b4c4-7632e0d38dc6" />
<img width="959" height="485" alt="GoogleIdentify1" src="https://github.com/user-attachments/assets/f698708a-8b3c-4668-858f-2eb09f894e78" />
<img width="959" height="479" alt="GoogleIdentify2" src="https://github.com/user-attachments/assets/fb83eaf7-03b7-4b80-aec6-b80ae8a9a05c" />
<img width="954" height="452" alt="Authconfiguration" src="https://github.com/user-attachments/assets/f46b5fc6-0b2e-4fbd-b919-45ced79141aa" />
<img width="959" height="470" alt="Création des identifiants" src="https://github.com/user-attachments/assets/3fad38a5-cf22-4d0f-b0eb-016dc321631c" />
<img width="959" height="473" alt="OAuth 2 0 1" src="https://github.com/user-attachments/assets/4f880924-4cac-48ed-8be3-1c7b62946b12" />

#### Test et validation
<img width="959" height="474" alt="se connecter" src="https://github.com/user-attachments/assets/5bc41294-3e72-42dc-a41e-4476af4a15df" />
<img width="959" height="473" alt="AccesFinal" src="https://github.com/user-attachments/assets/2fb6904c-b482-4a9b-ad01-344e4c490dc9" />
<img width="959" height="475" alt="Logout1" src="https://github.com/user-attachments/assets/90345713-01b0-45b8-8347-e10b4fd71ff4" />
