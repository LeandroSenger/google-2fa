# Package - for 2-factor authentication


A One Time Password Authentication package, compatible with Google Authenticator.

# Ex:

## use Senger\Google2fa\GoogleAuthenticator;

 $ga = new GoogleAuthenticator();

 $secret  = $ga->createSecret();
 
 $ga->verifyCode($secret, $gacode, 1);


Google 2fa.

