=== wpSOL ===
Contributors: koter84, Gerrit Jan Faber
Requires at least: 3.6
Tested up to: 4.0
Stable tag: trunk
Tags: scouting, scouting nederland, sol, scoutsonline, openid, login, sidebar-widget
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

[NL]

Verbind Wordpress met de Scouting Nederland OpenID-server

[EN]

Connect Wordpress to the Scouting Nederland OpenID-server

== Description ==

[NL]

wpSOL verbind Wordpress met de Scouting Nederland OpenID-server zodat mensen kunnen inloggen en registreren met hun account van scouting.nl

om de login te valideren maakt deze plugin een https verbinding met login.scouting.nl, dit is onderdeel van de openid-standaard.

bugs en feature-requests kan je kwijt op: [GitHub](https://github.com/koter84/wpSOL/issues)

[EN]

wpSOL connects WordPress to the Scouting Nederland OpenID-server to allow people to login and register with their login-account from scouting.nl

this plugin connects over https to login.scouting.nl to verify the login as part of the openid-standard

bugs and feature-requests can go to: [GitHub](https://github.com/koter84/wpSOL/issues)

== Screenshots ==

1. wp-login.php met scouting-login
2. sidebar-widget in theme twenty-thirteen
3. sidebar-widget in custom theme

== Installation ==

[NL]

1. login op sol.scouting.nl en verander je rol naar "webmaster".
1. ga nu naar login.scouting.nl en beweeg je muis over "mijn websites" en klik op "voeg beheerde website toe".
1. voer het domein van je wordpress-website in en selecteer de organisatie die je toegang wilt geven.
1. installeer en activeer de plugin, klaar.

[EN]

1. login to sol.scouting.nl and change your role to "webmaster". 
1. go to login.scouting.nl move your mouse over "mijn websites" and click on "voeg beheerde website toe".
1. enter the domain which is setup for wordpress and select the organization you want to give access.
1. install and activate the plugin, that's it.

== Frequently Asked Questions ==

[NL]

= Het werkt niet! =

Waarschijnlijk moet je het domein van je website toevoegen op login.scouting.nl, dit kan alleen als je ingelogd bent als webmaster van jouw groep!
Kijk bij de [installatie-tab](https://wordpress.org/plugins/wpsol/installation/) voor een volledige uitleg.

= Moet ik onderdeel uitmaken van Scouting Nederland om hier gebruik van te maken? =

Ja, de OpenID-server wordt gebruikt om te bepalen of iemand onderdeel uitmaakt van Scouting Nederland, en of ze lid zijn van de juiste organisatie.
Om de plugin in te stellen bij Scouting Nederland moet je het webmaster-privilege hebben voor jouw scouting-groep.

= Kan ik binnen de plugin nog dingen instellen? =

Ja, er is een instellingen-pagina waar je de redirect na in- of uitloggen kan aanpassen en de naam van de gebruiker binnen wordpress kan forceren.

[EN]

= It's not working! =

You probably need to add the domain of your website to login.scouting.nl, you can only do this when you are logged in as a webmaster.
Check the [installation-tab](https://wordpress.org/plugins/wpsol/installation/) for a full explanation of how to do this.

= Do i need to be part of Scouting Nederland to use this? =

Yes, the OpenID-server is used to identify people and only allow access when they are a member of the right organisation within Scouting Nederland.
To setup the system at Scouting Nederland you need the webmaster-privilege for your scouting-group.

= Are there settings for this plugin? =

Yes, there is a settings-page where you can setup a redirect after login or logout and setup the Name the user gets in their profile and enforce that.

== Changelog ==

= v1.0.3 =
* added a redirect option for login and logout to go to the frontpage

= v1.0.2 =
* moved code from bitbucket to github

= v1.0.1 =
* some minor changes

= v1.0 =
* code cleanup

= v0.5 =
* i18n-support added to plugin

= v0.4 =
* setup default options during installation
* better login-flow
* username_prefix and autocreate new user options added
* better display of options page

= v0.3 =
* first public wordpress.org release
* make sidebar widget follow wordpress coding guidelines

= v0.2 =
* added a sidebar-login-widget
* added a settings page
* removed static-setting of domain-names

= v0.1 =
* initial internal release

== Translations ==

* Nederlands
* English
