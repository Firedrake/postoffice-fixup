= Fixup for Post Office label files =

Usage: fixup -o ordernumber (-d description -w weight -v value) pdf-file

Non-core modules: PDF::API2.

Royal Mail offers on-line postage for letters and parcels via
https://parcel.royalmail.com/ . I use this a few times a month and
wrote this software to make things slightly easier.

Download the label file (filename like Order-Label-nnnnn.pdf).

Run the fixup program, giving it an order number; this will add the
order number, and today's date, to the proof-of-postage part of the label.

If you also give a description, weight and value, the label will have
a CN22 customs form added to it, filled in as far as possible. (You'll
need CN22.pdf, which I got from that Royal Mail site complete with
spelling error.)

The output file will be named as Order-Label-nnnnn.processed.pdf.

Have fun!
