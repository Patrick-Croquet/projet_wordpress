# projet_wordpress
 Projet WordPress woocommerce
 

Installation à vérifier

wp-config.php

// ** Réglages MySQL - Votre hébergeur doit vous fournir ces informations. ** //
/** Nom de la base de données de WordPress. */
define( 'DB_NAME', 'maboutique' );

/** Utilisateur de la base de données MySQL. */
define( 'DB_USER', 'root' );

/** Mot de passe de la base de données MySQL. */
define( 'DB_PASSWORD', 'root' );

/** Adresse de l’hébergement MySQL. */
define( 'DB_HOST', 'localhost' );

En base de données
Dans la table wp_options modifier 
le port de siteurl : http://localhost:<8888>/wordpress
le port de home : http://localhost:<8888>/wordpress

Ajouter la table wp_users à partir d'une installation WordPress que vous avez déjà faite
Dans la table wp_user vous avez l'identifiant et le mot de passe du back office.