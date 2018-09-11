# PrivacyXML
PrivacyXML is a way of writing the privacy policy in XML.
Syntax:
```xml
<!DOCTYPE PXML SYSTEM "https://privacyXML.tk/PrivacyXML.dtd">
<PXML xmlns="https://privacyXML.tk/PrivacyXML.html">
	<age-restriction>
		<age><!--Minimum age--><age>
		<age><!--Maximum age--></age>
	</age-restriction>
	<data-mined>
		<data-type><!--Data mined via. Analytics, Metrics etc.--></data-type>
		<data-type><!--Other data mined--></data-type>
	</data-mined>
	<data-provided>
		<data-type><!--Data that the user provides such as E-mail address--></data-type>
	</data-provided>
	<data-recievers>
		<reciever><!--A reciever who recieves the data you collected--></reciever>
		<reciever><!--Another reciever who recieves the data you collected--></reciever>
	</data-recievers>
	<security><!--Insecure if the data can be intercepted by eavesdroppers, Mixed if so-so and Secure if it can't--></security>
</PXML>
```
Example PrivacyXML document:
```xml
<!DOCTYPE PXML SYSTEM "https://privacyXML.tk/PrivacyXML.dtd">
<PXML xmlns="https://privacyXML.tk/PrivacyXML.html">
	<age-restriction>
		<age>10<age>
	</age-resctriction>
	<data-mined>
		<data-type>Pages visited</data-type>
		<data-type>Number of visits</data-type>
		<data-type>Location</data-type>
	</data-mined>
	<data-provided>
		<data-type>Username</data-type>
		<data-type>Password</data-type>
		<data-type>E-mail address</data-type>
	</data-provided>
	<data-recievers>
	</data-recievers>
	<security>Secure</security>
</PXML>
```
