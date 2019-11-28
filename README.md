# architecture-guidelines
Preferred web app technologies from Bloksberg.

## Guidelines
These are guidelines, each new project should follow the guidelines here, if you see no reasons to do something else. If you do see reason to test out a new library, or you feel that these guidelines is not right for your app, talk to other member of the team and discuss. If you agree, apart from these guidelines.

## Target Languages

We have chosen to use two languages for the new applications we create.
For the API's we want to use Go. Go have gotten a lot of attentions, and we have great experience using it.
For the webapps we are using node, to get an isomorhpic approche and be able to reuse code on both the server and client


## TODO

* 12factor.net
* CI: wercker
* Cloud: Google Cloud
* Put logic that are common across views (different web views and app as far back as possible,
and logic that are just for one view, into that view)
* Testing:
  * ha oppsett for unittesting i alle repos
  * percy
  * ha system-testing ala teste alle ruter i et api, eller scrolle ned til bunnen av mange sider i en webapp
  * bundlesize testing (! core.css på dagbladet er 1.2 MB, tror sol er mye værre)

##

* [Go](https://github.com/dbmedialab/architecture-guidelines/wiki/Go)
* [Operation](https://github.com/dbmedialab/ops/wiki)
* [Javascript](#)
* [Databases and cacheing](#)
