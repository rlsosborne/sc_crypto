AES
---



API
===

.. doxygenfunction:: AESEncrypt

.. doxygenfunction:: AESDecrypt



Example
=======


An example program is shown below::

  unsigned int plain[4] = {1,2,3,4};
  unsigned int key[4] = {12314241,4367465,1231244,1234569};
  unsigned int cipher[4];
  main() {
    AESEncrypt(input, key, cipher);
    AESDecrypt(cipher, key, output);
    return 0;
  }