# longtest

run with:

set SELENIUM_BROWSER=firefox/r/n
set VELOCITY_DEBUG=1
set VELOCITY=1
set NODE_ENV=development
cmd /k meteor run --port 3000

or

SELENIUM_BROWSER=firefox VELOCITY_DEBUG=1 VELOCITY=1 NODE_ENV=development meteor run

cucumber.log:

[chimp][cucumber] Received message from cucumber child. Result: [

C:\Users\gatsu\AppData\Local\.meteor\packages\velocity_meteor-tool\1.1.4_2\mt-os.windows.x86_32\tools\fiber-helpers.js:160
    new Fiber(function () {
        ^
RangeError: Maximum call stack size exceeded
