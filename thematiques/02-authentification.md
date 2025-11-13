# Authentification

## Introduction
L’authentification est un aspect fondamental qui comprend plusieurs étapes cruciales afin de garantir
la sécurité d’une application.
De plus, à l’authentification, s’ajoute la notion de session qui, n’étant pas prise en compte par HTTP (stateless),
doit être gérée d’une manière ou d’une autre...

Les élément suivants vont donc être abordés:
- Code pour faire la vérification du user/password
- Stockage des mot de passe
- Gestion des sessions

## Théorie
- [Authentification-theorie](../supports/02-Auth.pptx)

## Pratique

### Webapp d’authentification

#### Bases (injection SQL...)
- [Authentification-pratique](../exercices/auth/02-Auth.docx)
- [Auth app - nodejstoken](../exercices/auth/02-nodejstoken.zip)

#### JWT
##### Répondre aux questions théoriques
- 02-jwt [pdf](../exercices/auth/02-jwt.pdf) | [docx](../exercices/auth/02-jwt.docx)
##### Implémenter dans l’application
- Générer les clés ?
- Utiliser jwt de Express...
    - [Documentation officielle](https://www.npmjs.com/package/express-jwt) 
    - [Suggestion de tutoriel](https://dev.to/hamzakhan/securing-your-expressjs-app-jwt-authentication-step-by-step-aom)


## Ressources
- [OWASP Password_Storage_Cheat_Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html
)
- https://proton.me/fr/business/pass/breach-observatory
- [JWT Handbook](../supports/02-jwt-handbook-v0_14_2.pdf)
