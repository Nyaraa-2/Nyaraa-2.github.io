## Customer.java
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
