This is project which has springboot and https using sll jks.
Inorder to create self signed certificate following command is used
keytool -genkey -alias https-example -storetype JKS -keyalg RSA -keysize 4096 -validity 365 -keystore keystore.jks

keytool -list -keystore keystore.jks
