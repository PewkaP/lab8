docker scout quickview lab8:classic
    i New version 1.9.3 available (installed version is 1.8.0) at https://github.com/docker/scout-cli
    ✓ SBOM of image already cached, 583 packages indexed

  Target             │  lab8:classic    │    4C    14H     8M     1L     2?   
    digest           │  cf68de612853    │                                     
  Base image         │  node:22-alpine  │    0C     0H     0M     0L          
  Updated base image │  node:slim       │    0C     0H     0M    23L          
                     │                  │                        +23          

What's next:
    View vulnerabilities → docker scout cves lab8:classic
    View base image update recommendations → docker scout recommendations lab8:classic
    Include policy results in your quickview by supplying an organization → docker scout quickview lab8:classic --org <organization>










docker scout cves lab8:classic
    i New version 1.9.3 available (installed version is 1.8.0) at https://github.com/docker/scout-cli
    ✓ SBOM of image already cached, 583 packages indexed
    ✗ Detected 17 vulnerable packages with a total of 25 vulnerabilities


## Overview

                    │           Analyzed Image            
────────────────────┼─────────────────────────────────────
  Target            │  lab8:classic                       
    digest          │  cf68de612853                       
    platform        │ linux/arm64/v8                      
    vulnerabilities │    4C    14H     8M     1L     2?   
    size            │ 90 MB                               
    packages        │ 583                                 


## Packages and Vulnerabilities

   1C     3H     2M     0L  lodash 4.17.10
pkg:npm/lodash@4.17.10

    ✗ CRITICAL CVE-2019-10744 [Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution')]
      https://scout.docker.com/v/CVE-2019-10744
      Affected range : <4.17.12                                      
      Fixed version  : 4.17.12                                       
      CVSS Score     : 9.1                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:H/A:H  
    
    ✗ HIGH CVE-2020-8203 [Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution')]
      https://scout.docker.com/v/CVE-2020-8203
      Affected range : >=3.7.0                                       
                     : <4.17.19                                      
      Fixed version  : 4.17.20                                       
      CVSS Score     : 7.4                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:H/PR:N/UI:N/S:U/C:N/I:H/A:H  
    
    ✗ HIGH CVE-2021-23337 [Improper Neutralization of Special Elements used in a Command ('Command Injection')]
      https://scout.docker.com/v/CVE-2021-23337
      Affected range : <4.17.21                                      
      Fixed version  : 4.17.21                                       
      CVSS Score     : 7.2                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H  
    
    ✗ HIGH CVE-2018-16487 [Uncontrolled Resource Consumption]
      https://scout.docker.com/v/CVE-2018-16487
      Affected range : <4.17.11  
      Fixed version  : 4.17.11   
    
    ✗ MEDIUM CVE-2020-28500 [Inefficient Regular Expression Complexity]
      https://scout.docker.com/v/CVE-2020-28500
      Affected range : <4.17.21                                      
      Fixed version  : 4.17.21                                       
      CVSS Score     : 5.3                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:L  
    
    ✗ MEDIUM CVE-2019-1010266 [Uncontrolled Resource Consumption]
      https://scout.docker.com/v/CVE-2019-1010266
      Affected range : <4.17.11  
      Fixed version  : 4.17.11   
    

   1C     0H     1M     0L  ejs 2.6.1
pkg:npm/ejs@2.6.1

    ✗ CRITICAL CVE-2022-29078 [Improper Neutralization of Special Elements in Output Used by a Downstream Component ('Injection')]
      https://scout.docker.com/v/CVE-2022-29078
      Affected range : <3.1.7                                        
      Fixed version  : 3.1.7                                         
      CVSS Score     : 9.8                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H  
    
    ✗ MEDIUM CVE-2024-33883 [Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution')]
      https://scout.docker.com/v/CVE-2024-33883
      Affected range : <3.1.10  
      Fixed version  : 3.1.10   
    

   1C     0H     0M     0L  morgan 1.9.0
pkg:npm/morgan@1.9.0

    ✗ CRITICAL CVE-2019-5413 [Improper Control of Generation of Code ('Code Injection')]
      https://scout.docker.com/v/CVE-2019-5413
      Affected range : <1.9.1                                        
      Fixed version  : 1.9.1                                         
      CVSS Score     : 9.8                                           
      CVSS Vector    : CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H  
    

   1C     0H     0M     0L  json-schema 0.2.3
pkg:npm/json-schema@0.2.3

    ✗ CRITICAL CVE-2021-3918 [Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution')]
      https://scout.docker.com/v/CVE-2021-3918
      Affected range : <0.4.0                                        
      Fixed version  : 0.4.0                                         
      CVSS Score     : 9.8                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H  
    

   0C     2H     0M     0L  pug 2.0.0-beta11
pkg:npm/pug@2.0.0-beta11

    ✗ HIGH CVE-2024-36361 [Improper Control of Generation of Code ('Code Injection')]
      https://scout.docker.com/v/CVE-2024-36361
      Affected range : <=3.0.2                                       
      Fixed version  : 3.0.3                                         
      CVSS Score     : 8.1                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:H/PR:N/UI:N/S:U/C:H/I:H/A:H  
    
    ✗ HIGH CVE-2021-21353 [Improper Neutralization of Special Elements in Output Used by a Downstream Component ('Injection')]
      https://scout.docker.com/v/CVE-2021-21353
      Affected range : <3.0.1                                        
      Fixed version  : 3.0.1                                         
      CVSS Score     : 6.8                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:H/PR:N/UI:N/S:C/C:N/I:H/A:N  
    

   0C     2H     0M     0L  pug-code-gen 1.1.1
pkg:npm/pug-code-gen@1.1.1

    ✗ HIGH CVE-2024-36361 [Improper Control of Generation of Code ('Code Injection')]
      https://scout.docker.com/v/CVE-2024-36361
      Affected range : <=2.0.3                                       
      Fixed version  : 3.0.3                                         
      CVSS Score     : 8.1                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:H/PR:N/UI:N/S:U/C:H/I:H/A:H  
    
    ✗ HIGH CVE-2021-21353 [Improper Neutralization of Special Elements in Output Used by a Downstream Component ('Injection')]
      https://scout.docker.com/v/CVE-2021-21353
      Affected range : <2.0.3                                        
      Fixed version  : 2.0.3                                         
      CVSS Score     : 6.8                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:H/PR:N/UI:N/S:C/C:N/I:H/A:N  
    

   0C     2H     0M     0L  github.com/opencontainers/runc 1.1.12
pkg:golang/github.com/opencontainers/runc@1.1.12

    ✗ HIGH GHSA-c5pj-mqfh-rvc3 [OWASP Top Ten 2017 Category A9 - Using Components with Known Vulnerabilities]
      https://scout.docker.com/v/GHSA-c5pj-mqfh-rvc3
      Affected range : <1.2.0-rc.1                                   
      Fixed version  : 1.2.0-rc.1                                    
      CVSS Score     : 7.2                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H  
    
    ✗ HIGH CVE-2024-3154 [OWASP Top Ten 2017 Category A9 - Using Components with Known Vulnerabilities]
      https://scout.docker.com/v/CVE-2024-3154
      Affected range : <1.2.0-rc.1                                   
      Fixed version  : 1.2.0-rc.1                                    
      CVSS Score     : 7.2                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:H/UI:N/S:U/C:H/I:H/A:H  
    

   0C     1H     1M     0L  express 4.15.5
pkg:npm/express@4.15.5

    ✗ HIGH CVE-2022-24999 [OWASP Top Ten 2017 Category A9 - Using Components with Known Vulnerabilities]
      https://scout.docker.com/v/CVE-2022-24999
      Affected range : <4.17.3                                       
      Fixed version  : 4.17.3                                        
      CVSS Score     : 7.5                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H  
    
    ✗ MEDIUM CVE-2024-29041 [Improper Validation of Syntactic Correctness of Input]
      https://scout.docker.com/v/CVE-2024-29041
      Affected range : <4.19.2                                       
      Fixed version  : 4.19.2                                        
      CVSS Score     : 6.1                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:N  
    

   0C     1H     0M     0L     1?  mime 1.3.4
pkg:npm/mime@1.3.4

    ✗ HIGH CVE-2017-16138 [Uncontrolled Resource Consumption]
      https://scout.docker.com/v/CVE-2017-16138
      Affected range : <1.4.1                                        
      Fixed version  : 1.4.1                                         
      CVSS Score     : 7.5                                           
      CVSS Vector    : CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H  
    
    ✗ UNSPECIFIED GMS-2017-247 [OWASP Top Ten 2017 Category A9 - Using Components with Known Vulnerabilities]
      https://scout.docker.com/v/GMS-2017-247
      Affected range : <1.4.1        
      Fixed version  : 1.4.1, 2.0.3  
    

   0C     1H     0M     0L  kind-of 3.2.2
pkg:npm/kind-of@3.2.2

    ✗ HIGH CVE-2019-20149 [OWASP Top Ten 2017 Category A9 - Using Components with Known Vulnerabilities]
      https://scout.docker.com/v/CVE-2019-20149
      Affected range : <=6.0.2                                       
      Fixed version  : 6.0.3                                         
      CVSS Score     : 7.5                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:H/A:N  
    

   0C     1H     0M     0L  qs 6.5.0
pkg:npm/qs@6.5.0

    ✗ HIGH CVE-2022-24999 [Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution')]
      https://scout.docker.com/v/CVE-2022-24999
      Affected range : >=6.5.0                                       
                     : <6.5.3                                        
      Fixed version  : 6.5.3                                         
      CVSS Score     : 7.5                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H  
    

   0C     1H     0M     0L  qs 6.5.2
pkg:npm/qs@6.5.2

    ✗ HIGH CVE-2022-24999 [Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution')]
      https://scout.docker.com/v/CVE-2022-24999
      Affected range : >=6.5.0                                       
                     : <6.5.3                                        
      Fixed version  : 6.5.3                                         
      CVSS Score     : 7.5                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H  
    

   0C     0H     1M     0L  tough-cookie 2.4.3
pkg:npm/tough-cookie@2.4.3

    ✗ MEDIUM CVE-2023-26136 [Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution')]
      https://scout.docker.com/v/CVE-2023-26136
      Affected range : <4.1.3                                        
      Fixed version  : 4.1.3                                         
      CVSS Score     : 6.5                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:L/A:N  
    

   0C     0H     1M     0L  path-parse 1.0.6
pkg:npm/path-parse@1.0.6

    ✗ MEDIUM CVE-2021-23343 [Uncontrolled Resource Consumption]
      https://scout.docker.com/v/CVE-2021-23343
      Affected range : <1.0.7                                        
      Fixed version  : 1.0.7                                         
      CVSS Score     : 5.3                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:L  
    

   0C     0H     1M     0L  request 2.88.0
pkg:npm/request@2.88.0

    ✗ MEDIUM CVE-2023-28155 [Server-Side Request Forgery (SSRF)]
      https://scout.docker.com/v/CVE-2023-28155
      Affected range : <=2.88.2                                      
      Fixed version  : not fixed                                     
      CVSS Score     : 6.1                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:C/C:L/I:L/A:N  
    

   0C     0H     1M     0L  ajv 5.5.2
pkg:npm/ajv@5.5.2

    ✗ MEDIUM CVE-2020-15366 [Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution')]
      https://scout.docker.com/v/CVE-2020-15366
      Affected range : <6.12.3                                       
      Fixed version  : 6.12.3                                        
      CVSS Score     : 5.6                                           
      CVSS Vector    : CVSS:3.1/AV:N/AC:H/PR:N/UI:N/S:U/C:L/I:L/A:L  
    

   0C     0H     0M     1L     1?  clean-css 3.4.28
pkg:npm/clean-css@3.4.28

    ✗ LOW GHSA-wxhq-pm8v-cw75 [Inefficient Regular Expression Complexity]
      https://scout.docker.com/v/GHSA-wxhq-pm8v-cw75
      Affected range : <4.1.11  
      Fixed version  : 4.1.11   
    
    ✗ UNSPECIFIED GMS-2019-15 [OWASP Top Ten 2017 Category A9 - Using Components with Known Vulnerabilities]
      https://scout.docker.com/v/GMS-2019-15
      Affected range : <4.1.11  
      Fixed version  : 4.1.11   
    


29 vulnerabilities found in 17 packages
  UNSPECIFIED  2   
  LOW          1   
  MEDIUM       8   
  HIGH         14  
  CRITICAL     4   


What's next:
    View base image update recommendations → docker scout recommendations lab8:classic










docker scout recommendations lab8:classic 
    i New version 1.9.3 available (installed version is 1.8.0) at https://github.com/docker/scout-cli
    ✓ SBOM of image already cached, 583 packages indexed

  Target   │  lab8:classic   
    digest │  cf68de612853   

## Recommended fixes

  Base image is  node:22-alpine 

  Name            │  22-alpine                                                                 
  Digest          │  sha256:8f753f5f91f073f518c4fe7d2597e6d84b28faa29fb4f60e95ec73f6bfb0bfde   
  Vulnerabilities │    0C     0H     0M     0L                                                 
  Pushed          │ 6 days ago                                                                 
  Size            │ 52 MB                                                                      
  Packages        │ 219                                                                        
  Flavor          │ alpine                                                                     
  OS              │ 3.20                                                                       
  Runtime         │ 22                                                                         

                                                                                                                                                                                                
  │ The base image is also available under the supported tag(s)  22-alpine3.20 ,  22.2-alpine ,  22.2-alpine3.20 ,  22.2.0-alpine ,  22.2.0-alpine3.20 ,  alpine ,  alpine3.20 ,  current-alpine , 
  │ current-alpine3.20 . If you want to display recommendations specifically for a different tag, please re-run the command using the  --tag  flag.                                              



Refresh base image
  Rebuild the image using a newer base image version. Updating this may result in breaking changes.

  ✓ This image version is up to date.


Change base image
  The list displays new recommended tags in descending order, where the top results are rated as most suitable.


            Tag           │                Details                 │   Pushed    │       Vulnerabilities        
──────────────────────────┼────────────────────────────────────────┼─────────────┼──────────────────────────────
   slim                   │ Benefits:                              │ 2 weeks ago │    0C     0H     0M    23L   
  Tag is preferred tag    │ • Tag is preferred tag                 │             │                        +23   
  Also known as:          │ • Tag is using slim variant            │             │                              
  • 22.2.0-slim           │ • slim was pulled 17K times last month │             │                              
  • 22.2-slim             │                                        │             │                              
  • current-slim          │ Image details:                         │             │                              
  • 22-slim               │ • Size: 76 MB                          │             │                              
  • bookworm-slim         │ • Runtime: 22                          │             │                              
  • 22-bookworm-slim      │                                        │             │                              
  • 22.2-bookworm-slim    │                                        │             │                              
  • 22.2.0-bookworm-slim  │                                        │             │                              
  • current-bookworm-slim │                                        │             │             
