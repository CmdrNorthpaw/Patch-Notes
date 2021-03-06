General:

   * Fixed non-Steam games sometimes appearing unavailable for Remote Play
   * Fixed steamwebhelper CPU/GPU usage in Steam overlay while the overlay is not visible


Library:

   * Fixed Activity section not appearing in game details when Family View is enabled
   * Fixed "Load More Activity" button not loading more activity
   * Fixed some display errors for soundtracks with track names containing unusual characters
   * Added support for playing back soundtracks containing .m4a content
   * When installing a game, Steam will now immediately sync your Steam Cloud files 
   * in the background instead of waiting potentially until the first launch of the game.
   * Minor layout and visual changes
   * Stop showing "library in use" message for non-Steam games when a shared library is being used


Big Picture:

   * Fix issue with the Big Picture Overlay in games w/ launchers
   * Fixed crash when viewing Community Connect in Library
   * Fix an issue where the on-screen keyboard would not work with mouse or touch input when a controller is attached 
   * Add a Capslock/Altlock mode to the on-screen keyboard which is enabled by 
    double tapping the shift/alt keys.
   * Remove the “Turn Off Controller” option from the power button menu for controllers which don’t support the feature
   * Add filter a for Steam Play white-listed games to the Big Picture Library’s filter list on Linux


SteamVR:

   * Hide games hidden by Family View from SteamVR (prevents them from showing up in SteamVR Home and  other VR quick launch game lists).
   *  Hide automatically created VR shortcuts when the original manifest has marked them hidden.
   * Mark hidden shortcuts to VR games as hidden in manifests created by Steam.
    Steam overlay will now show download status when starting an application that is updating or installing.
   * Eliminated spam related to the desktop overlay on Windows 10
   * Fixed issue with Quick Launch in SteamVR showing certain overlay applications


macOS:

   * Fixed intermittent Steam client and overlay crashes for certain system configurations
   * Fixed some keyboard control keys not being handled correctly by Big Picture browsers


Remote Play Together:

   * Added ability to invite players by dragging them from the friend's list into the 
    Remote Play Together window.


Steam Link:

   * When a Steam Link connects, the default view is recent games that 
    are optimized for the connecting device. 
     * This can be changed in the advanced streaming settings on the Steam Link app or hardware.

  

Linux:

   * Fix diagnostic tool helper processes blocking until they time out on Ubuntu 18.04


SteamNetworkingSockets:

   * Fix a bug with multiple P2P connections from the same peer