# PHP Encryption/Decryption.

PHP Encryption/Decryption data using openssl_decrypt with AES-256-CBC Encryption Method.

  ╔═────────────────────────═══════════════────────────────────────═╗ 
  ║                                                                 ║  
  ║                                                                 ║
  ║                            ░ ░ ▓▓░▒                             ║  
  ║                      ▓███ ▒░▒ ▒░  ▓▒█▒                          ║  
  ║                     █████▓ ░  ░█░░ ░░░██   ░▒                   ║  
  ║                    ▒███▓▒░ ░ ▓  ▒     ░▓█▒▒▓▒█▒                 ║  
  ║                    ███▒░░▒  ▒▒     ░▒ ░██▒░ ▓▓█                 ║  
  ║                   ▒▒█▒ ▒▒ ░ ▓   ░░▒  ░ ▓█    ▒█                 ║  
  ║                 ██▓██▒ ░ ░░ ▒    ▒     ░█▒ ░░░█▓                ║  
  ║               █▒█▓███   ▒  ░▒    ░  ░   ▓ ░░░▓ ▒▒▒              ║  
  ║              ██▓▓██▓██▒░▒░▒▒░     ▒░ ░ ▒█   ▒  ▒▒█              ║  
  ║              ██▒▓█▒▓██░ ▒█▓██   ░███▒▒ ██▒░   ▒ ░█              ║  
  ║              ██████▓██▒ █░███    ██▒▒░██▒   ▒  ░░█              ║  
  ║               ████▒█▓██▒░██       ░█▒░█▒   ▒ ▒ ░█               ║  
  ║               ░███▒▓▓██░             ██ ░░   ▒ ██               ║  
  ║                █████▓█▒   ░██████     █  ▒▓ ░▒▒█                ║  
  ║                 █▒████   █████████    █ ░    ▓█▒                ║  
  ║                  ███ █      ███▓       █ ░  ▒█                  ║  
  ║                      ▒       █░        █   ▒█                   ║  
  ║                      ░       █       ░  ████▓                   ║  
  ║                       ▓░   ░░█▒░░  ▒▒     ███░                  ║  
  ║                       ░█    ▓ ░            ██                   ║  
  ║                      █                     ██▒                  ║  
  ║                                                                 ║
  ╚═────────────────────────═══════════════────────────────────────═╝  
 
## How to use

```sh
//For Encryption :
 $objMecrypt= new Mecrypt();
 $ecrypted_string= $objMecrypt->Encryption("test-string");



//For Decryption :
$decrypted_string=$objMecrypt->Decryption($ecrypted_string);


//Print the result


echo "Encrypted string :".$ecrypted_string;
echo "<br/>Decrypted string :".$decrypted_string;
```

