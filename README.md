sa-pm2
======

[![Build Status](https://travis-ci.org/softasap/sa-pm2.svg?branch=master)](https://travis-ci.org/softasap/sa-pm2)

Simple

```YAML
  roles:
    - {
        role: "sa-pm2"
      }
```

Advanced:


```YAML
  roles:
  - {
      role: "sa-pm2",

      option_install_nodejs: true,
      option_nodejs_install_with_nvm: true,
      option_nodejs_install_with_apt: false,
      nodejs_version: "4.1.2"
    }
```


Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-pm2  role using the command


`
   ansible-galaxy install softasap.sa-pm2
`

the role will be available in the folder library/sa-grub

Please adjust the path accordingly.

```YAML

     - { 
         role: "softasap.sa-pm2"
       }

```



Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join Gitter channel at [Gitter] (https://gitter.im/softasap/)
