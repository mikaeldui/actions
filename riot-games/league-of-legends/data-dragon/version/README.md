# Data Dragon Version

Gets the latest version number for Data Dragon.

Example:

    - name: Data Dragon Version
      uses: mikaeldui/actions/riot-games/league-of-legends/data-dragon/version@main
      id: data-dragon
      
    - name: Print version
      run: echo "${{ steps.data-dragon.outputs.version }}
