# Certifikatore - Not finished yet

Blunt PowerShell script that uses keytool and openssl to create a Payara Java App Keystore and modifies a truststore so clients can https or tcp ssl to it.

I did this one some months ago, but hardware catastrophe deleted it forever. The hard part was the regEx to bring up the SAN´s 

What is needed:
-PowerShell
-Issued certificate(s) and their passwords
-Starting truststore

What is output:
-A keystore per certificate provided
-A modified truststore that contains all trusted certificates
-A .cer per certificate provided so it can be used for windows clients "certificate manager"


