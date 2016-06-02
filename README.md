sa-pm2
======

[![Build Status](https://travis-ci.org/softasap/sa-pm2.svg?branch=master)](https://travis-ci.org/softasap/sa-pm2)

Simple

  roles:
    - {
        role: "sa-pm2"
      }


Advanced:


  roles:
  - {
      role: "sa-pm2",

      option_install_nodejs: true,
      option_nodejs_install_with_nvm: true,
      option_nodejs_install_with_apt: false,
      nodejs_version: "4.1.2"
    }
