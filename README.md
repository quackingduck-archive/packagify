
    #####    ##    ####  #    #   ##    ####  ###### # ###### #   #
    #    #  #  #  #    # #   #   #  #  #    # #      # #       # #
    #    # #    # #      ####   #    # #      #####  # #####    #
    #####  ###### #      #  #   ###### #  ### #      # #        #
    #      #    # #    # #   #  #    # #    # #      # #        #
    #      #    #  ####  #    # #    #  ####  ###### # #        #


Convert a node module written as a single file to one that can be versioned and
distributed as a package.

  Install

    npm install -g packagify

  Create some module file

    touch my-module.js

  Make it a package

    packagify my-module.js

  Boom:

    my-module/
    ├── LICENSE
    ├── README.md
    ├── index.js
    ├── package.json
    └── test.js
