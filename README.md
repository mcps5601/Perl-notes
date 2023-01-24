# Perl-notes
## Print
```perl
#!/usr/bin/perl
$hello = "Hello World";
print "$hello\n"; # 記得加上換行符號
```
你也可以
```perl
#!/usr/bin/perl
use 5.010;
$hello = "Hello World";
say "$hello"; # say幫你省去換行符號
```

## Concatenation
```perl
print "hello" . "world" # "helloworld"
print "Dean"x3 . "\n"; # DeanDeanDean
```

## Symbols for comparison
|Symbols|String|
|-|-|
|==|eq|
|!=|ne|
|<|lt|
|>|gt|
|<=|le|
|>=|ge|

## if-else
```perl
$line = <STDIN>;
if ($line eq "\n"){
    print "只是一個空列 !\n";
}
else {
    print "該列所輸入的是: $line";
}
```