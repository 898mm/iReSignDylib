iReSignDylib
=======

iReSignDylib can inject dynamic library and also allows iDevice app bundles (.ipa) files to be signed or resigned with a digital certificate from Apple for distribution. It can also create signed iDevice app bundles (.ipa) files from .xcarchive files.  This tool is aimed at enterprises users, for enterprise deployment, when the person signing the app is different than the person(s) developing it.

How to use
=======

iReSignDylib allows you to inject dynamic library and re-sign any unencrypted ipa-file with any certificate for which you hold the corresponding private key, also created a signed ipa-file from an xcarchive file.

1. Drag your dynamic library file to the top box, or use the browse button.

2. Drag your unsigned .ipa or .xcarchive file to the second box, or use the browse button.

3. Enter your full certificate name from Keychain Access, for example "iPhone Developer: Firstname Lastname (XXXXXXXXXX)" in the bottom box.

4. Click ReSign! and wait. The resigned file will be saved in the same folder as the original file.

Preview
=======
![ScreenShot](https://raw.githubusercontent.com/898mm/iReSignDylib/master/ScreenShot.png)


Thanks to
=======
This software is modified based on iReSign (https://github.com/maciekish/iReSign), adding dynamic library injection function, thanks to original author Maciej Swic.


License
=======

Copyright (c) 2020 898mm

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
