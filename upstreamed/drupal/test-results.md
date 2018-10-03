# Test results

## Smoke testing

Smoke tests are a subset of tests covering important functionality of an application, used to aid assessment if its main functions appear to work correctly. They are not a replacement of a properly tested application, which should be done by the upstream project.

Bitnami maintained charts are smoke tested against several k8s clusters to ensure they work properly in all of them.

## Test summary

Application: **Drupal 8.5.6**

Date: **2018-09-01 11:34:23**

Test | GKE (Google) | AKS (Azure) | OKE (Oracle)
--- | :---: | :---: | :---:
[Log in and out](#log-in-and-out)  | Ok | Ok | Ok
[Check up to date](#check-up-to-date)  | Ok | Ok | Ok
[Add article](#add-article) | Ok | Ok | Ok
[Check existing article](#check-existing-article)  | Ok | Ok | Ok
[Add image](#a) | Ok | Ok | Ok
[Check image](#a) | Ok | Ok | Ok
[Add page](#a) | Ok | Ok | Ok
[Check page](#a) | Ok | Ok | Ok
[Change fav icon](#a) | Ok | Ok | Ok
[Check fav icon](#a) | Ok | Ok | Ok
[Change logo](#a) | Ok | Ok | Ok
[Check logo](#a) | Ok | Ok | Ok | Ok
[Check htaccess](#a) | Ok | Ok | Ok | Ok
[Add user](#a) | Ok | Ok | Ok | Ok
[Login new user](#a) | Ok | Ok | Ok | Ok

## Test details

### Log in and out

- **Description**: It should be possible to log in and out  
- **Test results**:
  - GKE (Google): **Pass** (in 4.3 seconds on 2018/09/01 at 23:49:13)
  - AKS (Azure): **Pass** (in 3.1 seconds on 2018/09/01 at 12:31:01)
  - OKE (Oracle): **Pass** (in 1.9 seconds on 2018/09/01 at 10:00:58)

### Check up to date

- **Description**: The application should be up to date  
- **Test results**:
  - GKE (Google): **Pass** (in 4.3 seconds on 2018/09/01 at 23:49:13)
  - AKS (Azure): **Pass** (in 3.1 seconds on 2018/09/01 at 12:31:01)
  - OKE (Oracle): **Pass** (in 1.9 seconds on 2018/09/01 at 10:00:58)

### Add article

- **Description**: It should be possible to add an article  
- **Test results**:
  - GKE (Google): **Pass** (in 4.3 seconds on 2018/09/01 at 23:49:13)
  - AKS (Azure): **Pass** (in 3.1 seconds on 2018/09/01 at 12:31:01)
  - OKE (Oracle): **Pass** (in 1.9 seconds on 2018/09/01 at 10:00:58)

### Check existing article

- **Description**: An article created in a previous test should exist  
- **Test results**:
  - GKE (Google): **Pass** (in 4.3 seconds on 2018/09/01 at 23:49:13)
  - AKS (Azure): **Pass** (in 3.1 seconds on 2018/09/01 at 12:31:01)
  - OKE (Oracle): **Pass** (in 1.9 seconds on 2018/09/01 at 10:00:58)

### ...
