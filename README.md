# Sample repository for sending sms on failures
This sample will be sending an sms when a previous build step failed.

For this, we use a simple curl that sends the sms through the [t developers](developers.telekom.com) portal. It uses `curl` for sending the request and as a first step in the build, it'll fail the build.

