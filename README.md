# rsaCipher_python_javascript
Simple RSA cipher, with python flask server, and javascript forge client


The first time we run `python servicio_flask.py` files public_key.pem and private_key.pem will be created, those are the files for cript and decript stuff, with GET http://localhost:5000/ we will obtain the public_key.pem to cript things, with POST http://localhost:5000/ { message: "ciphered_text" } we will get the text decripted.

The file rsa_cipher.html is an interface to to that stuff, with that you will be able to write text (in textarea) cipher the text, get the public_key and get the decripted text from the server, clicking a button.

Inspired by: https://medium.com/@DannyAziz97/rsa-encryption-with-js-python-7e031cbb66bb
