# Loot Raider Android

v1.0 (c) 2021 Infusions of Grandeur - Written By: Eric Crichlow

## Background

Loot Raider is the "spiritual successor" to a game named "Gold Runner", which was released for the TRS-80 Color Computer back in the mid 80s. That is also the game I released and open-sourced an iOS version of a number of years ago.

As Gold Runner was a clone of another game sold for more popular computers, there were copyright issues that drew the attention and ire of the original game's copyright holder.

In order to make a game that was true to the spirit of the original, but was different enough in its gameplay that it wasn't subject to legal entanglements, I changed the fundamental play mechanics and added new features that make this its own unique game.

The game was originally written for iOS back in 2018, and the Swift code for that platform was ported to Android Kotlin in 2021. Because the app was a port, there are some parts of the code, specifically constants in the file ConfigurationManager.kt, that came over from the iOS version but are not used in the Android version.

## History

Version 1.0 :	Initial public release

## Assets

The sprites used by the game, as well as the gameboard files for the first 6 levels, are contained in the project. These assets were created using a customer editor that I wrote on the Mac.

## Usage

Details about the file formats of the sprites and gameboards can be found in the file "WhatWasIThinking". This file also contains information about some of the thought processes that went into the architecture and development of the game.

The file with the values used for Firebase Analytics, google-services.json, has been removed. So the project will not build without replacing that file. 

## Support

Questions or suggestions can be submitted to support@infusionsofgrandeur.com

## License

Copyright 2021 Infusions of Grandeur

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
