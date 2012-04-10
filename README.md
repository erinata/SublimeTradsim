# SublimeTradsim

This is a Sublime Text plugin which implement the functionality of the Ruby Gem "Tradsim" <https://github.com/erinata/tradsim>. It provides translation between Traditional Chinese and Simplified Chinese.

## Installation

Install using Package Control (Recommanded)

1. I guess most Sublime Text 2 users are using Sublime Package Control. If not, please install in from here <http://wbond.net/sublime_packages/package_control>
2. Go to Preference > Package Control, and Choose "Install Package"
3. Choose the package named "Tradsim" to install it

Install manually

1. Download the repo
2. Copy everything in the repo to a folder named "Tradsim" under the package folder of SublimeText 2 (create it if it doesn't exist)

## Usage

Press Ctrl+Shift+P to bring up the command input panel. Type in "Tradsim" and you will see there are 2 commands provided.

    Tradsim: Translate to Traditional Chinese
    Tradsim: Translate to Simplified Chinese

Choose the command that you want to run to perform the translation

## Limitation

I try to rewrite the RubyGem "Tradsim" in Python. However, I didn't implement the "guess" and "toggle" methods. I may do it later.

## License

Copyright (C) 2012 Tom Lam. MIT License.
