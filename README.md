# Electron-Configuration

This is my attempt to make a python program which outputs the full and condensed electron configurations of elements given their element name, symbol, or atomic number. 

Update as of 2019/10/15
 - General updates; bug fixes
 - Attempts to add transition metal exceptions added but commented out for now.
 - Problems below are still unresolved

Update as of 2019/10/10
 - Fixed the f-block electrons. The issues below are still yet to be resolved

Update as of 2019/10/08

The base program is currently executable, but there are a number of things to improve on:
  - Each individual electron is hard coded in a simple list (i.e. 1s^1, 1s^2). I think there is a way to simplify this using matrices.
  - Exceptions, such as the electron configuration of Chromium and Copper, and the electron configuration of ions in the d-block are still unaccounted for (don't want to have to hard code exceptions)
  - I still haven't added proper superscripts to the electron configurations
  - I have included several elements without agreed upon chemical properties (i.e. Oganesson) which I may take out at a later date.
  - I feel like I can use dictionaries for this but am unsure how to implement it.
  - break is used often and should be avoided in the future.

