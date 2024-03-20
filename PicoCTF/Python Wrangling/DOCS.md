Table of Contents

  Obedient Cat
  Mod 26
  Python Wrangling

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

Notes

    $ man wget
    $ man cat
    $ man python
    $ man nano
    
Links

  https://rot13.com/
  