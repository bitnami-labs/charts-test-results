# Test results

## Smoke testing

Smoke tests are a subset of tests covering important functionality of an application, used to aid assessment if its main functions appear to work correctly. They are not a replacement of a properly tested application, which should be done by the upstreaam project.

Bitnami maintained charts are smoke tested against several k8s clusters to ensure they work properly in all of them.

## Results

Application: **Drupal 8.5.6**

Date: **2018-09-02 11:34:23**

Test | GKE (Google) | AKS (Azure) | OKE (Oracle)
--- | :---: | :---: | :---:
Login - Logout  | Ok | Ok | Ok
Check up-to-date  | Ok | Ok | Ok
Add article | Ok | Ok | Ok
Check article  | Ok | Ok | Ok
Add image | Ok | Ok | Ok
Check image | Ok | Ok | Ok
Add page | Ok | Ok | Ok
Check page | Ok | Ok | Ok
Change fav icon | Ok | Ok | Ok
Check fav icon | Ok | Ok | Ok
Change logo | Ok | Ok | Ok
Check logo | Ok | Ok | Ok | Ok
Check htaccess | Ok | Ok | Ok | Ok
Add user | Ok | Ok | Ok | Ok
Login new user | Ok | Ok | Ok | Ok
