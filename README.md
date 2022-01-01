# Analysis

File size is abnormal - 832314880 (bytes)

The file version - pretends to be Balbolkoa, a text-to-speech program

Reason for file version - to evade antivirus

The bulk of the file is in one section alone, named "DoItInPe", which is marked as RWX and is 98.71% of the total file size.
[insert DoItInPe.jpg]

Another section that stands out is the "ClearedP" section, which has an unusually high entropy score of 7.995.
[insert ClearedP.jpg]

800MB is a lot of assembly, most of which is irrelevant.
So the best course of action would be to run the sample, see which code was actually executed and go from there.
To do so, we use drcov by DynamoRIO, and the IDA Pro Lighthouse plugin

So ironically, while this file is over 800MB, it is actually packed.

