Table of Contents

  Obedient Cat
  Mod 26
  Python Wrangling
  Wave a Flag

Gym

  Obedient Cat

    https://play.picoctf.org/practice/challenge/147

      This file has a flag in plain sight (aka "in-the-clear"). Download flag.
        https://mercury.picoctf.net/static/fb851c1858cc762bd4eed569013d7f00/flag

      $ wget "https://mercury.picoctf.net/static/fb851c1858cc762bd4eed569013d7f00/flag"
      $ ls
      $ cat flag
        
        picoCTF{s4n1ty_v3r1f13d_28e8376d}

      $ man wget
      $ man cat

  Mod 26

    https://play.picoctf.org/practice/challenge/144

      Cryptography can be easy, do you know what ROT13 is? cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_jdJBFOXJ}

      https://rot13.com/
        cvpbPGS{arkg_gvzr_V'yy_gel_2_ebhaqf_bs_ebg13_GYpXOHqX}
          
          picoCTF{next_time_I'll_try_2_rounds_of_rot13_TLcKBUdK}

  Python Wrangling

    https://play.picoctf.org/practice/challenge/166

      Python scripts are invoked kind of like programs in the Terminal... Can you run this Python script using this password to get the flag?
        https://mercury.picoctf.net/static/5c4c0cbfbc149f3b0fc55c26f36ee707/ende.py
        https://mercury.picoctf.net/static/5c4c0cbfbc149f3b0fc55c26f36ee707/pw.txt
        https://mercury.picoctf.net/static/5c4c0cbfbc149f3b0fc55c26f36ee707/flag.txt.en
      
        $ wget "https://mercury.picoctf.net/static/5c4c0cbfbc149f3b0fc55c26f36ee707/ende.py"
        $ wget "https://mercury.picoctf.net/static/5c4c0cbfbc149f3b0fc55c26f36ee707/pw.txt"
        $ wget "https://mercury.picoctf.net/static/5c4c0cbfbc149f3b0fc55c26f36ee707/flag.txt.en"

        $ nano ende.py
        $ cat pw.txt
          192ee2db192ee2db192ee2db192ee2db
        
        $ python ende.py -d flag.txt.en
          Please enter the password:

          picoCTF{4p0110_1n_7h3_h0us3_192ee2db}

        $ man python
        $ man nano

Wave a flag

Description
Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information...

https://mercury.picoctf.net/static/a00f554b16385d9970dae424f66ee1ab/warm

This program will only work in the webshell or another Linux computer.

Run this program by entering the following in the Terminal prompt: $ ./warm, but you'll first have to make it executable with $ chmod +x warm

-h and --help are the most common arguments to give to programs to get more information from them!

Not every program implements help features like -h and --help.

$ wget "https://mercury.picoctf.net/static/a00f554b16385d9970dae424f66ee1ab/warm"
$ chmod +x warm
$ ./warm
Hello user! Pass me a -h to learn what I can do!
$ ./warm -h

picoCTF{b1scu1ts_4nd_gr4vy_18788aaa}

Notes

    $ man wget
    $ man cat
    $ man python
    $ man nano
    
Links

  https://rot13.com/
  