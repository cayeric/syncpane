# syncpane
script that synchronizes markdown, PDF and jpg files from a document repository into a panefolder using hard links

    USAGE: syncpane PANEFOLDER [REPOSITORY]
      PANEFOLDER: the location that will serve as root folder for the Obsidian vault
      REPOSITORY: use this absolute path instead the path from the configured PANE_REPOSITORY_ROOT environment variable

INSTALL
=======
1. copy the syncpane file into the /usr/local/bin folder, set permission accordingly

        sudo cp syncpane /usr/local/bin && sudo chmod ugo+x /usr/local/bin/syncpane
2. add a PANE_REPOSITORY_ROOT variable with the absolut path to the documents root folder to the profile script

        # for zsh environment:
        $ echo 'EXPORT PANE_REPOSITORY_ROOT="/path/to/folder"' >> ~/.zshrc

#Obsidian
