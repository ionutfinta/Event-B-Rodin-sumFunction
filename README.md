# Event-B Rodin `sum` function

This function allows you to sum sets of integers in Rodin. \
It is based on verified recursive sum algorithm I can't get it proven.

This can also be used as an inspiration to do some more advanced things with Event-B Rodin.

## Usage

Simply imports the files from /sumFunction into your project and add `sum_ctx` to the clause `SEES` of the machine in which you need it.

You can then use the function as any other function: `sum(S)`

## Rodin's style reference
sum -- sum  -- Sum of elements of set \

| | |
| -:| :- |
| __Description__ | sum(S) is an expression that gives the sum of each element in  the given set. it is only defined for finite sets.|
|__Definition__ | sum(S) = s_1 + s_2 + ... + s_n where s_n are integers elements of S.
|__Types__ | sum(S) is an integer (:INT -or Z-) with S being a POW(Z) (powerset of integers)
|__WD__ | ?

## Compatibility

Made with Rodin Platform Version: 3.4.0-6980ca1 on Windows 10 amd64.

## Contribution

Any contribution is welcome !
