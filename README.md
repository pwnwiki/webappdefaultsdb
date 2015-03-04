Web Application  Defaults DB
===========

A DB of known Web Application Admin URLS, Username/Password Combos and Exploits

This list was originally released @ DerbyCon 2012 by Gillis Jones

Updated and released by the Web App Defaults DB Group

If you have info and don't want to trouble with Git, please feel free to shoot the info to:

webappdefaultsdb@gmail.com 

and let us worry about the repo voodoo.

If you wish to submit via git, please use the following field types:

* AdminURL: 
* UserPass: 
* Comment: 
* Link:

This will make it much easier for people to parse the entire db for information.

For example:
```
## Example CMS
Info: This webapp falls over if you hit /dos.php on version 1.0 and prior

* ADMINURL: /admin/uberleet.php 
* USERPASS: root:toor
* COMMENT: Usernames with be user@domain.com
* LINK: [http://exploitsdownload.com/search/cms](http://exploitsdownload.com/search/cms)

Documentation: [http://www.wikipedia.org/](http:/www.wikipedia.org/)

API Documentation: [https://apigee.com/console](https://apigee.com/console)
```

# List of CMSs in DB
* Accrisoft Freedom
* AdaptCMS Lite
* Adobe Business Catalyst
* Adobe CQ5
* Alfresco Community Edition
* Apache Lenya
* ATutor
* Autonomy Interwoven Teamsite CMS
* b2evolution
* BEdita
* BLOG:CMS
* blosxom
* Bricolage

<table>
<tr><td><b>Name</b></td><td><b>URL</b></td><td><b>Username</b></td><td><b>Password</b></td><td><b>Comment</b></td><td><b>Link</b></td>
 <tr><td>Cascade Server</td><td>/login.act</td><td>&nbsp;</td><td>&nbsp;</td><td>http://help.hannonhill.com/kb/security</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>CivicSpace</td><td>To be determined</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Clickability (Limelight Networks)</td><td>hosted by limelight?</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>CMS Made Simple</td><td>&nbsp;</td><td>admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/cmsmadesimple</td></tr>
 <tr><td>CMSimple</td><td>&nbsp;</td><td>admin</td><td>test</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/cmsimple</td></tr>
 <tr><td>Composite C1</td><td>/Administration</td><td>admin@<samplestore>.com</td><td>admin</td><td>&nbsp;</td><td>Username may be admin@yourstore.com</td><td>&nbsp;</td></tr>
 <tr><td>Computhink ViewWise</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Concrete5</td><td>/index.php/login (alternatively /dashboard) </td><td>admin</td><td>random set at install</td><td>"Yep, great tip. When you go to logs (after resetting the password), you tick the box for emails sent and click on print view with full text. This opens the email that was sent with the link to set a new password. Click on that link and it will open a new browser window."</td><td>http://exploitsdownload.com/search/concrete5</td></tr>
 <tr><td>Contegro</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>Hosted on Contegro. </td><td>&nbsp;</td></tr>
 <tr><td>Content SORT</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>WP plugin</td><td>&nbsp;</td></tr>
 <tr><td>CoreMedia WCM</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td><- Magic Quadrant Masterbaters</td><td>&nbsp;</td></tr>
 <tr><td>Cotonti</td><td>/admin.php</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/cotonti</td></tr>
 <tr><td>Daisy</td><td>/login</td><td>admin</td><td>admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Django-cms</td><td>/admin</td><td>admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/django</td></tr>
 <tr><td>Dokuwiki</td><td>/dokuwiki?do=login</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/dokuwiki</td></tr>
 <tr><td>Dotclear</td><td>/dotclear/admin/</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/dotclear</td></tr>
 <tr><td>dotCMS</td><td>/admin/</td><td>admin@dotcms.org (pre 1.9.2 test@dotcms.org)</td><td>admin (pre 1.9.2 test)</td><td>http://dotcms.com/docs/1.9/DefaultsOnAnInitialDotCMSInstall</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/dotcms</td></tr>
 <tr><td>DotNetNuke</td><td>Admin login</td><td>admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/dotnetnuke</td></tr>
 <tr><td>Drupal</td><td>/admin or /?q=admin (non-clean) </td><td>admin</td><td>assigned in setup</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/drupal</td></tr>
 <tr><td>DSpace</td><td>(dspace?).site.com/admin </td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>DynPG</td><td>/cms or /dynpg</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/dynpg</td></tr>
 <tr><td>e107</td><td><siteURL>/<Basedir>/e107_admin/admin.php?view.all</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/e107</td></tr>
 <tr><td>Ektron CMS400.Net</td><td>/workarea/login.aspx</td><td>admin</td><td>admin</td><td>documentation.ektron.com/CMS400/v70/adminmanual.pdf</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Elcom CMS</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/elcom</td></tr>
 <tr><td>EMC Documentum ECM</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>EPrints</td><td>/perl/users/home</td><td>admin</td><td>admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Escenic Content Engine</td><td>/escenic/ </td><td><publication>_admin <where publication= the content's name></td><td>Specified by owner</td><td>documentation.vizrt.com/ece-pub-admin-guide-5.4.pdf</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Exponent CMS</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://docs.exponentcms.org/docs/2.0.3/logging-in</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/exponentcms</td></tr>
 <tr><td>ExpressionEngine</td><td>/admin.php or /phpmyadmin/</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search?q=expression+engine</td></tr>
 <tr><td>Exsite Webware</td><td>/cgi-bin/</td><td>admin</td><td>password</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>eZ Publish</td><td>add "_admin" to the end of the frontoffice url</td><td>admin</td><td>password</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search?q=frog+cms</td></tr>
 <tr><td>Fedora</td><td><host>.com:8091 or /login</td><td>admin</td><td>admin</td><td>  </td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Flagship Docs</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Foswiki</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Frog CMS</td><td>/admin/</td><td>admin</td><td>password</td><td>&nbsp;</td><td>creds valid pre 1.0 version</td><td>&nbsp;</td></tr>
 <tr><td>Geeklog</td><td>/admin/</td><td>Admin</td><td>password</td><td>&nbsp;</td><td>valid as of 02, looking for more recent sources. </td><td>&nbsp;</td></tr>
 <tr><td>Habari</td><td>/admin/login.php</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search?q=habari</td></tr>
 <tr><td>Hippo CMS</td><td><Site>.com:8080/cms</td><td>admin</td><td>admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Hyland OnBase ECM</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>Info Behind Paywall</td><td>&nbsp;</td></tr>
 <tr><td>IBM Enterprise Content Management</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>IBM Lotus Web Content Management</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Ikiwiki</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>ImpressCMS</td><td>/admin.php</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Quest Software inSync</td><td>/GoAdmin</td><td>admin</td><td>admin</td><td>&nbsp;</td><td>http://support-public.cfm.software.dell.com/ddbeaa24-9332-4506-bda8-aceeef47af34:602964.pdf</td></tr>
 <tr><td>Jadu</td><td>"/mymicrosite/jadu/</td></tr>
 <tr><td>        </td></tr>
 <tr><td>"</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>JCore</td><td>/admin/</td><td>admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Joomla!</td><td>/administrator or /joomla/administrator</td><td>admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Jumbo</td><td>jumbo/loginpage.php</td><td>admin</td><td>password</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Kajona</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Kentico CMS</td><td>/CMSSiteManager</td><td>administrator</td><td>:blank:</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>KnowledgeTree Community Edition</td><td>/knowledgetree/</td><td>admin</td><td>admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Liferay Community Edition</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>LogicalDOC</td><td>/logicaldoc/webdav/store</td><td>admin</td><td>admin</td><td>&nbsp;</td><td>As of 4.5</td><td>&nbsp;</td></tr>
 <tr><td>Lyceum</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Magnolia</td><td>:8080/magnoliaAuthor/.magnolia.</td><td>superuser</td><td>superuser</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Mambo</td><td>administrator/index.php</td><td>admin</td><td>admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Mediawiki </td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>MiaCMS</td><td>/login.php</td><td>admin</td><td>let_me_in</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Microsoft Office 365</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Microsoft SharePoint Foundation</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Microsoft SharePoint Server</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Midgard CMS</td><td>/midgard</td><td>admin</td><td>password</td><td>http://www.midgard-project.org/documentation/midgard-admin-sitewizard/#36700c60b73acecb128e78b284b2d84e</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>MODx</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>-Weirdness</td><td>&nbsp;</td></tr>
 <tr><td>mojoPortal</td><td>/Secure/Login.aspx</td><td>admin@admin.com</td><td>admin</td><td>http://www.mojoportal.com/installation-quick-start.aspx</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Movable Type</td><td>_mt/mt.cgi</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Mura CMS</td><td>/admin</td><td>admin</td><td>admin</td><td>http://docs.getmura.com/user-guide/users/</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Nucleus CMS</td><td>/nucleus/</td><td>&nbsp;</td><td>&nbsp;</td><td>http://faq.nucleuscms.org/item/80</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Nuxeo EP</td><td>/admin</td><td>Administrator</td><td>Administrator</td><td>http://doc.nuxeo.com/display/NXDOC54/Setup</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>O3spaces</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Ocportal</td><td>/adminzone</td><td>admin</td><td>&nbsp;</td><td>http://ocportal.com/docs5/tut_configuration.htm</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/ocportal</td></tr>
 <tr><td>OpenACS</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>OpenCms</td><td>8080/opencms/opencms/system/login/</td><td>Admin</td><td>admin</td><td>http://www.opencms.org/en/development/installation/server.html</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/opencms</td></tr>
 <tr><td>OpenKM</td><td>/OpenKM</td><td>okmAdmin</td><td>admin</td><td>http://forum.openkm.com/viewtopic.php?f=4&t=3711</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>OpenText ECM Suite</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>OpenText Web Experience Management</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>OpenText Web Site Management</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>OpenWGA</td><td>/admin</td><td>admin</td><td>wga</td><td>http://www.openwga.com/home/support/tutorials/going_live_from_openwga_developer_studio.en.html</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Opus</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/opus</td></tr>
 <tr><td>Oracle ECM Suite</td><td><sitename>.com:7001/console</td><td>&nbsp;</td><td>&nbsp;</td><td>http://docs.oracle.com/cd/E17904_01/doc.1111/e14495/verify.htm#CHDHCEFB</td><td>creds set in setup</td><td>&nbsp;</td></tr>
 <tr><td>Orchard Project</td><td>/Admin/</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>creds set in setup</td><td>&nbsp;</td></tr>
 <tr><td>papaya CMS</td><td>/papaya/</td><td>&nbsp;</td><td>&nbsp;</td><td>http://www.papaya-cms.com</td><td>documentation in german</td><td>&nbsp;</td></tr>
 <tr><td>Peardrop(CMS)</td><td>/admin.php</td><td>admin(?)</td><td>admin</td><td>http://peardrop.coolmediatech.com/index.php/Documentation_%280.1.x%29</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Percussion Software CM1</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Phire CMS</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>PHP-Fusion</td><td>/login.php</td><td>&nbsp;</td><td>&nbsp;</td><td>http://www.php-fusion.co.uk/</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/phpfusion/</td></tr>
 <tr><td>PHP-Nuke</td><td>/nuke/admin.php</td><td>God</td><td>Password</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/phpnuke/</td></tr>
 <tr><td>PHPSlash</td><td> </td><td>god</td><td>password</td><td>http://phpxref.com/xref/phpslash/doc/html/single/phpslash.html.source.html</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/phpslash/</td></tr>
 <tr><td>Phpweblog</td><td>/admin/users.php</td><td>Bypass using securiteam link</td><td>&nbsp;</td><td>http://www.securiteam.com/unixfocus/6K0021P0KE.html</td><td>sitekey:phpweblog</td><td>http://exploitsdownload.com/search/phpweblog/</td></tr>
 <tr><td>phpWebSite</td><td>/admin.php</td><td> admin</td><td>phpwebsite</td><td>hintsforums.macworld.com/archive/index.php/t-10721.html</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/phpwebsite</td></tr>
 <tr><td>phpWiki</td><td>/phpwiki/admin.php</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Pier</td><td><site>.com/?command=PULogin</td><td>admin</td><td>pier</td><td>http://www.piercms.com/doc/faq#193819363</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>pimcore</td><td>/admin</td><td>admin</td><td>admin</td><td>www.pimcore.com</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/pimcore/</td></tr>
 <tr><td>PivotX</td><td>/pivotx</td><td>&nbsp;</td><td>&nbsp;</td><td>http://book.pivotx.net</td><td>user created name/pass</td><td>http://exploitsdownload.com/search/pivotx/</td></tr>
 <tr><td>Pixie (CMS)</td><td>/admin</td><td>admin</td><td>pixie123</td><td>http://www.getpixie.co.uk/support/article/manual-installation/</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>PmWiki</td><td>&nbsp;</td><td>admin</td><td><admin designated></td><td>http://yate.null.ro/pmwiki/index.php?n=PmWiki.PasswordsAdmin</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/pmwiki/</td></tr>
 <tr><td>Polopoly Web CMS</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Prestashop</td><td>/admin or /admin939</td><td>&nbsp;</td><td>&nbsp;</td><td>http://doc.prestashop.com/display/PS14/System+Administrator+Guide</td><td>/admin is renamed upon install</td><td>http://exploitsdownload.com/search/prestashop/</td></tr>
 <tr><td>ProcessWire</td><td>/processwire/</td><td>admin</td><td>processwire2</td><td>http://www.processwire.com</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Pulse CMS</td><td>/pulsepro/</td><td><blank?></td><td>demo</td><td>http://www.pulsecms.com/docs/settings.php</td><td>Couldn't find username</td><td>http://exploitsdownload.com/search/pulsecms/</td></tr>
 <tr><td>Radiant</td><td>/admin/</td><td>admin</td><td>radiant</td><td>http://radiantcms.org</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>RavenNuke CMS</td><td>/admin.php or /ravennuke230/admin.php</td><td>&nbsp;</td><td>&nbsp;</td><td>http://rnwiki.ravennuke.com</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/ravennuke/</td></tr>
 <tr><td>Refinery CMS</td><td>:3000/refinery </td><td>&nbsp;</td><td>&nbsp;</td><td>http://refinerycms.com/guides/getting-started</td><td>No default user </td><td>http://exploitsdownload.com/search/refinery/</td></tr>
 <tr><td>RenovatioCMS</td><td>/?RVGET_document=System+Management</td><td>&nbsp;</td><td>&nbsp;</td><td>www.renovatiocms.com/</td><td>English Site Incomplete </td><td>&nbsp;</td></tr>
 <tr><td>Scoop</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Serendipity</td><td>/serendipity/serendipity_admin.php</td><td>John Doe</td><td>john</td><td>http://www.s9y.org/36.html</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/serendipity</td></tr>
 <tr><td>SilverStripe</td><td>/admin</td><td>admin</td><td>password</td><td>http://doc.silverstripe.org/sapphire/en/topics/configuration</td><td>User can assign defaults in configuration</td><td>http://exploitsdownload.com/search/silverstripe</td></tr>
 <tr><td>Sitecore Professional Edition</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/sitecore</td></tr>
 <tr><td>Sitefinity CMS</td><td>/Sitefinity/LoginPages/LoginForm</td><td>admin</td><td>Password</td><td>http://www.sitefinity.com/devnet/kb.aspx</td><td>If you see telerik.rad it's sitefinity</td><td>http://exploitsdownload.com/search/sitefinity</td></tr>
 <tr><td>Sitekit CMS</td><td>/admin</td><td>&nbsp;</td><td>&nbsp;</td><td>http://www.sitekit.net</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>SMW+</td><td>&nbsp;</td><td>root</td><td>m8nix</td><td>http://www.smwplus.com/index.php/Help:SMW%2B</td><td>&nbsp;</td><td>http://exploitsdownload.com/search/smwplus</td></tr>
 <tr><td>SPIP</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Squiz CMS</td><td>/_edit</td><td>admin/editor/approver</td><td>password</td><td>http://cms.squizsuite.net/quick-start-guide/</td><td>admin password should be changed</td><td>http://exploitsdownload.com/search?q=squiz</td></tr>
 <tr><td>Squiz Matrix</td><td>/_admin</td><td>root</td><td>root</td><td>http://matrix.squizsuite.net/quick-start-guide/</td><td>&nbsp;</td><td>http://exploitsdownload.com/search?q=squiz</td></tr>
 <tr><td>TangoCMS</td><td>index.php?url=session or /session</td><td>&nbsp;</td><td>&nbsp;</td><td>http://tangocms.org/announcements?page=2</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Telligent Community</td><td>/telligent_evolution</td><td>admin</td><td>pa$$word</td><td>&nbsp;</td><td>check for /solr/admin</td><td>&nbsp;</td></tr>
 <tr><td>Textpattern</td><td>/textpattern/index.php or /textpattern/</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>http://exploitsdownload.com/search?q=textpattern</td></tr>
 <tr><td>Tiki Wiki CMS Groupware</td><td>/tiki/tiki-login_scr.php</td><td>admin</td><td>admin</td><td>http://doc.tiki.org/Admin+Problems</td><td>&nbsp;</td><td>http://exploitsdownload.com/search?q=tikiwiki</td></tr>
 <tr><td>Titan CMS</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Tribiq CMS</td><td>/admin</td><td><user assigned></td><td><user assigned></td><td>tribiq.com/tribiq-6-documentation-installation.download</td><td>&nbsp;</td><td>http://exploitsdownload.com/search?q=tribiq</td></tr>
 <tr><td>TWiki</td><td>/cgi-bin/login</td><td>admin</td><td>&nbsp;</td><td>http://twiki.org/</td><td>&nbsp;</td><td>http://exploitsdownload.com/search?q=twiki</td></tr>
 <tr><td>Typo</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>TYPO3</td><td>/typo3</td><td>admin</td><td>password</td><td>http://wiki.typo3.org/TYPO3_Installation_Basics</td><td>&nbsp;</td><td>http://exploitsdownload.com/search?q=typo3</td></tr>
 <tr><td>uCoz</td><td>/admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Umbraco</td><td>/umbraco/login.aspx</td><td>admin</td><td>default</td><td>http://our.umbraco.org/</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>VosaoCMS</td><td>/cms</td><td>admin@test.com</td><td>admin</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>WebGUI</td><td>&nbsp;</td><td>root</td><td><user assigned></td><td>&nbsp;</td><td>&nbsp;</td><td>http://www.exploitsdownload.com/search?q=webgui</td></tr>
 <tr><td>Webnodes CMS</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>WolfCMS</td><td><wolfpath>/admin/</td><td><random></td><td><random></td><td>http://www.wolfcms.org/wiki/books:administration</td><td>&nbsp;</td><td>http://www.exploitsdownload.com/search?q=wolfCMS</td></tr>
 <tr><td>WordPress</td><td>/wp-admin/</td><td>admin</td><td><random></td><td>http://codex.wordpress.org/</td><td>Why are you looking HERE for WP?</td><td>http://www.exploitsdownload.com/search?q=Wordpress</td></tr>
 <tr><td>Wuzly</td><td>/admin/login.php</td><td>Administrator</td><td>100</td><td>&nbsp;</td><td>&nbsp;</td><td>http://osvdb.com/search/search?search[vuln_title]=wuzly</td></tr>
 <tr><td>Xaraya</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>XOOPS</td><td>/admin.php</td><td>admin</td><td>admin</td><td>xoops.org</td><td>&nbsp;</td><td>http://www.exploitsdownload.com/search?q=XOOPS</td></tr>
 <tr><td>Xpress Engine</td><td>/index.php?module=admin</td><td><userassigned></td><td><user assigned></td><td>http://xpressengine.org</td><td>&nbsp;</td><td>http://www.exploitsdownload.com/search?q=XpressEngine</td></tr>
 <tr><td>Yanel</td><td><site>.com:8080/yanel/</td><td>&nbsp;</td><td>&nbsp;</td><td>http://yanel.wyona.org/en/documentation/index.html</td><td>&nbsp;</td><td>&nbsp;</td></tr>
 <tr><td>Zikula</td><td>/admin.php or user.php</td><td>&nbsp;</td><td>&nbsp;</td><td>http://phpxref.zikula.de/nav.html?system/Admin/lib/Admin/Controller/Admin.php.html</td><td>&nbsp;</td><td>http://www.cvedetails.com/vulnerability-list/vendor_id-10810/Zikula.html</td></tr>
 <tr><td>Zotonic</td><td>&nbsp;</td><td>admin</td><td>admin</td><td>&nbsp;</td><td>Written in Erlang</td><td></td></tr></table>
