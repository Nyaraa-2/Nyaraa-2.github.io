## Customer.java
![image](https://user-images.githubusercontent.com/67165182/208377350-5646dc61-bce2-47cc-85a3-250939a6aed3.png)
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
