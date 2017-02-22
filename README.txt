You need Java 1.8 installed.
This is an IntelliJ IDEA project and it should be compatible with Eclipse (but not tested).

If you want to compile the project in console:

1. Make sure you are using Java 1.8:
$ javac -version
if you installed Java 1.8 before, but previous command gives you "1.7", switch to 1.8 (for Mac users):
$ export JAVA_HOME=`/usr/libexec/java_home -v 1.8`, if you have installed Java 1.8 before

2. Compile:
$ javac -cp "libs/*" src/com/anti_captcha/AnticaptchaBase.java src/com/anti_captcha/Main.java src/com/anti_captcha/IAnticaptchaTaskProtocol.java src/com/anti_captcha/Api/ImageToText.java src/com/anti_captcha/Api/NoCaptcha.java src/com/anti_captcha/Api/NoCaptchaProxyless.java src/com/anti_captcha/ApiResponse/BalanceResponse.java src/com/anti_captcha/ApiResponse/CreateTaskResponse.java src/com/anti_captcha/ApiResponse/TaskResultResponse.java src/com/anti_captcha/Helper/DebugHelper.java src/com/anti_captcha/Helper/HttpHelper.java src/com/anti_captcha/Helper/JsonHelper.java src/com/anti_captcha/Helper/StringHelper.java src/com/anti_captcha/Http/HttpRequest.java src/com/anti_captcha/Http/HttpResponse.java

3. Run:
$ java -cp "src:libs/*" com.anti_captcha.Main
