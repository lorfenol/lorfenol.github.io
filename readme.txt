atc123@linux-Lor:/home/sites$ ll
total 8
drwxrwxrwx 2 root   root   4096 nov.   5 13:15 ./
drwxr-xr-x 4 root   root   4096 nov.   5 13:13 ../
-rw-rw-r-- 1 atc123 atc123    0 nov.   5 13:15 readme.txt
atc123@linux-Lor:/home/sites$ sudo apt-get update
[sudo] password for atc123: 
Atteint http://fr.archive.ubuntu.com vivid InRelease                      
Atteint http://security.ubuntu.com vivid-security InRelease               
Atteint http://fr.archive.ubuntu.com vivid-updates InRelease          
Atteint http://fr.archive.ubuntu.com vivid-backports InRelease                 
Atteint http://security.ubuntu.com vivid-security/main Sources                 
Atteint http://fr.archive.ubuntu.com vivid/main Sources                        
Atteint http://security.ubuntu.com vivid-security/restricted Sources           
Atteint http://fr.archive.ubuntu.com vivid/restricted Sources                  
Atteint http://security.ubuntu.com vivid-security/universe Sources             
Atteint http://fr.archive.ubuntu.com vivid/universe Sources                    
Atteint http://security.ubuntu.com vivid-security/multiverse Sources           
Atteint http://fr.archive.ubuntu.com vivid/multiverse Sources                  
Atteint http://security.ubuntu.com vivid-security/main i386 Packages           
Atteint http://fr.archive.ubuntu.com vivid/main i386 Packages                  
Atteint http://security.ubuntu.com vivid-security/restricted i386 Packages     
Atteint http://fr.archive.ubuntu.com vivid/restricted i386 Packages            
Atteint http://security.ubuntu.com vivid-security/universe i386 Packages       
Atteint http://fr.archive.ubuntu.com vivid/universe i386 Packages              
Atteint http://security.ubuntu.com vivid-security/multiverse i386 Packages     
Atteint http://fr.archive.ubuntu.com vivid/multiverse i386 Packages            
Atteint http://security.ubuntu.com vivid-security/main Translation-en          
Atteint http://fr.archive.ubuntu.com vivid/main Translation-fr                 
Atteint http://security.ubuntu.com vivid-security/multiverse Translation-en    
Atteint http://fr.archive.ubuntu.com vivid/main Translation-en                 
Atteint http://fr.archive.ubuntu.com vivid/multiverse Translation-fr           
Atteint http://security.ubuntu.com vivid-security/restricted Translation-en    
Atteint http://fr.archive.ubuntu.com vivid/multiverse Translation-en           
Atteint http://security.ubuntu.com vivid-security/universe Translation-en      
Atteint http://fr.archive.ubuntu.com vivid/restricted Translation-fr           
Atteint http://fr.archive.ubuntu.com vivid/restricted Translation-en           
Atteint http://fr.archive.ubuntu.com vivid/universe Translation-fr             
Atteint http://fr.archive.ubuntu.com vivid/universe Translation-en             
Atteint http://fr.archive.ubuntu.com vivid-updates/main Sources                
Atteint http://fr.archive.ubuntu.com vivid-updates/restricted Sources          
Atteint http://fr.archive.ubuntu.com vivid-updates/universe Sources            
Atteint http://fr.archive.ubuntu.com vivid-updates/multiverse Sources          
Atteint http://fr.archive.ubuntu.com vivid-updates/main i386 Packages          
Atteint http://fr.archive.ubuntu.com vivid-updates/restricted i386 Packages    
Atteint http://fr.archive.ubuntu.com vivid-updates/universe i386 Packages      
Atteint http://fr.archive.ubuntu.com vivid-updates/multiverse i386 Packages    
Atteint http://fr.archive.ubuntu.com vivid-updates/main Translation-en         
Atteint http://fr.archive.ubuntu.com vivid-updates/multiverse Translation-en   
Atteint http://fr.archive.ubuntu.com vivid-updates/restricted Translation-en   
Atteint http://fr.archive.ubuntu.com vivid-updates/universe Translation-en     
Atteint http://fr.archive.ubuntu.com vivid-backports/main Sources              
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted Sources        
Atteint http://fr.archive.ubuntu.com vivid-backports/universe Sources          
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse Sources        
Atteint http://fr.archive.ubuntu.com vivid-backports/main i386 Packages        
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted i386 Packages  
Atteint http://fr.archive.ubuntu.com vivid-backports/universe i386 Packages    
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse i386 Packages  
Atteint http://fr.archive.ubuntu.com vivid-backports/main Translation-en       
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse Translation-en 
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted Translation-en 
Atteint http://fr.archive.ubuntu.com vivid-backports/universe Translation-en   
Lecture des listes de paquets... Fait                                          
atc123@linux-Lor:/home/sites$ sudo apt-get install jekyll
Lecture des listes de paquets... Fait
Construction de l'arbre des dépendances       
Lecture des informations d'état... Fait
Les paquets supplémentaires suivants seront installés : 
  javascript-common libc-ares2 libgsl0ldbl libjs-coffeescript libplot2c2
  libpq5 libruby2.1 libtamuanova-0.2 libv8-3.14.5 libyaml-0-2 nodejs plotutils
  python-pygments ruby ruby-afm ruby-ascii85 ruby-blankslate ruby-celluloid
  ruby-classifier ruby-coderay ruby-coffee-script ruby-coffee-script-source
  ruby-colorator ruby-execjs ruby-fast-stemmer ruby-ffi ruby-gsl ruby-hashery
  ruby-jekyll-coffeescript ruby-jekyll-gist ruby-jekyll-paginate
  ruby-jekyll-sass-converter ruby-jekyll-watch ruby-json ruby-kramdown
  ruby-liquid ruby-listen ruby-mercenary ruby-multi-json ruby-mysql
  ruby-narray ruby-oj ruby-parslet ruby-pdf-core ruby-pdf-reader ruby-pg
  ruby-posix-spawn ruby-prawn ruby-prawn-table ruby-pygments.rb
  ruby-rb-inotify ruby-rc4 ruby-redcarpet ruby-rouge ruby-safe-yaml ruby-sass
  ruby-sequel ruby-sequel-pg ruby-stringex ruby-timers ruby-toml ruby-ttfunk
  ruby-yajl ruby2.1 rubygems-integration
Paquets suggérés :
  gsl-ref-psdoc gsl-doc-pdf gsl-doc-info gsl-ref-html coffeescript
  ttf-bitstream-vera ri ruby-dev coderay fonts-arphic-gkai00mp
  ruby-pdf-inspector ruby-prawn-doc ruby-compass ttf-dejavu-core bundler
Les NOUVEAUX paquets suivants seront installés :
  javascript-common jekyll libc-ares2 libgsl0ldbl libjs-coffeescript
  libplot2c2 libpq5 libruby2.1 libtamuanova-0.2 libv8-3.14.5 libyaml-0-2
  nodejs plotutils python-pygments ruby ruby-afm ruby-ascii85 ruby-blankslate
  ruby-celluloid ruby-classifier ruby-coderay ruby-coffee-script
  ruby-coffee-script-source ruby-colorator ruby-execjs ruby-fast-stemmer
  ruby-ffi ruby-gsl ruby-hashery ruby-jekyll-coffeescript ruby-jekyll-gist
  ruby-jekyll-paginate ruby-jekyll-sass-converter ruby-jekyll-watch ruby-json
  ruby-kramdown ruby-liquid ruby-listen ruby-mercenary ruby-multi-json
  ruby-mysql ruby-narray ruby-oj ruby-parslet ruby-pdf-core ruby-pdf-reader
  ruby-pg ruby-posix-spawn ruby-prawn ruby-prawn-table ruby-pygments.rb
  ruby-rb-inotify ruby-rc4 ruby-redcarpet ruby-rouge ruby-safe-yaml ruby-sass
  ruby-sequel ruby-sequel-pg ruby-stringex ruby-timers ruby-toml ruby-ttfunk
  ruby-yajl ruby2.1 rubygems-integration
0 mis à jour, 66 nouvellement installés, 0 à enlever et 217 non mis à jour.
Il est nécessaire de prendre 12,3 Mo dans les archives.
Après cette opération, 52,5 Mo d'espace disque supplémentaires seront utilisés.
Souhaitez-vous continuer ? [O/n] o
Réception de : 1 http://fr.archive.ubuntu.com/ubuntu/ vivid-updates/main libpq5 i386 9.4.5-0ubuntu0.15.04 [83,3 kB]
Réception de : 2 http://fr.archive.ubuntu.com/ubuntu/ vivid/main libyaml-0-2 i386 0.1.6-3 [49,1 kB]
Réception de : 3 http://fr.archive.ubuntu.com/ubuntu/ vivid/main libc-ares2 i386 1.10.0-2 [38,3 kB]
Réception de : 4 http://fr.archive.ubuntu.com/ubuntu/ vivid/main javascript-common all 11 [6 066 B]
Réception de : 5 http://fr.archive.ubuntu.com/ubuntu/ vivid/main rubygems-integration all 1.8 [4 576 B]
Réception de : 6 http://fr.archive.ubuntu.com/ubuntu/ vivid/main libruby2.1 i386 2.1.2-2ubuntu3 [3 231 kB]
Réception de : 7 http://fr.archive.ubuntu.com/ubuntu/ vivid/main ruby2.1 i386 2.1.2-2ubuntu3 [70,7 kB]
Réception de : 8 http://fr.archive.ubuntu.com/ubuntu/ vivid/main ruby all 1:2.1.0.4ubuntu1 [5 940 B]
Réception de : 9 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-liquid all 2.6.1-2 [22,9 kB]
Réception de : 10 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-ascii85 all 1.0.2-3 [9 004 B]
Réception de : 11 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-rc4 all 0.1.5-2build1 [3 970 B]
Réception de : 12 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-afm all 0.2.2-1 [5 350 B]
Réception de : 13 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-hashery all 2.1.1-1 [29,3 kB]
Réception de : 14 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-ttfunk all 1.4.0-1 [23,7 kB]
Réception de : 15 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-pdf-reader all 1.3.3-1 [125 kB]
Réception de : 16 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-pdf-core all 0.4.0-1 [18,0 kB]
Réception de : 17 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-prawn all 1.3.0+dfsg-1 [277 kB]
Réception de : 18 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-prawn-table all 0.2.0-1 [96,6 kB]
Réception de : 19 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-coderay all 1.1.0-2 [75,6 kB]
Réception de : 20 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-stringex all 2.5.2-2 [84,2 kB]
Réception de : 21 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-kramdown all 1.4.2-2 [370 kB]
Réception de : 22 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-mercenary all 0.3.4-1 [11,0 kB]
Réception de : 23 http://fr.archive.ubuntu.com/ubuntu/ vivid/main ruby-safe-yaml all 1.0.3-1 [17,5 kB]
Réception de : 24 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-colorator all 0.1-3 [3 886 B]
Réception de : 25 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-fast-stemmer i386 1.0.2-1build2 [7 830 B]
Réception de : 26 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-classifier all 1.3.4-2 [14,0 kB]
Réception de : 27 http://fr.archive.ubuntu.com/ubuntu/ vivid/main python-pygments all 2.0.1+dfsg-1svn1 [468 kB]
Réception de : 28 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-posix-spawn i386 0.3.9-1 [24,4 kB]
Réception de : 29 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-yajl i386 1.2.0-2build1 [35,4 kB]
Réception de : 30 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-pygments.rb all 0.5.4~ds1-3 [276 kB]
Réception de : 31 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-redcarpet i386 3.1.2-1build1 [47,1 kB]
Réception de : 32 http://fr.archive.ubuntu.com/ubuntu/ vivid/main ruby-blankslate all 2.1.2.4-4build1 [4 426 B]
Réception de : 33 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-parslet all 1.6.1-1 [47,9 kB]
Réception de : 34 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-toml all 0.1.1-1 [7 996 B]
Réception de : 35 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-jekyll-paginate all 1.0.0-1 [5 814 B]
Réception de : 36 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-jekyll-gist all 1.1.0-1 [4 274 B]
Réception de : 37 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe libjs-coffeescript all 1.4.0-1.1 [65,1 kB]
Réception de : 38 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-coffee-script-source all 1.3.3-2 [3 216 B]
Réception de : 39 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-multi-json all 1.10.1-1 [15,8 kB]
Réception de : 40 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe libv8-3.14.5 i386 3.14.5.8-5ubuntu2 [1 192 kB]
Réception de : 41 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe nodejs i386 0.10.25~dfsg2-2ubuntu1 [689 kB]
Réception de : 42 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-execjs all 2.2.1-1 [13,9 kB]
Réception de : 43 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-coffee-script all 2.2.0-2 [4 000 B]
Réception de : 44 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-jekyll-coffeescript all 1.0.0-1 [3 868 B]
Réception de : 45 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-sass all 3.4.6-2 [169 kB]
Réception de : 46 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-jekyll-sass-converter all 1.0.0-2 [4 488 B]
Réception de : 47 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-jekyll-watch all 1.0.0-1 [4 030 B]
Réception de : 48 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe jekyll all 2.2.0+dfsg-2 [52,5 kB]
Réception de : 49 http://fr.archive.ubuntu.com/ubuntu/ vivid/main libgsl0ldbl i386 1.16+dfsg-2build1 [775 kB]
Réception de : 50 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe libplot2c2 i386 2.6-3ubuntu1 [894 kB]
Réception de : 51 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe libtamuanova-0.2 i386 0.2-3 [8 032 B]
Réception de : 52 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe plotutils i386 2.6-3ubuntu1 [649 kB]
Réception de : 53 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-timers all 1.1.0-2 [4 854 B]
Réception de : 54 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-celluloid all 0.15.2-2 [36,8 kB]
Réception de : 55 http://fr.archive.ubuntu.com/ubuntu/ vivid/main ruby-ffi i386 1.9.6debian-2 [79,6 kB]
Réception de : 56 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-narray i386 0.6.0.9-1build1 [77,6 kB]
Réception de : 57 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-gsl i386 1.15.3+dfsg-2build1 [502 kB]
Réception de : 58 http://fr.archive.ubuntu.com/ubuntu/ vivid/main ruby-json i386 1.8.1-1build1 [43,5 kB]
Réception de : 59 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-listen all 2.4.0-4 [14,0 kB]
Réception de : 60 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-mysql i386 2.9.1-1build1 [43,6 kB]
Réception de : 61 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-oj i386 2.10.3-2build1 [83,1 kB]
Réception de : 62 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-pg i386 0.17.1-2 [324 kB]
Réception de : 63 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-rb-inotify all 0.9.5-1 [11,0 kB]
Réception de : 64 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-rouge all 1.5.1-1 [135 kB]
Réception de : 65 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-sequel all 4.15.0-1 [762 kB]
Réception de : 66 http://fr.archive.ubuntu.com/ubuntu/ vivid/universe ruby-sequel-pg i386 1.6.10-1 [20,1 kB]
12,3 Mo réceptionnés en 15s (771 ko/s)                                         
Extraction des modèles depuis les paquets : 100%
Sélection du paquet libpq5:i386 précédemment désélectionné.
(Lecture de la base de données... 157431 fichiers et répertoires déjà installés.)
Préparation du dépaquetage de .../libpq5_9.4.5-0ubuntu0.15.04_i386.deb ...
Dépaquetage de libpq5:i386 (9.4.5-0ubuntu0.15.04) ...
Sélection du paquet libyaml-0-2:i386 précédemment désélectionné.
Préparation du dépaquetage de .../libyaml-0-2_0.1.6-3_i386.deb ...
Dépaquetage de libyaml-0-2:i386 (0.1.6-3) ...
Sélection du paquet libc-ares2:i386 précédemment désélectionné.
Préparation du dépaquetage de .../libc-ares2_1.10.0-2_i386.deb ...
Dépaquetage de libc-ares2:i386 (1.10.0-2) ...
Sélection du paquet javascript-common précédemment désélectionné.
Préparation du dépaquetage de .../javascript-common_11_all.deb ...
Dépaquetage de javascript-common (11) ...
Sélection du paquet rubygems-integration précédemment désélectionné.
Préparation du dépaquetage de .../rubygems-integration_1.8_all.deb ...
Dépaquetage de rubygems-integration (1.8) ...
Sélection du paquet libruby2.1:i386 précédemment désélectionné.
Préparation du dépaquetage de .../libruby2.1_2.1.2-2ubuntu3_i386.deb ...
Dépaquetage de libruby2.1:i386 (2.1.2-2ubuntu3) ...
Sélection du paquet ruby2.1 précédemment désélectionné.
Préparation du dépaquetage de .../ruby2.1_2.1.2-2ubuntu3_i386.deb ...
Dépaquetage de ruby2.1 (2.1.2-2ubuntu3) ...
Sélection du paquet ruby précédemment désélectionné.
Préparation du dépaquetage de .../ruby_1%3a2.1.0.4ubuntu1_all.deb ...
Dépaquetage de ruby (1:2.1.0.4ubuntu1) ...
Sélection du paquet ruby-liquid précédemment désélectionné.
Préparation du dépaquetage de .../ruby-liquid_2.6.1-2_all.deb ...
Dépaquetage de ruby-liquid (2.6.1-2) ...
Sélection du paquet ruby-ascii85 précédemment désélectionné.
Préparation du dépaquetage de .../ruby-ascii85_1.0.2-3_all.deb ...
Dépaquetage de ruby-ascii85 (1.0.2-3) ...
Sélection du paquet ruby-rc4 précédemment désélectionné.
Préparation du dépaquetage de .../ruby-rc4_0.1.5-2build1_all.deb ...
Dépaquetage de ruby-rc4 (0.1.5-2build1) ...
Sélection du paquet ruby-afm précédemment désélectionné.
Préparation du dépaquetage de .../ruby-afm_0.2.2-1_all.deb ...
Dépaquetage de ruby-afm (0.2.2-1) ...
Sélection du paquet ruby-hashery précédemment désélectionné.
Préparation du dépaquetage de .../ruby-hashery_2.1.1-1_all.deb ...
Dépaquetage de ruby-hashery (2.1.1-1) ...
Sélection du paquet ruby-ttfunk précédemment désélectionné.
Préparation du dépaquetage de .../ruby-ttfunk_1.4.0-1_all.deb ...
Dépaquetage de ruby-ttfunk (1.4.0-1) ...
Sélection du paquet ruby-pdf-reader précédemment désélectionné.
Préparation du dépaquetage de .../ruby-pdf-reader_1.3.3-1_all.deb ...
Dépaquetage de ruby-pdf-reader (1.3.3-1) ...
Sélection du paquet ruby-pdf-core précédemment désélectionné.
Préparation du dépaquetage de .../ruby-pdf-core_0.4.0-1_all.deb ...
Dépaquetage de ruby-pdf-core (0.4.0-1) ...
Sélection du paquet ruby-prawn précédemment désélectionné.
Préparation du dépaquetage de .../ruby-prawn_1.3.0+dfsg-1_all.deb ...
Dépaquetage de ruby-prawn (1.3.0+dfsg-1) ...
Sélection du paquet ruby-prawn-table précédemment désélectionné.
Préparation du dépaquetage de .../ruby-prawn-table_0.2.0-1_all.deb ...
Dépaquetage de ruby-prawn-table (0.2.0-1) ...
Sélection du paquet ruby-coderay précédemment désélectionné.
Préparation du dépaquetage de .../ruby-coderay_1.1.0-2_all.deb ...
Dépaquetage de ruby-coderay (1.1.0-2) ...
Sélection du paquet ruby-stringex précédemment désélectionné.
Préparation du dépaquetage de .../ruby-stringex_2.5.2-2_all.deb ...
Dépaquetage de ruby-stringex (2.5.2-2) ...
Sélection du paquet ruby-kramdown précédemment désélectionné.
Préparation du dépaquetage de .../ruby-kramdown_1.4.2-2_all.deb ...
Dépaquetage de ruby-kramdown (1.4.2-2) ...
Sélection du paquet ruby-mercenary précédemment désélectionné.
Préparation du dépaquetage de .../ruby-mercenary_0.3.4-1_all.deb ...
Dépaquetage de ruby-mercenary (0.3.4-1) ...
Sélection du paquet ruby-safe-yaml précédemment désélectionné.
Préparation du dépaquetage de .../ruby-safe-yaml_1.0.3-1_all.deb ...
Dépaquetage de ruby-safe-yaml (1.0.3-1) ...
Sélection du paquet ruby-colorator précédemment désélectionné.
Préparation du dépaquetage de .../ruby-colorator_0.1-3_all.deb ...
Dépaquetage de ruby-colorator (0.1-3) ...
Sélection du paquet ruby-fast-stemmer précédemment désélectionné.
Préparation du dépaquetage de .../ruby-fast-stemmer_1.0.2-1build2_i386.deb ...
Dépaquetage de ruby-fast-stemmer (1.0.2-1build2) ...
Sélection du paquet ruby-classifier précédemment désélectionné.
Préparation du dépaquetage de .../ruby-classifier_1.3.4-2_all.deb ...
Dépaquetage de ruby-classifier (1.3.4-2) ...
Sélection du paquet python-pygments précédemment désélectionné.
Préparation du dépaquetage de .../python-pygments_2.0.1+dfsg-1svn1_all.deb ...
Dépaquetage de python-pygments (2.0.1+dfsg-1svn1) ...
Sélection du paquet ruby-posix-spawn précédemment désélectionné.
Préparation du dépaquetage de .../ruby-posix-spawn_0.3.9-1_i386.deb ...
Dépaquetage de ruby-posix-spawn (0.3.9-1) ...
Sélection du paquet ruby-yajl précédemment désélectionné.
Préparation du dépaquetage de .../ruby-yajl_1.2.0-2build1_i386.deb ...
Dépaquetage de ruby-yajl (1.2.0-2build1) ...
Sélection du paquet ruby-pygments.rb précédemment désélectionné.
Préparation du dépaquetage de .../ruby-pygments.rb_0.5.4~ds1-3_all.deb ...
Dépaquetage de ruby-pygments.rb (0.5.4~ds1-3) ...
Sélection du paquet ruby-redcarpet précédemment désélectionné.
Préparation du dépaquetage de .../ruby-redcarpet_3.1.2-1build1_i386.deb ...
Dépaquetage de ruby-redcarpet (3.1.2-1build1) ...
Sélection du paquet ruby-blankslate précédemment désélectionné.
Préparation du dépaquetage de .../ruby-blankslate_2.1.2.4-4build1_all.deb ...
Dépaquetage de ruby-blankslate (2.1.2.4-4build1) ...
Sélection du paquet ruby-parslet précédemment désélectionné.
Préparation du dépaquetage de .../ruby-parslet_1.6.1-1_all.deb ...
Dépaquetage de ruby-parslet (1.6.1-1) ...
Sélection du paquet ruby-toml précédemment désélectionné.
Préparation du dépaquetage de .../ruby-toml_0.1.1-1_all.deb ...
Dépaquetage de ruby-toml (0.1.1-1) ...
Sélection du paquet ruby-jekyll-paginate précédemment désélectionné.
Préparation du dépaquetage de .../ruby-jekyll-paginate_1.0.0-1_all.deb ...
Dépaquetage de ruby-jekyll-paginate (1.0.0-1) ...
Sélection du paquet ruby-jekyll-gist précédemment désélectionné.
Préparation du dépaquetage de .../ruby-jekyll-gist_1.1.0-1_all.deb ...
Dépaquetage de ruby-jekyll-gist (1.1.0-1) ...
Sélection du paquet libjs-coffeescript précédemment désélectionné.
Préparation du dépaquetage de .../libjs-coffeescript_1.4.0-1.1_all.deb ...
Dépaquetage de libjs-coffeescript (1.4.0-1.1) ...
Sélection du paquet ruby-coffee-script-source précédemment désélectionné.
Préparation du dépaquetage de .../ruby-coffee-script-source_1.3.3-2_all.deb ...
Dépaquetage de ruby-coffee-script-source (1.3.3-2) ...
Sélection du paquet ruby-multi-json précédemment désélectionné.
Préparation du dépaquetage de .../ruby-multi-json_1.10.1-1_all.deb ...
Dépaquetage de ruby-multi-json (1.10.1-1) ...
Sélection du paquet libv8-3.14.5 précédemment désélectionné.
Préparation du dépaquetage de .../libv8-3.14.5_3.14.5.8-5ubuntu2_i386.deb ...
Dépaquetage de libv8-3.14.5 (3.14.5.8-5ubuntu2) ...
Sélection du paquet nodejs précédemment désélectionné.
Préparation du dépaquetage de .../nodejs_0.10.25~dfsg2-2ubuntu1_i386.deb ...
Dépaquetage de nodejs (0.10.25~dfsg2-2ubuntu1) ...
Sélection du paquet ruby-execjs précédemment désélectionné.
Préparation du dépaquetage de .../ruby-execjs_2.2.1-1_all.deb ...
Dépaquetage de ruby-execjs (2.2.1-1) ...
Sélection du paquet ruby-coffee-script précédemment désélectionné.
Préparation du dépaquetage de .../ruby-coffee-script_2.2.0-2_all.deb ...
Dépaquetage de ruby-coffee-script (2.2.0-2) ...
Sélection du paquet ruby-jekyll-coffeescript précédemment désélectionné.
Préparation du dépaquetage de .../ruby-jekyll-coffeescript_1.0.0-1_all.deb ...
Dépaquetage de ruby-jekyll-coffeescript (1.0.0-1) ...
Sélection du paquet ruby-sass précédemment désélectionné.
Préparation du dépaquetage de .../ruby-sass_3.4.6-2_all.deb ...
Dépaquetage de ruby-sass (3.4.6-2) ...
Sélection du paquet ruby-jekyll-sass-converter précédemment désélectionné.
Préparation du dépaquetage de .../ruby-jekyll-sass-converter_1.0.0-2_all.deb ...
Dépaquetage de ruby-jekyll-sass-converter (1.0.0-2) ...
Sélection du paquet ruby-jekyll-watch précédemment désélectionné.
Préparation du dépaquetage de .../ruby-jekyll-watch_1.0.0-1_all.deb ...
Dépaquetage de ruby-jekyll-watch (1.0.0-1) ...
Sélection du paquet jekyll précédemment désélectionné.
Préparation du dépaquetage de .../jekyll_2.2.0+dfsg-2_all.deb ...
Dépaquetage de jekyll (2.2.0+dfsg-2) ...
Sélection du paquet libgsl0ldbl précédemment désélectionné.
Préparation du dépaquetage de .../libgsl0ldbl_1.16+dfsg-2build1_i386.deb ...
Dépaquetage de libgsl0ldbl (1.16+dfsg-2build1) ...
Sélection du paquet libplot2c2 précédemment désélectionné.
Préparation du dépaquetage de .../libplot2c2_2.6-3ubuntu1_i386.deb ...
Dépaquetage de libplot2c2 (2.6-3ubuntu1) ...
Sélection du paquet libtamuanova-0.2 précédemment désélectionné.
Préparation du dépaquetage de .../libtamuanova-0.2_0.2-3_i386.deb ...
Dépaquetage de libtamuanova-0.2 (0.2-3) ...
Sélection du paquet plotutils précédemment désélectionné.
Préparation du dépaquetage de .../plotutils_2.6-3ubuntu1_i386.deb ...
Dépaquetage de plotutils (2.6-3ubuntu1) ...
Sélection du paquet ruby-timers précédemment désélectionné.
Préparation du dépaquetage de .../ruby-timers_1.1.0-2_all.deb ...
Dépaquetage de ruby-timers (1.1.0-2) ...
Sélection du paquet ruby-celluloid précédemment désélectionné.
Préparation du dépaquetage de .../ruby-celluloid_0.15.2-2_all.deb ...
Dépaquetage de ruby-celluloid (0.15.2-2) ...
Sélection du paquet ruby-ffi précédemment désélectionné.
Préparation du dépaquetage de .../ruby-ffi_1.9.6debian-2_i386.deb ...
Dépaquetage de ruby-ffi (1.9.6debian-2) ...
Sélection du paquet ruby-narray précédemment désélectionné.
Préparation du dépaquetage de .../ruby-narray_0.6.0.9-1build1_i386.deb ...
Dépaquetage de ruby-narray (0.6.0.9-1build1) ...
Sélection du paquet ruby-gsl précédemment désélectionné.
Préparation du dépaquetage de .../ruby-gsl_1.15.3+dfsg-2build1_i386.deb ...
Dépaquetage de ruby-gsl (1.15.3+dfsg-2build1) ...
Sélection du paquet ruby-json précédemment désélectionné.
Préparation du dépaquetage de .../ruby-json_1.8.1-1build1_i386.deb ...
Dépaquetage de ruby-json (1.8.1-1build1) ...
Sélection du paquet ruby-listen précédemment désélectionné.
Préparation du dépaquetage de .../ruby-listen_2.4.0-4_all.deb ...
Dépaquetage de ruby-listen (2.4.0-4) ...
Sélection du paquet ruby-mysql précédemment désélectionné.
Préparation du dépaquetage de .../ruby-mysql_2.9.1-1build1_i386.deb ...
Dépaquetage de ruby-mysql (2.9.1-1build1) ...
Sélection du paquet ruby-oj précédemment désélectionné.
Préparation du dépaquetage de .../ruby-oj_2.10.3-2build1_i386.deb ...
Dépaquetage de ruby-oj (2.10.3-2build1) ...
Sélection du paquet ruby-pg précédemment désélectionné.
Préparation du dépaquetage de .../ruby-pg_0.17.1-2_i386.deb ...
Dépaquetage de ruby-pg (0.17.1-2) ...
Sélection du paquet ruby-rb-inotify précédemment désélectionné.
Préparation du dépaquetage de .../ruby-rb-inotify_0.9.5-1_all.deb ...
Dépaquetage de ruby-rb-inotify (0.9.5-1) ...
Sélection du paquet ruby-rouge précédemment désélectionné.
Préparation du dépaquetage de .../ruby-rouge_1.5.1-1_all.deb ...
Dépaquetage de ruby-rouge (1.5.1-1) ...
Sélection du paquet ruby-sequel précédemment désélectionné.
Préparation du dépaquetage de .../ruby-sequel_4.15.0-1_all.deb ...
Dépaquetage de ruby-sequel (4.15.0-1) ...
Sélection du paquet ruby-sequel-pg précédemment désélectionné.
Préparation du dépaquetage de .../ruby-sequel-pg_1.6.10-1_i386.deb ...
Dépaquetage de ruby-sequel-pg (1.6.10-1) ...
Traitement des actions différées (« triggers ») pour man-db (2.7.0.2-5) ...
Traitement des actions différées (« triggers ») pour doc-base (0.10.6) ...
Traitement de 5 fichiers de documentation ajoutés…
Traitement des actions différées (« triggers ») pour install-info (5.2.0.dfsg.1-6) ...
Paramétrage de libpq5:i386 (9.4.5-0ubuntu0.15.04) ...
Paramétrage de libyaml-0-2:i386 (0.1.6-3) ...
Paramétrage de libc-ares2:i386 (1.10.0-2) ...
Paramétrage de javascript-common (11) ...
apache2_invoke: Enable configuration javascript-common
Paramétrage de rubygems-integration (1.8) ...
Paramétrage de python-pygments (2.0.1+dfsg-1svn1) ...
Paramétrage de libjs-coffeescript (1.4.0-1.1) ...
Paramétrage de libv8-3.14.5 (3.14.5.8-5ubuntu2) ...
Paramétrage de nodejs (0.10.25~dfsg2-2ubuntu1) ...
update-alternatives: utilisation de « /usr/bin/nodejs » pour fournir « /usr/bin/js » (js) en mode automatique
Paramétrage de libgsl0ldbl (1.16+dfsg-2build1) ...
Paramétrage de libplot2c2 (2.6-3ubuntu1) ...
Paramétrage de libtamuanova-0.2 (0.2-3) ...
Paramétrage de plotutils (2.6-3ubuntu1) ...
Paramétrage de ruby2.1 (2.1.2-2ubuntu3) ...
Paramétrage de ruby (1:2.1.0.4ubuntu1) ...
Paramétrage de ruby-liquid (2.6.1-2) ...
Paramétrage de ruby-ascii85 (1.0.2-3) ...
Paramétrage de ruby-rc4 (0.1.5-2build1) ...
Paramétrage de ruby-afm (0.2.2-1) ...
Paramétrage de ruby-hashery (2.1.1-1) ...
Paramétrage de ruby-ttfunk (1.4.0-1) ...
Paramétrage de ruby-pdf-reader (1.3.3-1) ...
Paramétrage de ruby-pdf-core (0.4.0-1) ...
Paramétrage de ruby-prawn (1.3.0+dfsg-1) ...
Paramétrage de ruby-prawn-table (0.2.0-1) ...
Paramétrage de ruby-coderay (1.1.0-2) ...
Paramétrage de ruby-stringex (2.5.2-2) ...
Paramétrage de ruby-kramdown (1.4.2-2) ...
Paramétrage de ruby-mercenary (0.3.4-1) ...
Paramétrage de ruby-safe-yaml (1.0.3-1) ...
Paramétrage de ruby-colorator (0.1-3) ...
Paramétrage de ruby-blankslate (2.1.2.4-4build1) ...
Paramétrage de ruby-parslet (1.6.1-1) ...
Paramétrage de ruby-toml (0.1.1-1) ...
Paramétrage de ruby-jekyll-paginate (1.0.0-1) ...
Paramétrage de ruby-jekyll-gist (1.1.0-1) ...
Paramétrage de ruby-coffee-script-source (1.3.3-2) ...
Paramétrage de ruby-multi-json (1.10.1-1) ...
Paramétrage de ruby-execjs (2.2.1-1) ...
Paramétrage de ruby-coffee-script (2.2.0-2) ...
Paramétrage de ruby-jekyll-coffeescript (1.0.0-1) ...
Paramétrage de ruby-sass (3.4.6-2) ...
Paramétrage de ruby-jekyll-sass-converter (1.0.0-2) ...
Paramétrage de ruby-jekyll-watch (1.0.0-1) ...
Paramétrage de ruby-timers (1.1.0-2) ...
Paramétrage de ruby-celluloid (0.15.2-2) ...
Paramétrage de ruby-listen (2.4.0-4) ...
Paramétrage de ruby-rouge (1.5.1-1) ...
Paramétrage de libruby2.1:i386 (2.1.2-2ubuntu3) ...
Paramétrage de ruby-fast-stemmer (1.0.2-1build2) ...
Paramétrage de ruby-classifier (1.3.4-2) ...
Paramétrage de ruby-posix-spawn (0.3.9-1) ...
Paramétrage de ruby-yajl (1.2.0-2build1) ...
Paramétrage de ruby-pygments.rb (0.5.4~ds1-3) ...
Paramétrage de ruby-redcarpet (3.1.2-1build1) ...
Paramétrage de jekyll (2.2.0+dfsg-2) ...
Paramétrage de ruby-ffi (1.9.6debian-2) ...
Paramétrage de ruby-narray (0.6.0.9-1build1) ...
Paramétrage de ruby-gsl (1.15.3+dfsg-2build1) ...
Paramétrage de ruby-json (1.8.1-1build1) ...
Paramétrage de ruby-mysql (2.9.1-1build1) ...
Paramétrage de ruby-oj (2.10.3-2build1) ...
Paramétrage de ruby-pg (0.17.1-2) ...
Paramétrage de ruby-rb-inotify (0.9.5-1) ...
Paramétrage de ruby-sequel (4.15.0-1) ...
Paramétrage de ruby-sequel-pg (1.6.10-1) ...
Traitement des actions différées (« triggers ») pour libc-bin (2.21-0ubuntu4) ...
atc123@linux-Lor:/home/sites$ jekyll new MonBlog
New jekyll site installed in /home/sites/MonBlog. 
atc123@linux-Lor:/home/sites$ cd MonBlog
atc123@linux-Lor:/home/sites/MonBlog$ jekyll serve
Configuration file: /home/sites/MonBlog/_config.yml
            Source: /home/sites/MonBlog
       Destination: /home/sites/MonBlog/_site
      Generating... 
                    done.
Configuration file: /home/sites/MonBlog/_config.yml
    Server address: http://0.0.0.0:4000/
  Server running... press ctrl-c to stop.

^Catc123@linux-Lor:/home/sites/MonBlog$ sudo jekyll update
[sudo] password for atc123: 
Invalid command. Use --help for more information 
atc123@linux-Lor:/home/sites/MonBlog$ sudo gem update jekyll
Updating installed gems
Updating jekyll
jekyll -w
Fetching: liquid-3.0.6.gem (100%)
Successfully installed liquid-3.0.6
Fetching: rouge-1.10.1.gem (100%)
Successfully installed rouge-1.10.1
Fetching: rb-fsevent-0.9.6.gem (100%)
Successfully installed rb-fsevent-0.9.6
Fetching: listen-3.0.4.gem (100%)
Successfully installed listen-3.0.4
Fetching: jekyll-watch-1.3.0.gem (100%)
Successfully installed jekyll-watch-1.3.0
Fetching: jekyll-3.0.0.gem (100%)
Successfully installed jekyll-3.0.0
Parsing documentation for jekyll-3.0.0
Installing ri documentation for jekyll-3.0.0
Installing darkfish documentation for jekyll-3.0.0
Parsing documentation for jekyll-watch-1.3.0
Installing ri documentation for jekyll-watch-1.3.0
Installing darkfish documentation for jekyll-watch-1.3.0
Parsing documentation for liquid-3.0.6
Installing ri documentation for liquid-3.0.6
Installing darkfish documentation for liquid-3.0.6
Parsing documentation for listen-3.0.4
Installing ri documentation for listen-3.0.4
Installing darkfish documentation for listen-3.0.4
Parsing documentation for rb-fsevent-0.9.6
Installing ri documentation for rb-fsevent-0.9.6
Installing darkfish documentation for rb-fsevent-0.9.6
Parsing documentation for rouge-1.10.1
Installing ri documentation for rouge-1.10.1
Installing darkfish documentation for rouge-1.10.1
/usr/lib/ruby/2.1.0/rdoc/class_module.rb:173:in `aref_prefix': missing aref_prefix for RDoc::SingleClass (NotImplementedError)
	from /usr/lib/ruby/2.1.0/rdoc/class_module.rb:181:in `aref'
	from /usr/lib/ruby/2.1.0/rdoc/generator/template/darkfish/class.rhtml:47:in `block in generate_class'
	from /usr/lib/ruby/2.1.0/erb.rb:850:in `eval'
	from /usr/lib/ruby/2.1.0/erb.rb:850:in `result'
	from /usr/lib/ruby/2.1.0/rdoc/generator/darkfish.rb:724:in `template_result'
	from /usr/lib/ruby/2.1.0/rdoc/generator/darkfish.rb:703:in `block in render_template'
	from /usr/lib/ruby/2.1.0/rdoc/generator/darkfish.rb:698:in `open'
	from /usr/lib/ruby/2.1.0/rdoc/generator/darkfish.rb:698:in `open'
	from /usr/lib/ruby/2.1.0/rdoc/generator/darkfish.rb:698:in `render_template'
	from /usr/lib/ruby/2.1.0/rdoc/generator/darkfish.rb:351:in `generate_class'
	from /usr/lib/ruby/2.1.0/rdoc/generator/darkfish.rb:371:in `block in generate_class_files'
	from /usr/lib/ruby/2.1.0/rdoc/generator/darkfish.rb:368:in `each'
	from /usr/lib/ruby/2.1.0/rdoc/generator/darkfish.rb:368:in `generate_class_files'
	from /usr/lib/ruby/2.1.0/rdoc/generator/darkfish.rb:245:in `generate'
	from /usr/lib/ruby/2.1.0/rdoc/rubygems_hook.rb:137:in `block in document'
	from /usr/lib/ruby/2.1.0/rdoc/rubygems_hook.rb:134:in `chdir'
	from /usr/lib/ruby/2.1.0/rdoc/rubygems_hook.rb:134:in `document'
	from /usr/lib/ruby/2.1.0/rdoc/rubygems_hook.rb:196:in `generate'
	from /usr/lib/ruby/2.1.0/rdoc/rubygems_hook.rb:56:in `block in generation_hook'
	from /usr/lib/ruby/2.1.0/rdoc/rubygems_hook.rb:55:in `each'
	from /usr/lib/ruby/2.1.0/rdoc/rubygems_hook.rb:55:in `generation_hook'
	from /usr/lib/ruby/2.1.0/rubygems/dependency_installer.rb:400:in `call'
	from /usr/lib/ruby/2.1.0/rubygems/dependency_installer.rb:400:in `block (2 levels) in install'
	from /usr/lib/ruby/2.1.0/rubygems/dependency_installer.rb:399:in `each'
	from /usr/lib/ruby/2.1.0/rubygems/dependency_installer.rb:399:in `block in install'
	from /usr/lib/ruby/2.1.0/rubygems/dependency_installer.rb:353:in `in_background'
	from /usr/lib/ruby/2.1.0/rubygems/dependency_installer.rb:398:in `install'
	from /usr/lib/ruby/2.1.0/rubygems/commands/update_command.rb:206:in `update_gem'
	from /usr/lib/ruby/2.1.0/rubygems/commands/update_command.rb:220:in `block in update_gems'
	from /usr/lib/ruby/2.1.0/rubygems/commands/update_command.rb:219:in `each'
	from /usr/lib/ruby/2.1.0/rubygems/commands/update_command.rb:219:in `update_gems'
	from /usr/lib/ruby/2.1.0/rubygems/commands/update_command.rb:98:in `execute'
	from /usr/lib/ruby/2.1.0/rubygems/command.rb:305:in `invoke_with_build_args'
	from /usr/lib/ruby/2.1.0/rubygems/command_manager.rb:167:in `process_args'
	from /usr/lib/ruby/2.1.0/rubygems/command_manager.rb:137:in `run'
	from /usr/lib/ruby/2.1.0/rubygems/gem_runner.rb:54:in `run'
	from /usr/bin/gem:21:in `<main>'
atc123@linux-Lor:/home/sites/MonBlog$ jekyll -w
/usr/lib/ruby/vendor_ruby/mercenary/program.rb:30:in `go': invalid option: -w (OptionParser::InvalidOption)
	from /usr/lib/ruby/vendor_ruby/mercenary.rb:22:in `program'
	from /usr/bin/jekyll:18:in `<main>'
atc123@linux-Lor:/home/sites/MonBlog$ jekyll -v
jekyll 2.2.0
atc123@linux-Lor:/home/sites/MonBlog$ sudo apt-get update
Atteint http://fr.archive.ubuntu.com vivid InRelease
Réception de : 1 http://fr.archive.ubuntu.com vivid-updates InRelease [64,4 kB]
Atteint http://fr.archive.ubuntu.com vivid-backports InRelease                 
Atteint http://fr.archive.ubuntu.com vivid/main Sources                        
Atteint http://fr.archive.ubuntu.com vivid/restricted Sources                  
Atteint http://fr.archive.ubuntu.com vivid/universe Sources                    
Atteint http://fr.archive.ubuntu.com vivid/multiverse Sources                  
Réception de : 2 http://security.ubuntu.com vivid-security InRelease [64,4 kB] 
Atteint http://fr.archive.ubuntu.com vivid/main i386 Packages                  
Atteint http://fr.archive.ubuntu.com vivid/restricted i386 Packages            
Atteint http://fr.archive.ubuntu.com vivid/universe i386 Packages              
Atteint http://fr.archive.ubuntu.com vivid/multiverse i386 Packages            
Atteint http://fr.archive.ubuntu.com vivid/main Translation-fr                 
Atteint http://fr.archive.ubuntu.com vivid/main Translation-en                 
Atteint http://fr.archive.ubuntu.com vivid/multiverse Translation-fr           
Atteint http://fr.archive.ubuntu.com vivid/multiverse Translation-en           
Atteint http://fr.archive.ubuntu.com vivid/restricted Translation-fr           
Atteint http://fr.archive.ubuntu.com vivid/restricted Translation-en           
Atteint http://fr.archive.ubuntu.com vivid/universe Translation-fr             
Atteint http://fr.archive.ubuntu.com vivid/universe Translation-en             
Réception de : 3 http://fr.archive.ubuntu.com vivid-updates/main Sources [98,8 kB]
Réception de : 4 http://fr.archive.ubuntu.com vivid-updates/restricted Sources [3 687 B]
Réception de : 5 http://fr.archive.ubuntu.com vivid-updates/universe Sources [44,8 kB]
Réception de : 6 http://fr.archive.ubuntu.com vivid-updates/multiverse Sources [1 957 B]
Réception de : 7 http://fr.archive.ubuntu.com vivid-updates/main i386 Packages [221 kB]
Réception de : 8 http://security.ubuntu.com vivid-security/main Sources [47,4 kB]
Réception de : 9 http://fr.archive.ubuntu.com vivid-updates/restricted i386 Packages [12,8 kB]
Réception de : 10 http://fr.archive.ubuntu.com vivid-updates/universe i386 Packages [118 kB]
Réception de : 11 http://security.ubuntu.com vivid-security/restricted Sources [2 792 B]
Réception de : 12 http://fr.archive.ubuntu.com vivid-updates/multiverse i386 Packages [5 394 B]
Réception de : 13 http://fr.archive.ubuntu.com vivid-updates/main Translation-en [109 kB]
Réception de : 14 http://security.ubuntu.com vivid-security/universe Sources [18,0 kB]
Réception de : 15 http://fr.archive.ubuntu.com vivid-updates/multiverse Translation-en [2 246 B]
Réception de : 16 http://fr.archive.ubuntu.com vivid-updates/restricted Translation-en [2 969 B]
Réception de : 17 http://security.ubuntu.com vivid-security/multiverse Sources [1 957 B]
Réception de : 18 http://fr.archive.ubuntu.com vivid-updates/universe Translation-en [69,1 kB]
Atteint http://fr.archive.ubuntu.com vivid-backports/main Sources              
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted Sources        
Atteint http://fr.archive.ubuntu.com vivid-backports/universe Sources          
Réception de : 19 http://security.ubuntu.com vivid-security/main i386 Packages [125 kB]
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse Sources        
Atteint http://fr.archive.ubuntu.com vivid-backports/main i386 Packages        
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted i386 Packages  
Atteint http://fr.archive.ubuntu.com vivid-backports/universe i386 Packages    
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse i386 Packages  
Atteint http://fr.archive.ubuntu.com vivid-backports/main Translation-en       
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse Translation-en 
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted Translation-en 
Atteint http://fr.archive.ubuntu.com vivid-backports/universe Translation-en   
Réception de : 20 http://security.ubuntu.com vivid-security/restricted i386 Packages [10,2 kB]
Réception de : 21 http://security.ubuntu.com vivid-security/universe i386 Packages [58,1 kB]
Réception de : 22 http://security.ubuntu.com vivid-security/multiverse i386 Packages [5 394 B]
Atteint http://security.ubuntu.com vivid-security/main Translation-en          
Atteint http://security.ubuntu.com vivid-security/multiverse Translation-en
Atteint http://security.ubuntu.com vivid-security/restricted Translation-en
Atteint http://security.ubuntu.com vivid-security/universe Translation-en
1 088 ko réceptionnés en 7s (136 ko/s)                                         
Lecture des listes de paquets... Fait
atc123@linux-Lor:/home/sites/MonBlog$ sudo apt-get install ruby
Lecture des listes de paquets... Fait
Construction de l'arbre des dépendances       
Lecture des informations d'état... Fait
ruby est déjà la plus récente version disponible.
ruby passé en « installé manuellement ».
0 mis à jour, 0 nouvellement installés, 0 à enlever et 217 non mis à jour.
atc123@linux-Lor:/home/sites/MonBlog$ sudo apt-get update
Atteint http://security.ubuntu.com vivid-security InRelease
Atteint http://security.ubuntu.com vivid-security/main Sources                 
Atteint http://security.ubuntu.com vivid-security/restricted Sources           
Atteint http://security.ubuntu.com vivid-security/universe Sources             
Atteint http://security.ubuntu.com vivid-security/multiverse Sources           
Atteint http://security.ubuntu.com vivid-security/main i386 Packages           
Atteint http://security.ubuntu.com vivid-security/restricted i386 Packages     
Atteint http://fr.archive.ubuntu.com vivid InRelease                           
Atteint http://security.ubuntu.com vivid-security/universe i386 Packages       
Atteint http://security.ubuntu.com vivid-security/multiverse i386 Packages     
Atteint http://security.ubuntu.com vivid-security/main Translation-en          
Atteint http://security.ubuntu.com vivid-security/multiverse Translation-en    
Atteint http://security.ubuntu.com vivid-security/restricted Translation-en    
Atteint http://fr.archive.ubuntu.com vivid-updates InRelease                   
Atteint http://security.ubuntu.com vivid-security/universe Translation-en      
Atteint http://fr.archive.ubuntu.com vivid-backports InRelease                 
Atteint http://fr.archive.ubuntu.com vivid/main Sources        
Atteint http://fr.archive.ubuntu.com vivid/restricted Sources
Atteint http://fr.archive.ubuntu.com vivid/universe Sources
Atteint http://fr.archive.ubuntu.com vivid/multiverse Sources
Atteint http://fr.archive.ubuntu.com vivid/main i386 Packages
Atteint http://fr.archive.ubuntu.com vivid/restricted i386 Packages
Atteint http://fr.archive.ubuntu.com vivid/universe i386 Packages
Atteint http://fr.archive.ubuntu.com vivid/multiverse i386 Packages
Atteint http://fr.archive.ubuntu.com vivid/main Translation-fr
Atteint http://fr.archive.ubuntu.com vivid/main Translation-en
Atteint http://fr.archive.ubuntu.com vivid/multiverse Translation-fr
Atteint http://fr.archive.ubuntu.com vivid/multiverse Translation-en
Atteint http://fr.archive.ubuntu.com vivid/restricted Translation-fr
Atteint http://fr.archive.ubuntu.com vivid/restricted Translation-en
Atteint http://fr.archive.ubuntu.com vivid/universe Translation-fr
Atteint http://fr.archive.ubuntu.com vivid/universe Translation-en
Atteint http://fr.archive.ubuntu.com vivid-updates/main Sources
Atteint http://fr.archive.ubuntu.com vivid-updates/restricted Sources
Atteint http://fr.archive.ubuntu.com vivid-updates/universe Sources
Atteint http://fr.archive.ubuntu.com vivid-updates/multiverse Sources
Atteint http://fr.archive.ubuntu.com vivid-updates/main i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-updates/restricted i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-updates/universe i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-updates/multiverse i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-updates/main Translation-en
Atteint http://fr.archive.ubuntu.com vivid-updates/multiverse Translation-en
Atteint http://fr.archive.ubuntu.com vivid-updates/restricted Translation-en
Atteint http://fr.archive.ubuntu.com vivid-updates/universe Translation-en
Atteint http://fr.archive.ubuntu.com vivid-backports/main Sources
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted Sources
Atteint http://fr.archive.ubuntu.com vivid-backports/universe Sources
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse Sources
Atteint http://fr.archive.ubuntu.com vivid-backports/main i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-backports/universe i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-backports/main Translation-en
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse Translation-en
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted Translation-en
Atteint http://fr.archive.ubuntu.com vivid-backports/universe Translation-en
Lecture des listes de paquets... Fait                                          
atc123@linux-Lor:/home/sites/MonBlog$ sudo apt-get install rubygems
Lecture des listes de paquets... Fait
Construction de l'arbre des dépendances       
Lecture des informations d'état... Fait
Note : sélection de « ruby » au lieu de « rubygems »
ruby est déjà la plus récente version disponible.
0 mis à jour, 0 nouvellement installés, 0 à enlever et 217 non mis à jour.
atc123@linux-Lor:/home/sites/MonBlog$ sudo apt-get update
Atteint http://security.ubuntu.com vivid-security InRelease
Atteint http://security.ubuntu.com vivid-security/main Sources                 
Atteint http://security.ubuntu.com vivid-security/restricted Sources           
Atteint http://security.ubuntu.com vivid-security/universe Sources             
Atteint http://security.ubuntu.com vivid-security/multiverse Sources           
Atteint http://security.ubuntu.com vivid-security/main i386 Packages           
Atteint http://fr.archive.ubuntu.com vivid InRelease                           
Atteint http://security.ubuntu.com vivid-security/restricted i386 Packages     
Atteint http://security.ubuntu.com vivid-security/universe i386 Packages       
Atteint http://security.ubuntu.com vivid-security/multiverse i386 Packages     
Atteint http://security.ubuntu.com vivid-security/main Translation-en          
Atteint http://security.ubuntu.com vivid-security/multiverse Translation-en    
Atteint http://fr.archive.ubuntu.com vivid-updates InRelease                   
Atteint http://security.ubuntu.com vivid-security/restricted Translation-en    
Atteint http://security.ubuntu.com vivid-security/universe Translation-en      
Atteint http://fr.archive.ubuntu.com vivid-backports InRelease                 
Atteint http://fr.archive.ubuntu.com vivid/main Sources        
Atteint http://fr.archive.ubuntu.com vivid/restricted Sources
Atteint http://fr.archive.ubuntu.com vivid/universe Sources
Atteint http://fr.archive.ubuntu.com vivid/multiverse Sources
Atteint http://fr.archive.ubuntu.com vivid/main i386 Packages
Atteint http://fr.archive.ubuntu.com vivid/restricted i386 Packages
Atteint http://fr.archive.ubuntu.com vivid/universe i386 Packages
Atteint http://fr.archive.ubuntu.com vivid/multiverse i386 Packages
Atteint http://fr.archive.ubuntu.com vivid/main Translation-fr
Atteint http://fr.archive.ubuntu.com vivid/main Translation-en
Atteint http://fr.archive.ubuntu.com vivid/multiverse Translation-fr
Atteint http://fr.archive.ubuntu.com vivid/multiverse Translation-en
Atteint http://fr.archive.ubuntu.com vivid/restricted Translation-fr
Atteint http://fr.archive.ubuntu.com vivid/restricted Translation-en
Atteint http://fr.archive.ubuntu.com vivid/universe Translation-fr
Atteint http://fr.archive.ubuntu.com vivid/universe Translation-en
Atteint http://fr.archive.ubuntu.com vivid-updates/main Sources
Atteint http://fr.archive.ubuntu.com vivid-updates/restricted Sources
Atteint http://fr.archive.ubuntu.com vivid-updates/universe Sources
Atteint http://fr.archive.ubuntu.com vivid-updates/multiverse Sources
Atteint http://fr.archive.ubuntu.com vivid-updates/main i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-updates/restricted i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-updates/universe i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-updates/multiverse i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-updates/main Translation-en
Atteint http://fr.archive.ubuntu.com vivid-updates/multiverse Translation-en
Atteint http://fr.archive.ubuntu.com vivid-updates/restricted Translation-en
Atteint http://fr.archive.ubuntu.com vivid-updates/universe Translation-en
Atteint http://fr.archive.ubuntu.com vivid-backports/main Sources
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted Sources
Atteint http://fr.archive.ubuntu.com vivid-backports/universe Sources
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse Sources
Atteint http://fr.archive.ubuntu.com vivid-backports/main i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-backports/universe i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse i386 Packages
Atteint http://fr.archive.ubuntu.com vivid-backports/main Translation-en
Atteint http://fr.archive.ubuntu.com vivid-backports/multiverse Translation-en
Atteint http://fr.archive.ubuntu.com vivid-backports/restricted Translation-en
Atteint http://fr.archive.ubuntu.com vivid-backports/universe Translation-en
Lecture des listes de paquets... Fait                          
atc123@linux-Lor:/home/sites/MonBlog$ sudo apt-get install python
Lecture des listes de paquets... Fait
Construction de l'arbre des dépendances       
Lecture des informations d'état... Fait
python est déjà la plus récente version disponible.
0 mis à jour, 0 nouvellement installés, 0 à enlever et 217 non mis à jour.
atc123@linux-Lor:/home/sites/MonBlog$ jekyll -v
jekyll 2.2.0
atc123@linux-Lor:/home/sites/MonBlog$ sudo jekyll update
/var/lib/gems/2.1.0/gems/jekyll-3.0.0/bin/jekyll:13:in `<top (required)>': undefined method `require_from_bundler' for Jekyll::PluginManager:Class (NoMethodError)
	from /usr/local/bin/jekyll:23:in `load'
	from /usr/local/bin/jekyll:23:in `<main>'

