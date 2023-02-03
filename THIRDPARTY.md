# Third-party dependencies copyright notes

The Notepad Next is licensed under the GPL v3 License (see [LICENSE](LICENSE)).
See below for exceptions.

## Source Code Dependencies
- [[MIT](src/scintilla/License.txt)]  [scintilla and lexilla](https://www.scintilla.org/)
    - [`src/lexilla/*`](src/lexilla/)
    - [`src/scintilla/*`](src/scintilla/)
- [[MPL-1.1 OR GPL-2.0+ OR LGPL-2.1+](src/uchardet/COPYING)]  [uchardet](https://gitlab.freedesktop.org/uchardet/uchardet)
    - [`src/uchardet/*`](src/uchardet/)

**lua**
- [[MIT](https://www.lua.org/license.html)]  [lua](https://www.lua.org/)
    - [`src/lua/*`](src/lua/)
- [[MIT](https://github.com/vinniefalco/LuaBridge#official-repository)]  [LuaBridge](https://github.com/vinniefalco/LuaBridge)
    - [`src/LuaBridge/*`](src/LuaBridge/)

**Qt**
- [[LGPL-2.1](src/ads/LICENSE)]  [Advanced Docking System for Qt](https://github.com/githubuser0xFFFF/Qt-Advanced-Docking-System)
    - [`src/ads/*`](src/ads/)
- [[MIT](src/editorconfig-core-qt/LICENSE)]  [EditorConfig core for Qt](https://github.com/editorconfig/editorconfig-core-qt)
    - [`src/editorconfig-core-qt/*`](src/editorconfig-core-qt/)
- [[MIT](src/QSimpleUpdater/LICENSE.md)]  [Updater system for Qt](https://github.com/alex-spataru/QSimpleUpdater)
    - [`src/QSimpleUpdater/*`](src/QSimpleUpdater/)
- [[MIT](src/singleapplication/LICENSE)]  [SingleApplication](https://github.com/itay-grudev/SingleApplication)
    - [`src/singleapplication/*`](src/singleapplication/)


## Build-time dependencies
**Nsis Plugins**
- [[MIT](https://github.com/Drizin/NsisMultiUser/blob/master/License.txt)]  [Multi User Plugin](https://github.com/Drizin/NsisMultiUser/)
    - [`NsisMultiUser.nsh`](installer/NsisMultiUser/Include/NsisMultiUser.nsh)
    - [`NsisMultiUserLang.nsh`](installer/NsisMultiUser/Include/NsisMultiUserLang.nsh)
- [[LGPL-2.1+ with Clarification](https://github.com/lordmulder/stdutils/blob/master/LGPL_CLARIFICATION.txt)]  [StdUtils plug-in](https://github.com/lordmulder/stdutils/)
    - [`StdUtils.nsh`](installer/NsisMultiUser/Include/StdUtils.nsh)
    - [`StdUtils.dll`](installer/NsisMultiUser/Plugins/x86-unicode/StdUtils.dll)
- [[zlib](https://nsis.sourceforge.io/UAC_plug-in#Plugin_Info)]  [UAC plug-in](https://nsis.sourceforge.io/UAC_plug-in)
    - [`UAC.nsh`](installer/NsisMultiUser/Include/UAC.nsh)
    - [`UAC.dll`](installer/NsisMultiUser/Plugins/x86-unicode/UAC.dll)


## Runtime Dependencies
- [[Apache-2.0](https://www.openssl.org/source/license.html)]  [OpenSSL](https://www.openssl.org/)
    - [`libcrypto-1_1-x64.dll`](deploy/windows/libcrypto-1_1-x64.dll)
    - [`libssl-1_1-x64.dll`](deploy/windows/libssl-1_1-x64.dll)
