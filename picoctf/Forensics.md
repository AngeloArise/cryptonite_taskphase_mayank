# Forensics

## Glory of the Garden (easy)
Challenge had a image of a garden linked, usually i would open it in a notepad and use 'ctrl+f', but using the ```strings``` function has been proven to be a lot easier and faster.

### Flag
Challenge required the user to find the flag inside a .jpg file.
```
picoCTF{more_than_m33ts_the_3y3eBdBd2cc}
```
<br>
<br>

## Information  (easy)
Similar, Challenge had an image linked, I tried stringing, no luck. Then fed the image to a metadata extractor, found two strings suspicious looking, the 'current_iptc_digest' and the 'license'. The license was a 64 bit encoded string

### Flag
Challenge required the user to find a flag from an image linked.
```
picoCTF{the_m3tadata_1s_modified}
```
<br>
<br>
