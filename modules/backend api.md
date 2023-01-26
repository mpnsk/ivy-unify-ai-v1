These work as interface to other frameworks. They are the same in name and structure but differentiate themself with framework specific datastructures as argument.
Some functions don't exist in all frameworks or are very different in each framework. In each case ivy makes a judgement call.

The example is the logspace method being absent in tensorflow, ivy reimplements it by composition of other functions. 