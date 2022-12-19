## Sommaire

* Présentation
* Présentation du centre de formation
* Présentation de l'entreprise
* Contexte de réalisation du projet présenté
    * Cahier des charges
    * Environnement Humain
    * Environnement Technique
    * Schéma de principe


### Concevoir et développer des composants d'interface utilisateur en intégrant les recommandations de sécurité

* Maquetter une application.
* Développer une interface utilisateur de type desktop.
* Développer des composants d'accès aux données.
* Développer la partie front-end d'une interface utilisateur web.
* Développer la partie back-end d'une interface utilisateur web.

### Concevoir et développer la persistance des données en intégrant les recommandations de sécurité

* Concevoir une base de données.
* Mettre en place une base de données.
* Développer des composants dans le langage d'une base de données.

### Concevoir et développer une application multicouche répartie en intégrant les recommandations de sécurité

* Collaborer à la gestion d'un projet informatique et à l'organisation de l'environnement de développement.
* Concevoir une application.
* Développer des composants métier.
* Construire une application organisée en couches.
* Développer une application mobile.
* Préparer et exécuter les plans de tests d'une application.
* Préparer et exécuter le déploiement d'une application.
    
## Concevoir et développer des composants d'interface utilisateur en intégrant les recommandations de sécurité

### Maquetter une application
![image](https://user-images.githubusercontent.com/67165182/208379411-da58b4ae-4ebf-4918-a80e-540a84c8c5a1.png)
## Customer.java

```java
package com.redhat.customer;

import lombok.Data;

import javax.validation.constraints.Email;
import javax.validation.constraints.NotEmpty;

@Data
public class Customer {
    private Integer customerId;
    @NotEmpty
    private String firstName;
    private String middleName;
    @NotEmpty
    private String lastName;
    private String suffix;
    @Email
    private String email;
    private String phone;
}
```
## Customer.java

```java
package com.redhat.customer;

import lombok.Data;

import javax.validation.constraints.Email;
import javax.validation.constraints.NotEmpty;

@Data
public class Customer {
    private Integer customerId;
    @NotEmpty
    private String firstName;
    private String middleName;
    @NotEmpty
    private String lastName;
    private String suffix;
    @Email
    private String email;
    private String phone;
}
```
## Customer.java

```java
package com.redhat.customer;

import lombok.Data;

import javax.validation.constraints.Email;
import javax.validation.constraints.NotEmpty;

@Data
public class Customer {
    private Integer customerId;
    @NotEmpty
    private String firstName;
    private String middleName;
    @NotEmpty
    private String lastName;
    private String suffix;
    @Email
    private String email;
    private String phone;
}
```
