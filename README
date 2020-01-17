
                                         |\_______
                                    . __ |       /.
                            _______/| XX |        |
                           .\       | TT |        |
                           |        | !! |        |
                           |        | :: |        |
                           :        : .. |        |
                     ._____:   ________ _|__      :_____
                     |    /__ _\__    /    /_____ /   _/___
         tRUEsCHOOL  |     _/   _/   /    /|    //   _/   /.
         ----------  |_____||___\____\\_________\____\_____|
             _____       _____    _____. :     ___:_  _____ ______
            _\  _/_____ _\  _/____\    |______/ __  \/ __  \     |
          __\______   /.    \|   /.\   ._    /  //  /  //  /     |_
          \_     |/____|__________|____|/____\_____/\_____/|______/
           /_____|         .        . .. .        . h7/dS!
                           :        : ii :        :
                           |        | II |        |
                     _  _ _|_      _| UU |_       |
                           |/______\| XX |/_______|




                          TrueSchool Ascii Presents


                       Multi Platform Amiga Fonts v1.02




                               01. Description
                               02. Contents
                               03. Details
                               04. Windows TTF
                               05. Windows FON
                               06. Linux general
                               07. Linux console
                               08. Linux X-Windows
                               09. Mac OSX
                               10. Website embedding
                               11. Credits and thanks
                               12. Contact
                               13. History
                               14. Legal stuff
                               15. Contribution




      01. DESCRIPTION
      ===============


      Faithfully remade multi platform Amiga fonts in Amiga aspect.


      02. CONTENTS
      ============


      The contents of this archive are as follows:

            [dir] eot           - eot versions
            [dir] fon           - fon versions
            [dir] misc          - miscellaneous files
            [dir] psf1          - psf v1 versions
            [dir] psf2          - psf v2 versions
            [dir] raw           - raw (headerless) versions
            [dir] screens       - screenshots
            [dir] ttf           - ttf versions
                  file_id.diz   - File id
                  readme.txt    - This file


      03. DETAILS
      ===========


      Fonts included are:

            Family Name: Topaz a500a1000a2000
              File Name: Topaz_a500_v1.0.*
                Details: Original Topaz Kickstart 1.x version


            Family Name: TopazPlus a500a1000a2000
              File Name: TopazPlus_a500_v1.0.*
                Details: Modified Topaz Kickstart 1.x version


            Family Name: Topaz a600a1200a4000
              File Name: Topaz_a1200_v1.0.*
                Details: Original Topaz Kickstart 2.x version


            Family Name: TopazPlus a600a1200a4000
              File Name: TopazPlus_a1200_v1.0.*
                Details: Modified Topaz Kickstart 2.x+ version


            Family Name: P0T-NOoDLE
              File Name: P0T-NOoDLE_v1.0.*
                Details: Original P0T-NOoDLE font


            Family Name: MicroKnight
              File Name: MicroKnight_v1.0.*
                Details: Original MicroKnight font


            Family Name: MicroKnightPlus
              File Name: MicroKnightPlus_v1.0.*
                Details: Modified MicroKnight version


            Family Name: mOsOul
              File Name: mO'sOul_v1.0.*
                Details: Original mO'sOul font


      I would like to point out that these fonts are 100% complete. The
      Topaz_a1200, TopazPlus_a1200 and P0T-NOoDLE even include all the
      inverted characters that are present in the original Amiga
      equivalents.


      Special note about the bitmap versions of these three fonts
      -----------------------------------------------------------

      'space' (Unicode 0020) contains an inverted underscore on the
      Amiga keymap. It had to be moved to 'Non-breaking space'
      (Unicode 00A0). This has to be taken into consideration under
      some rare circumstances. Only the bitmap versions are affected
      by this.


      Special note about the scalable versions of these three fonts
      -------------------------------------------------------------

      I did not find a good way to match the inverted characters to the
      fonts codepages. If you want to know which characters do match,
      compare the bitmap versions with the scalable versions by using
      the included table.txt. All characters are sorted in the Unicode
      table as they appear in the Amiga character map.


      04. WINDOWS TTF
      ===============


      Install
      -------

      Turn ClearType off. Right click on the desktop and choose
      'Properties'. Go to 'Appearance -> Effects'. Make sure the
      'Use the following method to smooth edges of screen fonts'
      section is not selected. Click 'OK' twice.

      Go to 'control panel -> fonts -> file -> install new font'.
      Browse to the fonts and select the ones you want to install
      and click 'OK'.


      Configure
      ---------

      Default settings usually work just fine. If you must choose which
      encoding you want to use in your application, select either cp1252
      or ISO 8859-1.


      Putty and forks
      ---------------

      Go to 'Window -> Appearance' to select the font and font size you
      wish to use. Go to 'Window -> Translation' and choose
      'Win1252 (Western)' from the dropdown menu.

      Setting up the codepage in other terminal applications shouldn't
      be too hard. Just poke around in the settings.


      05. WINDOWS FON
      ===============


      Install
      -------

      These are bitmap versions of the fonts. Install and use them in
      the same way as the ttf's (see above).


      General notes
      -------------

      These are included as a pure fan service for the two persons in
      the world who actually might have any real use for them when
      there are identical ttf's available.

      I advise against using these with putty. It's not that they won't
      work, but some of the inverted characters (noteably the inverted
      @) influence on how the terminal emulation looks. Ncurses driven
      programs such as Midnight Commander and CenterIM will get inverted
      @'s instead of (blank) borders for instance.


      06. LINUX GENERAL
      =================


      UTF-8 encoding is a big no-no!
      ------------------------------

      Make sure that LC_ALL is set to ISO-8859-1 (or -15). This can be
      easily checked by typing:


            user@host:~$ locale


      If your distribution lacks the command, you can do this:


            user@host:~$ set|grep LC_ALL


      To set your LC_* values, do:


            user@host:~$ export LC_ALL="sv_SE.ISO-8859-1"


      The above example is for a swedish/finnish character map. Use
      de_DE.ISO-8859-1 for german, en_US.ISO-8859-1 for american english
      and so on. (read docs or google.)

      If you want to watch ascii using less, but it displays the wrong
      character encoding, use the following command:


            user@host:~$ export LESSCHARSET="latin1"


      The above settings will not be saved upon a reboot! If you want
      the them to be permanent (which you likely do ;)), make the
      appropriate changes to something like /etc/profile for global, or
      ~/.bashrc for current user setup.

      This can differ between distributions and the type of shell used,
      so if you're uncertain, i suggest you do some good old RTFM about
      your distribution.

      Basically most of these settings should(tm), at least in theory,
      also work on BSD systems. Some things can differ however, such as
      the names of the character sets. sv_SE.ISO-8859-1 in BSD would
      become something like sv_SE.ISO8859-1 and so on... Note that the
      use of these fonts in BSD has been untested so you're on your own.


      07. LINUX CONSOLE
      =================


      Included in this package are psf fonts for use in the Linux
      console. Two different versions are included, but you should be
      safe using the psf1 ones. The psf2 format was designed to be used
      for fonts wider than 8 pixels (and 512 characters) on framebuffer
      devices. All of these fonts are 8x16 pixels large, so there are no
      real uses for the psf2 ones, but i included them for the sake of
      completion.


      Install
      -------

      To try the fonts out you can in many cases do:


             user@host:~$ setfont <fontname.psf.gz>


      Again, this differs between distributions and the settings will
      not be permanent unless you explicitly make appropriate changes
      in system configuration files.

      Make sure you read the Linux general section further up in this
      document.


      08. LINUX X-WINDOWS
      ===================


      Install
      -------

      Read your distribution/xorg manuals on how to install ttf fonts
      on your system, and then install them.

      Configure
      ---------

      Whichever application you choose to use the fonts in, make sure
      you choose the correct encoding. Use codepage 1252 or ISO-8859-1.
      This goes for text editors as well as terminal applications.


      Linux Graphical Terminal (xterm, rxvt etc.)
      -------------------------------------------

      See Linux general section above.


      09. MAC OSX
      ===========


      Install
      -------

      Double click on the ttf you want to install. Choose
      'Install Font'. From the Font Book, drag and drop your newly
      installed fonts to 'Fixed Width' (and 'Favourites' ;)).


      Note for OSX 10.4.x (Tiger)
      ---------------------------

      The font validator will warn you that the fonts are missing
      opentype data, which is not true. This is a bug in 10.4.x (or so
      i've read), and you can safely install these fonts anyway. The bug
      has been fixed in 10.5.x (Leopard).


      Note for Extensis Suitcase
      --------------------------

      I have gotten a report that a Suitcase Fusion 2 v13.1.0 (49) setup
      failed to handle the fonts properly. I don't know if it was the
      particular setup/version or if Suitcase will always fail in
      handling them, so use it on your own risk.


      Configure
      ---------

      Make sure that the text editor or terminal application uses a
      character encoding set compatible with these fonts.

      Codepage 1252 or ISO 8859-1 should work. I've noticed that some
      applications have two different suffixes for ISO 8859-1, which are
      Latin1 or Windows. In these cases, the Windows one is the one you
      should use and probably it is just an alias for codepage 1252.


      Note for Textmate
      -----------------

      Some people might have problems with line height not being
      correct. If you encounter this problem, you could try changing the
      hidden/expert values OakLineHeightDelta and OakBaselineDelta. Read
      Textmate documentation for more information on how to change
      these. If these settings don't do it for you, start nagging the
      Textmate developers about it.


      Note for Terminal
      -----------------

      Go to 'Terminal -> Window Settings -> Display'. Change the font to
      the desired one, and change 'Character Set Encoding' to
      'Western (Windows Latin 1)'. Also make sure to read the Linux
      general section further up in the document to find out how to set
      up the encoding properly for the terminal and less. Read the OSX
      documentation or use google to find out how to make the changes
      permanent. And for you who didn't know: OSX runs on a BSD backend.


      10. WEBSITE EMBEDDING
      =====================


      Font embedding is easy. Just add something like this
      to a stylesheet; let's call it style.css:

            
            /* IE6/7/8 */
            @font-face {
                       font-family:P0T-NOoDLE;
                       src: url(P0T-NOoDLE_v1.0.eot);
            }

            /* FF3.5+/Safari/Opera10 */
            @font-face {
                       font-family:P0T-NOoDLE;
                       src: url(P0T-NOoDLE_v1.0.ttf) format("truetype");
            }

            PRE {
                 font-family:P0T-NOoDLE; font-size:12pt; font-weight:normal;
                 color:#000000; background-color:#9B9B9B;
                 line-height: 16px;
                 margin: 0; padding: 0;
            }


      Add the following line inside the <HEAD> tags in the html
      file you intend to use with font embedding:


            <link href="style.css" rel="stylesheet" type="text/css">



      Using the above example, put the ascii you want to display within
      <PRE> tags in your html file.

      To be able to use font embedding in Internet Explorer, use the
      included eot fonts.

      The font embedding support as described above currently works with
      Firefox v3.5+, Safari, Opera v10+, Google Chrome v3.0+ and Internet
      Explorer v6+, and it has been successfully tested in Windows, Linux
      and OSX.


      11. CREDITS AND THANKS
      ======================


            dMG of TrueSchool and Divine Stylers
            ------------------------------------
            - Font pixeling of fon's
            - Manual vectorizing, metrics calculation and many
              many hours of debugging ttf's
            - Conversion to eot and psf
            - Writing this documentation


      I want to thank the following people for contributing to this
      project in one way or the other:


            H7 of Divine Stylers
            --------------------
            TrueSchool logo


            Mogue of Arclite
            ----------------
            file_id


            bOhEmE of Style
            ---------------
            Hardcore OSX betatesting and promiscuous suggestions


            Spot of Up Rough Soundsystem
            ----------------------------
            Getting grey hair from betatesting the fonts embedded on
            the internal beta of the upcoming totally awesome Up Rough
            ascii portal


            Varj
            ----
            Proof reading the documentation


            aBHO of Twisted
            ---------------
            Proof reading the documentation


            D-Kynen
            -------
            Proof reading the documentation


      12. CONTACT
      ===========


      You can reach me the following ways:

            email: asciiscene{AT}gmail{DOT}com
              irc: #ascii on ircNET
            forum: http://www.asciiarena.com
              bbs: the yard
              www: http://www.trueschool.se


      I will not be your multiplatform font expert, computer support
      person or html guru, so emails or private messages with such
      requests will be treated as spam and thus will be ignored.

      Please do contact me for any other reason though! :)


      13. HISTORY
      ===========


      v1.0 - Now multi platform with bitmap- and scalable versions
      v0.7 - Initial Release. Bitmap versions of misc. Amiga fonts


      14. LEGAL STUFF
      ===============


      These fonts are released under the GPL-FE license:

      http://www.gnu.org/licenses/gpl-faq.html#FontException


      Topaz is © AmigaInc.
      ttf, fon, eot, raw & psf v1/v2 versions of Topaz are © dMG/t!s^dS!
      ttf, fon, eot, raw & psf v1/v2 versions of TopazPlus are © dMG/t!s^dS!

      P0T-NOoDLE is © Leo "Nudel" Davidson
      ttf, fon, eot, raw & psf v1/v2 versions are © dMG/t!s^dS!

      MicroKnight is © Niels Krogh "Nölb/Grafictive" Mortensen
      ttf, fon, eot, raw & psf v1/v2 versions of MicroKnight are © dMG/t!s^dS!
      ttf, fon, eot, raw & psf v1/v2 versions of MicroKnightPlus are
      © dMG/t!s^dS!

      mO'sOul is © Desoto/Mo'Soul
      ttf, fon, eot, raw & psf v1/v2 versions are © dMG/t!s^dS!


      15. CONTRIBUTION
      ================

      Contact me if you want to contribute somehow.

      This is it, my friend.

