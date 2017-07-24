# seqBuilder
A GUI based injection sequence builder for LC-MS runs.

The seqbuilder will allow you to pre-define the (square) layout of your autosampler in terms of how many sample holders there are and how many plate holders of each kind there are as well.

Then it allows you to graphically generate the information needed in terms of type (samples, calibrants, qcs,e tc), id's and concentration levels. Fill down or fill right options are avaialable with or without adding a numerical sequence for concentration levels as well as ids.

You can then also define starting sequence and between injection batch sequence and end of whole batch sequence of the QCs you want.

It then generates an injection list with options such as with or without randomization of the injection sequence of samples.

In the end you get a sequence list that can be directluy imported into Sciex Analyst.
