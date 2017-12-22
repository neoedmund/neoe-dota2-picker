# neoe-dota2-picker

A dota2 hero picker helper [Chinese 中文 README](https://github.com/neoedmund/neoe-dota2-picker/blob/master/README_cn.md)

## methodology 

use www.dotabuff.com hero's matchups data 

## how to run the application
* install JDK or JRE from java.com 
* download release package
* execute `runme.cmd` , support Linux and Windows

## how to use
* the first line is enemy 
* the 2nd line is ally
* the below lines are condidate.

* `click` on the cell, and type the hero name(English name, Chinese name, Chinese Pinyin name are supported) to find and select hero(use `up` `down` arrow key and `enter` key).
* `right click` on a cell can de-select hero.

## how to update data
* dotabuff.com's hero data will change over time. data will change a bit like a patch is released.
* To update, delete `compiled` and `versus` directory if exists. the program will download newest data from `dotabuff.com`.

## why release this tool
As a Christmas gift of 2017 for all dota2 lovers and open source lovers.

## screenshot
![UI](https://raw.githubusercontent.com/neoedmund/neoe-dota2-picker/master/jbhkmf1rc2.jpg)

