# running sampe1 with android studio

Prerequisites for android studio: 
1. You must download and install Cucumber for java plugin.
2. Also you must download and install Gherkin plugin.

# Libraries & plugins 
1- Recycler View.
2- Retrofit.
3- Cucumber.

# User Stories
The following required functionality is completed:

As a User(runner), I want to be able to log-in to the application to start trip and manage shipments.
Upon User(runner)logging-in request run data sheet from System.
As a User(runner) I want to be able to view run-sheet details.

 
# To run the enviroment using Vagrant Up & linux (ubuntu)

1-Install vagrant using the terminal.
2-Install dongsupark/coreos-stable Vagrant box.
3-Customize the Vagrant file according to the available one for StreetGlide.
4-Run "vagrant up" command using provider libvirt.
5-Then run vagrant ssh to access the core-os.
6-After accessing core-os run command "update_engine_client -check_for_update".
https://www.vagrantup.com/intro/index.html

# Tools and Technologies are Used :
1- Vagrant with Libvert https://docs.cumulusnetworks.com/display/VX/Vagrant+and+Libvirt+with+KVM+or+QEMU 
2- Domain-Driven Design (DDD) http://www.zankavtaskin.com/2014/12/applied-domain-driven-design-ddd-part-0.html https://www.codeproject.com/Articles/339725/Domain-Driven-Design-Clear-Your-Concepts-Before-Yo
3- Cucumber and Espresso https://medium.com/gumtree-dev-team/android-bdd-with-cucumber-and-espresso-the-full-guide-9c20cfcb8535
4- TDD & BDD (unit test & intgration test & UI test).
5- CircleCI CI/CD. https://proandroiddev.com/circleci-with-android-continuous-integration-3ecd98f92bd4 
6- Kotlin with RX.
7- GreenDAO ORM Android DB http://greenrobot.org/greendao/. 
8- Mockito & Robolectric.
9- parmeterized unit test.https://www.tutorialspoint.com/junit/junit_parameterized_test.htm
10- MVP.
11- Android Continuous Integration using Fastlane (under dev).
12- Firebase test lab (under dev).
13- AWS&CircleCI(under dev).
14- Make Android App bundle(under dev) and dynamic delivery https://www.youtube.com/watch?v=9D63S4ZRBls.


# User Acceptance Test Cases 
![AcceptanceTestCase1](https://user-images.githubusercontent.com/15185524/60012311-ed6d0700-967b-11e9-8f30-2f4c250017c7.PNG)

![AcceptanceTestCase2](https://user-images.githubusercontent.com/15185524/60012458-489ef980-967c-11e9-8fd8-38a341f0d600.PNG)


# Domain-Driven-Design Archticture Diagram
 ![alt text](http://1.bp.blogspot.com/-f9QYYWLc1Uk/UoKzpDHYkkI/AAAAAAAACA4/OD1bq9MLYFY/s1600/DDD_png_pure.png)

 
 
# UML Diagrams (Sequence Diagram & Class Diagram)
![loginSeq](https://user-images.githubusercontent.com/15185524/60013055-c7e0fd00-967d-11e9-99bb-8876bc9bca7d.png)


![alt text](https://lh3.googleusercontent.com/w_yUHZzc3TUhpVlxegy0l4WyoTxn1cSWVpoPHhzcBImE9b65cz6_2YGdFLqHVUQ_OWyb7MJkq-XmfFsOyMqzVFXoW7sdBkmDTQq9tFB4ENF7Z7WwOGlHst_YjcZS6JNL6QsnvHF5KJat2Tw76fNgyBNDylh2iGWG8mGIAzQg6kXFe_JdS-N3B-txGgi_jn-8VjbeQ3283tJbAEg6zREyHMK7Kdx-mxkhX3XXwoB2hvarR2lFe2Q9utBpEbLD8-krVor1NamGoCCLK2I_BhwR8G4z1Uq2yge_PLUvxBP732adg4jBRVUIzyacdpEfoms3yyfv4bnwozk7Z_mwaB2GqxO3dsp6KU3XArYUZgWuFjDbr2tPItn5MQircQAiBXSUF3Ysv6gak1r77twK1ThpHuzms2B8sjB9pY36M-3-8eTIb56UtJaaN5ERtN4epje5ynWqfZvKecovGh-DxYcbxduwVnMYrjXBWzITilaEvKEAaqzGQ3R4lCOXiVj7U_ANX_NvSiQ1sPIR_SXIBHfggWbG5gMI97e6qtJCNAjvYknyxh5R_6x7T9KMuOZ8sVK4_mIwjTGCNVFMpl3Z7ZZBPvsmNyQ8-IXxbah_1Yws9W-2FK0bP6kKg5HKA7n8PHChUnGY7XCxmRpDOAaaBhBvROTP0W3JUw=w1579-h685-no)

![loginSeq](https://user-images.githubusercontent.com/15185524/60013055-c7e0fd00-967d-11e9-99bb-8876bc9bca7d.png)


![alt text](https://lh3.googleusercontent.com/SGfMh19sg8iasVJcyAr1qEX4DuCcLbqSmDwpgx_EBrFOdXU0CxSof9Mic9NaMEIcoFLlmVfOx-yMy8Iw7rV5PsHU-oh0Zqw2kSpx-a88F3PxL2LLybN5VbQd7J_qkh_cbQG4wX9PpZNES3MXHojqjLAeT6XIAVZRRlo1Dz1urub_arZmOwMfAbGks7dr_md7stCutojSAkZ12RQH32fxB92MEvP4Mo4f8iIUiSvlo8yWGHG8pIiUC85sDgG0lL6Z2Wk8ykzt9fhKfhuow-IXowCtYMA1m02THZwQn7-NN8EB4gV6GBSFxq9D88bL0oZ-s5Q1WqNL7sDv6YjsD5zFD2QYbBYLwOrzFQeBKjZyxEccMZNv2_XSXal3ZtDXyBeS-3QanRp_gpsV7jKPe-L3zFSOkZSp-yoT0pRkBL4OBO6ooSYYGCivv8v5bJGIKUI45DpEtgerR8F79dFZBuOLfHXwBxqvKxV0WmFfwjzKwVAt-BIVQ13kO8A4cbZLDn7cIJ73ePZJAq0oYH_c8yjfsOVXkXLqaWGcMk9Bbme0pVnHS_yfehbaWWNk4Xdz6X1ejeKZ8caItj3ApS6BkD8S5E47aMmsHRp7TP_P5Myzw_qlWld9m7QiLzHGuPKu5K8IafshvYUQvlALM5h8nOcWtxlN4h71GA=w1208-h691-no)

# BDD & TDD Flow  
![BDD TDD](https://user-images.githubusercontent.com/15185524/60012542-813ed300-967c-11e9-9883-9359e7d0efbc.png)


# Checklist Template_UnitTesting

![DZ_ChecklistTemplate_UnitTesting_0_Page1](https://user-images.githubusercontent.com/15185524/60012698-eabee180-967c-11e9-955c-aa356d6960ec.png)


![DZ_ChecklistTemplate_UnitTesting_0_Page2](https://user-images.githubusercontent.com/15185524/60012772-1e017080-967d-11e9-95e6-623ac2450042.png)


![DZ_ChecklistTemplate_UnitTesting_0_Page3](https://user-images.githubusercontent.com/15185524/60012883-5a34d100-967d-11e9-8bca-8d1ca1b4d5ef.png)



# Git Fow 
![Gitflow](https://user-images.githubusercontent.com/15185524/60012960-8b150600-967d-11e9-9b41-fe7f1c51fe9a.png)

# CI/CD FLOW 
![CICD](https://user-images.githubusercontent.com/15185524/60012620-b77c5280-967c-11e9-8a3f-721e7265f82b.png)


# Android Test pyramid 

![alt text](https://cdn-images-1.medium.com/max/1563/1*6M7_pT_2HJR-o-AXgkHU0g.jpeg)

https://medium.com/android-testing-daily/the-3-tiers-of-the-android-test-pyramid-c1211b359acd
