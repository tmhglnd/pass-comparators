# th.passcomparators
Max Abstractions that pass a value to output if true else block output

## About

This is a small package containing six useful abstractions build with vanilla max objects: [==p], [!=p], [<p], [<=p], [>p], [>=p]. The comparatorsPass are similar to the gen~ or jit. comparators. If the input value matches the condition it is passed to the outlet, if the condition is false the value is not output. An additional argument 1 will set the pass-false flag. When set the false condition will also be output as 0's (similar to gen~'s pass comparators). All abstraction have a corresponding helpfile with reference (*.maxhelp, *.maxref.xml).

## Install

```
1. download zip 
2. unzip in Max searchpath (eg. on MacOS ~/Documents/Max 8/Library)
3. restart Max8
```

```
1. open terminal
2. navigate to Max searchpath (eg. on MacOS cd ~/Documents/Max\ 8/Library)
3. $ git clone https://github.com/tmhglnd/th.passcomparators.git
```
