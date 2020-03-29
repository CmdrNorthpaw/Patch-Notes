General:

   * During game install allow the user to pick a different language if they’ve changed the per-game language setting or previously installed the game in a different language
   * Fixed a rare crash Steam could cause in some Steam VR helper processes when Steamworks is initialized in an unexpected manner
   * Fixed Steam client crash when errors are encountered in audio encoding or decoding when running a game using Steam Voice
   * Fixed achievement notification images for some games
   * Fixed the achievement section of library game pages not updating when a user gains an achievement
   * Fixed intermittent failures in broadcast, YouTube and other web video playback. If you are currently or have previously experienced this please ensure that the “Enable hardware video decoding” setting is enabled in the Interface tab of settings.
   * Updated embedded Chromium build in Steam to 79.0.3945.117


Library:

   * Decreased the number of network requests made when initially loading a game page
   * Added the ability to resize the game list by dragging the divider between the left and right panels
   * When viewing game details for a demo, added a section with a link to the main game.
   * Fix formatting of game reviews displayed in activity feed
   * Fixed long lists of trading cards not properly wrapping in game activity sections
   * Fixed What's New section not resizing properly when Automatic display size is selected
   * Fixed the play bar freaking out when scrolled to the top on very short windows when viewing game details for games with very little content in the right panel


Chat:

   * Improved the performance of large chat room groups.


Steam Cloud:

   * Fixed using multiple Steam accounts on one machine under the same local user – if the game files are written to a common (non-Steam) location, they were previously mixed between Steam accounts
   * Fixed inability to download files greater than 256MB


Steam Input:

   * Increased responsiveness of Switch Controllers when alt-tabbing
   * Added support for the Victrix Pro FS with Touch Pad.
   * Fixed some cases where Switch Controllers could lock up Steam on Windows.


Steam Networking Sockets:

   * Fixed a bug that could cause a P2P connection to drop if a relay went offline while in use


Remote Play:

   * Added a controller overlay with mouse mode, on-screen keyboard functionality and more! Default way to bring up is a long press of the Back button and can be configured in Remote Play settings.
   * Added the option to record/playback input from the controller overlay when on the Windows login screen
   * Added loading screen tips for useful functionality, including which button opens the overlay
   * Added additional detail when running install scripts during PC to PC streaming
   * Added Steam Overlay to the streaming client in Remote Play Together.
   * Reduced audio dropouts when streaming microphone input
   * Fixed sending controller input to the remote side in Remote Play Together
   * Fixed muted audio when streaming after an RDP session
   * Fixed controller overlay showing up automatically when connecting
   * Fixed doubled up controller input when doing PC to PC streaming
   * Fixed black screen when streaming from a locked computer
   * Fixed Play button saying "Stop" instead of "Connect" when the stream stops unexpectedly
   * Fixed crash in Remote Play Together when one or more player has a controller connected
   * Fixed characters being doubled when typing in foreign languages.
   * Fixed remote client discovery when using link-local ipv4 addresses (IP auto-configuration)
   * Fixed low audio volume when starting the stream
   * Fixed VR games getting auto filtered during a VR session when a Remote Play spectator is connected.
   * Fixed several stability issues during launching, task switching, overlay, and shutdown of various games.
   * Fixed custom cursor size on specific games such as Heroes of Might and Magic III HD Edition.
   * Fixed player names displaying in the wrong position for InGame and Snooze status.


Big Picture Mode:

   * Added plumbing to use the desktop client’s image cache for games. Game icons should now load quicker and start working in offline mode.
   * Added the ability to rumble controllers in the “Reorder Controllers Dialog”. Controllers which support LED color such as the DS4 will also have the controller’s LED color setting reflected in the controller image.
   * Fixed navigating community content panels for games w/ mature content
   * Fixed some cases where the Overlay would not come up when using a controller w/ gyro bound to mouse in Steam Input


SteamVR:

   * Fixed incorrectly adding non-Steam app screenshots to SteamVR.
   * Fixed some hybrid 2D/VR games not appearing in the VR UI.


Windows:

   * Fixed behavior of some Steam windows in certain multi-monitor + mixed high DPI/scaling scenarios


Linux:

   * Disabled CEF keyring integration by default. The -enable-keyring option can be passed to the Steam client to reinstate it.
   * Fix race condition that could cause some Proton-enabled games to redownload
   * Fixed Big Picture Mode on-screen keyboard not popping up when clicking on text fields with Touch Screen Mode enabled
   * Fixed Big Picture Mode on-screen Keyboard not allowing more than 3 clicks on a key in quick succession with mouse/touch input
   * Fixed a client crash occasionally happening while iterating directories
   * Fixes to Steam overlay for titles that use XInput2


Linux Steam runtime 0.20200318.1:

   * Updated to latest version of libvulkan
   * Added exports for more WSI functions for Proton
   * Improved runtime diagnostic tools