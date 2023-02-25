<h1>
  Prompt:
</h1>

![alt text](prompt.png)

<h1>
  Writeup:
</h1>

> **$ sh Flag.pdf <br>
> $ binwalk -e flag <br>
> $ cd _flag.extracted <br>
> $ binwalk -e 64 <br>
> $ cd _64.extracted <br>
> $ lunzip flag <br>
> $ mv flag.out flag.lz4 <br>
> $ lz4 flag.lz4 <br>
> $ mv flag flag.lzma <br>
> $ lzma -d flag.lzma <br>
> $ binwalk -e flag <br>
> $ cd _flag.extracted <br>
> $ binwalk -e 0.lzo <br>
> $ cd _0.lzo.extracted <br>
> $ lzip 0 <br>
> $ binwalk -e 0.out <br>
> $ cd _0.out.extracted <br>
> $ binwalk -e 0.xz <br>
> $ cat 0** <br>
<p>7069636f4354467b66316c656e406d335f6d406e3170756c407431306e5f
6630725f3062326375723137795f33633739633562617d0a</p><br>
> **$ hex -d 0**
