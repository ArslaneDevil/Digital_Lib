``` mermaid
class Utilisateur {
}

class Navigateur {
}

class MarketStore {
}

class ServeurDeMiseADisposition {
}

class Application {
   +Nom
   +Description
   +Droits d'auteur
}

class PageDeSelection {
}

Utilisateur --> Navigateur : utilise
Utilisateur --> MarketStore : utilise
Navigateur --> ServeurDeMiseADisposition : demande infos
MarketStore --> ServeurDeMiseADisposition : demande infos
Navigateur --> PageDeSelection : affiche
MarketStore --> PageDeSelection : affiche
PageDeSelection --> Application : affiche infos

