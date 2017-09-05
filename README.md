# Inforoutes logging mapping

Plugin which allows you to set up inforoutes username by email address

## Install

```bash
cd {RAINLOOP_ROOTPATH/rainloop/v/{RAINLOOP_VERSION}/plugins
git clone https://github.com/cdg46/inforoutes-login-mapping
```

## Configuration

 - Connect to admin interface of rainloop
  ```http//yourdomain/?admin```
 - Go to Packages
 - Select infroroutes-loggin-mapping
 - Go to Plugins
 - Add your mapping
  ```*@domaine.ltd:*@domaine.mainDomain.ltd```
 - save
 - Go to Domains
 - Add ```domaine.ltd``` with **imap** and **smtp** credentials
 - Go to Plugins
 - open ```override-smtp-credentials```
 - Configure **smtp** credentials as requested by **mainDomain.ltd**
 - Add override user wildcar domains
