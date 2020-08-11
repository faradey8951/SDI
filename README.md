# SDI 
![ICON](https://i112.fastpic.ru/big/2020/0527/15/8ee92ed9e628774e94b9de0538401315.png)
-----------------------------
Soundcard Data Interface is source-closed project based on idea to transfer data using sound card
-----------------------------

-----------------------------
* Current Version: 0.2 Beta
- Download: https://github.com/faradey8951/SDI/blob/master/SDI.zip?raw=true
-----------------------------

-----------------------------
* Current version known issues:
    - Incorrect input audio devices indexing
-----------------------------
-----------------------------
* New features & changes:
  - Block data field square size changed
  - Group box controls size changed
  - Sync level and signal border settings have been removed
  - One level setting replaced into decoder settings group box on decoder menu page
  - Implemented more stable signal sync analyzer
  - Corrected available amplitude buffer sizes to fixed values
  - Now text data can be decoded on 16-bit amplitude buffer size only
  - Implemented correlation correction and signal smoothing algorithm (see "encoded signal basics and adjustments")
  - App may be hidden now without RAM leaking and freezing
  - Input and output audio devices list update automatically
  - MP3 player now uses WasapiOut instead of WaveOut feature to minimize delays and improve performance
  - Signal graph has been recoded that gives more stability and sets ram usage to minimal 
  - MP3 player now clears MemoryStream after playing that makes RAM usage to be safe
  - Error analyzer has been recoded fully and now being universal for any data block size
  - Implemented picture encoder that makes any picture less quality and being able to store on tape
  - Implemented special data block type - file marker (32-bit)
  - Improved much code branches, created classes instead of methods
  - Updated audio devices enumerators. Now audio input/output device may be selected correctly. App can't be run, if at least one output or input audio device doesn't exist

* Fixes:
  - Incorrect error analyzing system for 38-bit data blocks
  - App crashes, if decoding signal has much errors
  - App crashes sometimes, when try to play encoded file
  - App freezes when mp3 starts playing
  - MP3 clearing does not it immediately
  - MP3 encoding can't be cancelled manually
  - Programm freezes sometimes, when it hidden
  - Output audio device can't be changed
  - RAM leaking, when data being awaited after successful decoding
  - Play glitches, when mp3 decoding, if signal has much errors
  - Incorrect 16-bit Hamming Code branch
-----------------------------

-----------------------------
You may support the project with donation
- You will be put into the official project's partners list
- Current Official Project's Partners List:
  * Keith Aumann
- Donation https://www.paypal.me/SDIproject
-----------------------------

Also, you may help me with translation (see Lang directory)

-----------------------------
Current text encoding langs list:
- Русский
- English
-----------------------------

-----------------------------
Current app langs list:
- Русский
- English
-----------------------------

-----------------------------
For cassette tapes:
- Set rec level about -10dB or less
-----------------------------

-----------------------------
User Manual:
- https://github.com/faradey8951/SDI/blob/master/User%20Manual.pdf
-----------------------------

-----------------------------
Licence:
- You may share this project
- You are not allowed to sell this project
- You are not allowed to copy and steal the source code (some source code peaces may be published by me, if needed)
-----------------------------
