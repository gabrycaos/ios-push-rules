
Guide for create openssl certificates can be used with php can be found at:

http://www.raywenderlich.com/32960/apple-push-notification-services-in-ios-6-tutorial-part-1

but when you make the command
		
		```
		$ openssl pkcs12 -nocerts -out PushChatKey.pem -in PushChatKey.p12

		```

you must add the flags 

		```
		-nodes -nocerts

		```
