# Development Pills and Tricks
This repository contains only terminal pills and snippets helped me or frequently used

## npm @packages
    // discover new releases of the packages
    npm outdated
    
    // upgrading npm dependencies
    npm install -g npm-check-updates
    ncu  // list new major version
    ncu -u  // upgrade package.json (then run npm update or install)
    
    // list of globally installed packages
    npm list -g --depth 0
    ncu -g  // list new major version (globally)
    
    // check unused npm packages
    npm install -g depcheck
    depcheck --skip-missing
