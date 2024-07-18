RAM512:
![image](https://github.com/user-attachments/assets/3f04e9ea-c2cd-4f95-84cc-0e245b599cca)
 CHIP RAM512 {

    IN  in[16], load, address[9];
    OUT out[16];

    BUILTIN RAM512;
    CLOCKED in, load;
}

RAM4K:
![image](https://github.com/user-attachments/assets/f1a82589-3d42-4323-9f5c-b0211edaf782)
 CHIP RAM4K {

    IN  in[16], load, address[12];
    OUT out[16];

    BUILTIN RAM4K;
    CLOCKED in, load;
}

RAM16K:
![image](https://github.com/user-attachments/assets/68a2f890-06c8-45ee-98fb-a81c18038272)
 CHIP RAM16K {

    IN  in[16], load, address[14];
    OUT out[16];

    BUILTIN RAM16K;
    CLOCKED in, load;
}

PC:
![image](https://github.com/user-attachments/assets/a163deca-64e4-48e6-b3c5-dfcc55a90950)
CHIP PC {

    IN  in[16], load, inc, reset;
    OUT out[16];

    BUILTIN PC;
    CLOCKED in, load, inc, reset;
}


