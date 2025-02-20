
[![GitHub license](https://img.shields.io/github/license/microsoft/Web-Dev-For-Beginners.svg)](https://github.com/microsoft/Web-Dev-For-Beginners/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/Web-Dev-For-Beginners.svg)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/microsoft/Web-Dev-For-Beginners.svg)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/Web-Dev-For-Beginners.svg)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/Web-Dev-For-Beginners.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/Web-Dev-For-Beginners.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/Web-Dev-For-Beginners.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/stargazers/)


[![Open in Visual Studio Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://open.vscode.dev/microsoft/Web-Dev-For-Beginners)

# തുടക്കക്കാർക്കുള്ള വെബ് വികസനം - ഒരു പാഠ്യപദ്ധതി

മൈക്രോസോഫ്റ്റിലെ അസുർ ക്ലൗഡ് അഡ്വക്കേറ്റ്സ് ജാവാസ്ക്രിപ്റ്റ്, സിഎസ്എസ്, എച്ച്ടിഎംഎൽ അടിസ്ഥാനകാര്യങ്ങൾ എന്നിവയെക്കുറിച്ച് 12-ആഴ്ച, 24-പാഠ പാഠ്യപദ്ധതി വാഗ്ദാനം ചെയ്യുന്നതിൽ സന്തോഷമുണ്ട്. ഓരോ പാഠത്തിലും പാഠത്തിന് മുമ്പും ശേഷവുമുള്ള ക്വിസുകൾ, പാഠം പൂർത്തിയാക്കാനുള്ള രേഖാമൂലമുള്ള നിർദ്ദേശങ്ങൾ, ഒരു പരിഹാരം, ഒരു അസൈൻമെന്റ് എന്നിവയും അതിലേറെയും ഉൾപ്പെടുന്നു. ഞങ്ങളുടെ പ്രോജക്റ്റ് അധിഷ്‌ഠിത അദ്ധ്യാപനം പുതിയ കഴിവുകൾ സ്വായത്തമാക്കാൻ  നിങ്ങളെ അനുവദിക്കുന്നു.

**ഞങ്ങളുടെ രചയിതാക്കളായ ജെൻ ലൂപ്പർ, ക്രിസ് നോറിംഗ്, ക്രിസ്റ്റഫർ ഹാരിസൺ, ജാസ്മിൻ ഗ്രീൻവേ, യോഹാൻ ലസോർസ, ഫ്ലോർ ഡ്രീസ്, സ്കെച്ച്നോട്ട് ആർട്ടിസ്റ്റ് ടോമിമി ഇമുറ എന്നിവർക്ക് ഹൃദയം നിറഞ്ഞ നന്ദി!**

# ആമുഖം

> **അദ്ധ്യാപകർ**, ഞങ്ങൾ [ചില നിർദ്ദേശങ്ങൾ ഉൾപ്പെടുത്തിയിട്ടുണ്ട്](/for-teachers.md) ഈ പാഠ്യപദ്ധതി എങ്ങനെ ഉപയോഗിക്കാം എന്നതിനെക്കുറിച്ച്. നിങ്ങളുടെ ഫീഡ്‌ബാക്ക് ഞങ്ങൾ ഇഷ്ടപ്പെടുന്നു [ഞങ്ങളുടെ ചർച്ചാ ഫോറത്തിൽ](https://github.com/microsoft/Web-Dev-For-Beginners/discussions/categories/teacher-corner)!

> **വിദ്യാർത്ഥികൾ**, ഈ പാഠ്യപദ്ധതി സ്വന്തമായി ഉപയോഗിക്കുന്നതിന്, മുഴുവൻ റിപ്പോയും ഫോർക്ക് ചെയ്ത് സ്വന്തമായി വ്യായാമങ്ങൾ പൂർത്തിയാക്കുക, പ്രീ-ലെക്ചർ ക്വിസിൽ തുടങ്ങി, പ്രഭാഷണം വായിച്ച് ബാക്കി പ്രവർത്തനങ്ങൾ പൂർത്തിയാക്കുക. പരിഹാര കോഡ് പകർത്തുന്നതിനുപകരം പാഠങ്ങൾ മനസിലാക്കിക്കൊണ്ട് പ്രോജക്ടുകൾ സൃഷ്ടിക്കാൻ ശ്രമിക്കുക; എന്നിരുന്നാലും ആ പ്രോജക്റ്റ് അധിഷ്ടിതം  പാഠത്തിലെ /സൊല്യൂഷൻസ് ഫോൾഡറുകളിൽ ആ കോഡ് ലഭ്യമാണ്. മറ്റൊരു ആശയം സുഹൃത്തുക്കളുമായി ഒരു പഠന ഗ്രൂപ്പ് രൂപീകരിച്ച് ഒരുമിച്ച് ഉള്ളടക്കം പരിശോധിക്കുക എന്നതാണ്. കൂടുതൽ പഠനത്തിന്, ഞങ്ങൾ ശുപാർശ ചെയ്യുന്നു [മൈക്രോസോഫ്റ്റ് ലേൺ](https://docs.microsoft.com/users/jenlooper-2911/collections/jg2gax8pzd6o81/?WT.mc_id=academic-77807-sagibbon) കൂടാതെ താഴെ സൂചിപ്പിച്ചിരിക്കുന്ന വീഡിയോകൾ കണ്ടുകൊണ്ട്.

[![പ്രമോ വീഡിയോ](/images/web.gif)](https://youtube.com/watch?v=R1wrdtmBSII "പ്രമോ വീഡിയോ")

> 🎥 പ്രോജക്റ്റിനെക്കുറിച്ചും അത് സൃഷ്ടിച്ചവരെക്കുറിച്ചും ഒരു വീഡിയോയ്ക്കായി മുകളിലുള്ള ചിത്രത്തിൽ ക്ലിക്കുചെയ്യുക!

## അദ്ധ്യാപനo

ഈ പാഠ്യപദ്ധതി നിർമ്മിക്കുമ്പോൾ ഞങ്ങൾ രണ്ട് പെഡഗോഗിക്കൽ സിദ്ധാന്തങ്ങൾ തിരഞ്ഞെടുത്തു: ഇത് പ്രോജക്റ്റ് അടിസ്ഥാനമാക്കിയുള്ളതാണെന്നും അതിൽ പതിവ് ക്വിസുകൾ ഉൾപ്പെടുന്നുവെന്നും ഉറപ്പാക്കുന്നു. ഈ പരമ്പരയുടെ അവസാനത്തോടെ, വിദ്യാർത്ഥികൾ ഒരു ടൈപ്പിംഗ് ഗെയിം, ഒരു വെർച്വൽ ടെറേറിയം, ഒരു 'ഗ്രീൻ' ബ്രൗസർ എക്സ്റ്റൻഷൻ, ഒരു 'സ്പെയ്സ് ഇൻവേഡേഴ്സ്' ടൈപ്പ് ഗെയിം, ഒരു ബിസിനസ്-ടൈപ്പ് ബാങ്കിംഗ് ആപ്പ് എന്നിവ നിർമ്മിക്കുകയും ജാവാസ്ക്രിപ്റ്റിന്റെ അടിസ്ഥാനകാര്യങ്ങൾ പഠിക്കുകയും ചെയ്യും , ഇന്നത്തെ വെബ് ഡെവലപ്പറിന്റെ ആധുനിക ടൂൾചെയിനിനൊപ്പം HTML, CSS എന്നിവയും.

> 🎓 ഈ പാഠ്യപദ്ധതിയിലെ ആദ്യ കുറച്ച് പാഠങ്ങൾ നിങ്ങൾക്ക് മൈക്രോസോഫ്റ്റ് ലേൺ നെ കുറിച്ചുള്ള ഒരു[പഠന പാത](https://docs.microsoft.com/learn/paths/web-development-101/?WT.mc_id=academic-77807-sagibbon) ആയി എടുക്കാം.

പ്രോജക്റ്റുകളുമായി ഉള്ളടക്കം യോജിക്കുന്നുവെന്ന് ഉറപ്പുവരുത്തുന്നതിലൂടെ, ഈ പ്രക്രിയ വിദ്യാർത്ഥികളെ കൂടുതൽ ആകർഷകമാക്കുകയും ആശയങ്ങൾ നിലനിർത്തുന്നത് വർദ്ധിപ്പിക്കുകയും ചെയ്യും. ആശയങ്ങൾ അവതരിപ്പിക്കാൻ ഞങ്ങൾ ജാവാസ്ക്രിപ്റ്റ് അടിസ്ഥാനത്തിൽ നിരവധി സ്റ്റാർട്ടർ പാഠങ്ങൾ എഴുതി, paired with video from the "[ജാവാസ്ക്രിപ്റ്റിലേക്കുള്ള തുടക്കക്കാരുടെ പരമ്പര](https://channel9.msdn.com/Series/Beginners-Series-to-JavaScript/?WT.mc_id=academic-77807-sagibbon)" വീഡിയോ ട്യൂട്ടോറിയലുകളുടെ ശേഖരം, ചില എഴുത്തുകാർ ഈ പാഠ്യപദ്ധതിക്ക് സംഭാവന നൽകി.
ഇതുകൂടാതെ, ഒരു ക്ലാസിന് മുമ്പുള്ള ഒരു കുറഞ്ഞ ക്വിസ് ഒരു വിഷയം പഠിക്കുന്നതിനുള്ള വിദ്യാർത്ഥിയുടെ ഉദ്ദേശ്യം സജ്ജമാക്കുന്നു, അതേസമയം ക്ലാസിന് ശേഷമുള്ള രണ്ടാമത്തെ ക്വിസ് കൂടുതൽ നിലനിർത്തൽ ഉറപ്പാക്കുന്നു. ഈ പാഠ്യപദ്ധതി രൂപകൽപ്പന ചെയ്തിരിക്കുന്നത് വഴക്കമുള്ളതും രസകരവുമാണ്, ഇത് മുഴുവനായോ ഭാഗികമായോ എടുക്കാം. പദ്ധതികൾ ചെറുതായി ആരംഭിച്ച് 12 ആഴ്ച ചക്രത്തിന്റെ അവസാനത്തോടെ കൂടുതൽ സങ്കീർണമാകുന്നു.

ഒരു ചട്ടക്കൂട് സ്വീകരിക്കുന്നതിന് മുമ്പ് ഒരു വെബ് ഡെവലപ്പർ എന്ന നിലയിൽ ആവശ്യമായ അടിസ്ഥാന കഴിവുകളിൽ ശ്രദ്ധ കേന്ദ്രീകരിക്കുന്നതിന് ഞങ്ങൾ ജാവാസ്ക്രിപ്റ്റ് ചട്ടക്കൂടുകൾ അവതരിപ്പിക്കുന്നത് മനപ്പൂർവ്വം ഒഴിവാക്കിയിട്ടുണ്ടെങ്കിലും, ഈ പാഠ്യപദ്ധതി പൂർത്തിയാക്കുന്നതിനുള്ള ഒരു നല്ല അടുത്ത ഘട്ടം വീഡിയോകളുടെ മറ്റൊരു ശേഖരത്തിലൂടെ നോഡ്.js- നെക്കുറിച്ച് പഠിക്കുക എന്നതാണ്: "[നോഡ്.js ലേക്കുള്ള തുടക്കക്കാരുടെ പരമ്പര](https://channel9.msdn.com/Series/Beginners-Series-to-Nodejs/?WT.mc_id=academic-77807-sagibbon)".

> ഞങ്ങളുടെ [പെരുമാറ്റച്ചട്ടം](/CODE_OF_CONDUCT.md), [സംഭാവന](/CONTRIBUTING.md), [പരിഭാഷ](/TRANSLATIONS.md) എന്നിവയുടെ മാർഗ്ഗനിർദ്ദേശങ്ങൾ പരിശോധിക്കുക. നിങ്ങളുടെ ക്രിയാത്മക മായ അഭിപ്രായത്തെ ഞങ്ങൾ സ്വാഗതം ചെയ്യുന്നു!
>
## ഓരോ പാഠത്തിലും  ഉൾപ്പെടുന്നത്:

- ഓപ്ഷണൽ സ്കെച്ച്നോട്ട്
- ഓപ്ഷണൽ അനുബന്ധ വീഡിയോ
- പാഠത്തിനു മുമ്പുള്ള വാംഅപ്പ് ക്വിസ്
- എഴുതിയ പാഠഭാഗം
- പ്രോജക്റ്റ് അധിഷ്‌ഠിത പാഠങ്ങൾക്കായി, പ്രോജക്റ്റ് എങ്ങനെ നിർമ്മിക്കാം എന്നതിനെക്കുറിച്ചുള്ള ഘട്ടം ഘട്ടമായുള്ള ഗൈഡുകൾ
- വിജ്ഞാന പരിശോധനകൾ
- ഒരു വെല്ലുവിളി
- അനുബന്ധ വായന
- അസ്സൈൻമെന്റ്
- പാഠാനന്തര ക്വിസ്

> **ക്വിസുകളെക്കുറിച്ചുള്ള ഒരു കുറിപ്പ്**: എല്ലാ ക്വിസുകളും [ഈ ആപ്പിൽ](https://ashy-river-0debb7803.1.azurestaticapps.net/) അടങ്ങിയിരിക്കുന്നു, മൂന്ന് ചോദ്യങ്ങൾ വീതമടങ്ങിയ മൊത്തം 48 ക്വിസുകൾ. അവ പാഠങ്ങൾക്കുള്ളിൽ നിന്ന് ബന്ധിപ്പിച്ചിരിക്കുന്നു, പക്ഷേ ക്വിസ് ആപ്പ് പ്രാദേശികമായി പ്രവർത്തിപ്പിക്കാൻ കഴിയും; 'ക്വിസ്-ആപ്പ്' ഫോൾഡറിലെ നിർദ്ദേശം പാലിക്കുക. അവ ക്രമേണ പ്രാദേശികവൽക്കരിക്കപ്പെടുന്നു.

## പാഠങ്ങൾ


|       |                    പദ്ധതിയുടെ പേര്                       |                          പഠിപ്പിച്ച ആശയങ്ങൾ                          | പഠന ലക്ഷ്യങ്ങൾ                                                                                                                 |                                                         ലിങ്ക് ചെയ്ത പാഠം                                                         |        രചയിതാവ്          |
| :---: | :------------------------------------------------------: | :--------------------------------------------------------------------: | ----------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------: | :---------------------: |
|  01   |                   ആമുഖം                      |   പ്രോഗ്രാമിംഗിലേക്കും ട്രേഡിലെ ഉപകരണങ്ങളിലേക്കും ആമുഖം           | മിക്ക പ്രോഗ്രാമിംഗ് ഭാഷകൾക്കും പിന്നിലെ അടിസ്ഥാന അടിസ്ഥാനങ്ങളും പ്രൊഫഷണൽ ഡെവലപ്പർമാരെ അവരുടെ ജോലികൾ ചെയ്യാൻ സഹായിക്കുന്ന സോഫ്‌റ്റ്‌വെയറുകളെക്കുറിച്ചും അറിയുക | [പ്രോഗ്രാമിംഗ് ഭാഷകളിലേക്കും വ്യാപാരത്തിന്റെ ഉപകരണങ്ങളിലേക്കുമുള്ള  ഇൻട്രോ](/1-getting-started-lessons/1-intro-to-programming-languages/README.md) |         ജാസ്മിൻ         |
|  02   |              ആമുഖം                     |             ഗിറ്റ്ഹബിന്റെ അടിസ്ഥാനങ്ങളിൽ ഒരു ടീമിനൊപ്പം പ്രവർത്തിക്കുന്നത് ഉൾപ്പെടുന്നു             | നിങ്ങളുടെ പ്രോജക്റ്റിൽ ഗിറ്റ്ഹബ് എങ്ങനെ ഉപയോഗിക്കാം, ഒരു കോഡ് അടിസ്ഥാനത്തിൽ മറ്റുള്ളവരുമായി എങ്ങനെ സഹകരിക്കാം                                                    |                            [ഗിറ്റ്ഹബിലേക്കുള്ള ഇൻട്രോ](/1-getting-started-lessons/2-github-basics/README.md)                             |          ഫ്ലോർ           |
|  03   |                 ആമുഖം                      |                             ആക്സസിബിലിറ്റി                              | വെബ് ആക്സസബിലിറ്റിയുടെ അടിസ്ഥാനകാര്യങ്ങൾ പഠിക്കുക                                                                                               |                       [ആക്സസിബിലിറ്റി അടിസ്ഥാനങ്ങൾ](/1-getting-started-lessons/3-accessibility/README.md)                       |       ക്രിസ്റ്റഫർ       |
|  04   |                     JS അടിസ്ഥാനങ്ങൾ                         |                         ജാവാസ്ക്രിപ്റ്റ് ഡാറ്റ തരങ്ങൾ                          | ജാവാസ്ക്രിപ്റ്റ് ഡാറ്റ തരങ്ങളുടെ അടിസ്ഥാനങ്ങൾ                                                                                                |                                       [ഡാറ്റ തരങ്ങൾ](/2-js-basics/1-data-types/README.md)                                        |         ജാസ്മിൻ         |
|  05   |                      JS അടിസ്ഥാനങ്ങൾ                         |                         പ്രവർത്തനങ്ങളും രീതികളും                         | ഒരു ആപ്ലിക്കേഷന്റെ ലോജിക് ഫ്ലോ കൈകാര്യം ചെയ്യാനുള്ള പ്രവർത്തനങ്ങളെയും രീതികളെയും കുറിച്ച് അറിയുക                                                             |                              [പ്രവർത്തനങ്ങളും രീതികളും](/2-js-basics/2-functions-methods/README.md)                               | ജാസ്മിനും ക്രിസ്റ്റഫറും |
|  06   |                    JS അടിസ്ഥാനങ്ങൾ                         |                        ജെഎസുമായി തീരുമാനങ്ങൾ എടുക്കുന്നു                        | തീരുമാനമെടുക്കുന്ന രീതികൾ ഉപയോഗിച്ച് നിങ്ങളുടെ കോഡിൽ സാഹചര്യങ്ങൾ എങ്ങനെ സൃഷ്ടിക്കാമെന്ന് മനസിലാക്കുക                                                           |                                 [തീരുമാനങ്ങൾ എടുക്കുക ](/2-js-basics/3-making-decisions/README.md)                                  |         ജാസ്മിൻ         |
|  07   |                        JS അടിസ്ഥാനങ്ങൾ                         |                            അറേകളും ലൂപ്പുകളും                            | ജാവാസ്ക്രിപ്റ്റിലെ അറേകളും ലൂപ്പുകളും ഉപയോഗിച്ച് ഡാറ്റഉപയോഗിച്ച് പ്രവർത്തിക്കുക                                                                                 |                                   [അറേകളും ലൂപ്പുകളും](/2-js-basics/4-arrays-loops/README.md)                                    |         ജാസ്മിൻ         |
|  08   |       [ടെറേറിയം](/3-terrarium/solution/README.md)       |                            HTML ൽ പരിശീലിക്കുക                            | ഒരു ലേഔട്ട് നിർമ്മിക്കുന്നതിൽ ശ്രദ്ധ കേന്ദ്രീകരിച്ച് ഒരു ഓൺലൈൻ ടെറേറിയം സൃഷ്ടിക്കുന്നതിന് HTML നിർമ്മിക്കുക                                                         |                                 [HTML ന്റെ ആമുഖം](/3-terrarium/1-intro-to-html/README.md)                                 |           ജെൻ           |
|  09   |       [ടെറേറിയം](/3-terrarium/solution/README.md)       |                            CSS ൽ പരിശീലിക്കുക                             | പേജ് പ്രതികരണാത്മകമാക്കുന്നതുൾപ്പെടെ CSS-ന്റെ അടിസ്ഥാനകാര്യങ്ങളിൽ ശ്രദ്ധ കേന്ദ്രീകരിച്ചുകൊണ്ട് ഓൺലൈൻ ടെറേറിയം സ്റ്റൈൽ ചെയ്യുന്നതിന് സിഎസ്എസ് നിർമ്മിക്കുക                    |                                  [CSS ന്റെ ആമുഖം](/3-terrarium/2-intro-to-css/README.md)                                  |           ജെൻ            |
|  10   |            [ടെറേറിയം](/3-terrarium/solution/README.md)            |                ജാവാസ്ക്രിപ്റ്റ് ക്ലോസ്രെസ്, ഡോം കൃത്രിമം                 | ക്ലോസ്രെസ്ന്റെയും ഡോം കൃത്രിമം  ഉപയോഗിച്ചുകൊണ്ട് ടെറേറിയം ഒരു ഡ്രാഗ്/ഡ്രോപ്പ് ഇന്റർഫേസായി പ്രവർത്തനമുണ്ടാക്കാൻ ജാവാസ്ക്രിപ്റ്റ് നിർമ്മിക്കുക          |                  [ജാവാസ്ക്രിപ്റ്റ് ക്ലോസ്രെസ്, ഡോം കൃത്രിമം](/3-terrarium/3-intro-to-DOM-and-closures/README.md)                   |           ജെൻ           |
|  11   |          [ടൈപ്പിംഗ് ഗെയിം](/4-typing-game/solution/README.md)          |                          ടൈപ്പിംഗ് ഗെയിം നിർമ്മിക്കുക                           | നിങ്ങളുടെ ജാവാസ്ക്രിപ്റ്റ് ആപ്പിന്റെ ലോജിക് ഡ്രൈവ് ചെയ്യുന്നതിന് കീബോർഡ് ഇവന്റുകൾ എങ്ങനെ ഉപയോഗിക്കാമെന്ന് മനസിലാക്കുക                                                          |                                [ഇവന്റ്-ഡ്രൈവിംഗ് പ്രോഗ്രാമിംഗ്](/4-typing-game/typing-game/README.md)                                |       ക്രിസ്റ്റഫർ       |
|  12   | [ഗ്രീൻ ബ്രൗസർ എക്സ്റ്റെൻഷൻ](/5-browser-extension/solution/README.md) |                         ബ്രൗസറുകളുമായി പ്രവർത്തിക്കുന്നു                          | ബ്രൗസറുകൾ എങ്ങനെ പ്രവർത്തിക്കുന്നു, അവയുടെ ചരിത്രം, ബ്രൗസർ എക്സ്റ്റെൻഷന്റെ ആദ്യ ഘടകങ്ങൾ എങ്ങനെ സ്കഫോൾഡ് ആാമെന്ന് മനസിലാക്കുക                               |                               [ബ്രൗസറുകളെ കുറിച്ച്](/5-browser-extension/1-about-browsers/README.md)                                |           ജെൻ           |
|  13   | [ഗ്രീൻ ബ്രൗസർ എക്സ്റ്റെൻഷൻ](/5-browser-extension/solution/README.md) | ഒരു ഫോം നിർമ്മിക്കുക, ഒരു എപിഐ വിളിക്കുക, പ്രാദേശിക സംഭരണത്തിൽ വേരിയബിളുകൾ സംഭരിക്കുക | പ്രാദേശിക സംഭരണത്തിൽ സംഭരിച്ചിരിക്കുന്ന വേരിയബിളുകൾ ഉപയോഗിച്ച് ഒരു API വിളിക്കുന്നതിനായി നിങ്ങളുടെ ബ്രൗസർ എക്സ്റ്റെൻഷന്റെ ജാവാസ്ക്രിപ്റ്റ് ഘടകങ്ങൾ നിർമ്മിക്കുക                      |                [APIs, ഫോമുകളും ലോക്കൽ സ്റ്റോറേജും](/5-browser-extension/2-forms-browsers-local-storage/README.md)                 |           ജെൻ           |
|  14   | [ഗ്രീൻ ബ്രൗസർ എക്സ്റ്റെൻഷൻ](/5-browser-extension/solution/README.md) |          ബ്രൗസറിലെ പശ്ചാത്തല പ്രക്രിയകൾ, വെബ് പ്രകടനം          | എക്സ്റ്റെൻഷന്റെ ഐക്കൺ കൈകാര്യം ചെയ്യുന്നതിന് ബ്രൗസറിന്റെ പശ്ചാത്തല പ്രക്രിയകൾ ഉപയോഗിക്കുക; വെബ് പ്രകടനത്തെക്കുറിച്ചും നിർമ്മിക്കുന്നതിനുള്ള ചില ഒപ്റ്റിമൈസേഷനുകളെ കുറിച്ചും അറിയുക   |             [പശ്ചാത്തല ജോലികളും പ്രകടനവും](/5-browser-extension/3-background-tasks-and-performance/README.md)              |           ജെൻ           |
|  15   |           [സ്പേസ് ഗെയിം](/6-space-game/solution/README.md)           |             ജാവാസ്ക്രിപ്റ്റ് ഉപയോഗിച്ച് കൂടുതൽ അഡ്വാൻസ്ഡ് ഗെയിം ഡെവലപ്പ് മെന്റ്             | ഒരു ഗെയിം നിർമ്മിക്കുന്നതിനുള്ള തയ്യാറെടുപ്പിൽ ക്ലാസുകളും കോമ്പോസിഷൻ, പബ്/സബ് പാറ്റേൺ എന്നിവ ഉപയോഗിച്ച് അനന്തരാവകാശത്തെക്കുറിച്ച് അറിയുക           |                      [അഡ്വാൻസ്ഡ് ഗെയിം ഡെവലപ്പ്മെന്റിന്റെ ആമുഖം](/6-space-game/1-introduction/README.md)                       |          ക്രിസ്          |
|  16   |           [സ്പേസ് ഗെയിം](/6-space-game/solution/README.md)           |                           ക്യാൻവാസിലേക്ക് വരയ്ക്കുന്നു                            | ഒരു സ്ക്രീനിലേക്ക് ഘടകങ്ങൾ വരയ്ക്കാൻ ഉപയോഗിക്കുന്ന കാൻവാസ് API കുറിച്ച് അറിയുക                                                                       |                                [ക്യാൻവാസിലേക്ക് വരയ്ക്കുക ](/6-space-game/2-drawing-to-canvas/README.md)                                |          ക്രിസ്          |
|  17   |           [സ്പേസ് ഗെയിം](/6-space-game/solution/README.md)           |                   സ്ക്രീനിന് ചുറ്റും എലമെൻറ് ചലിപ്പിക്കുന്നു                    | കാർട്ടീഷ്യൻ നിർദ്ദേശാങ്കങ്ങളും കാൻവാസ്  API ഉപയോഗിച്ച് മൂലകങ്ങൾക്ക് എങ്ങനെ ചലനം നേടാൻ കഴിയുമെന്ന് കണ്ടെത്തുക                                            |                           [ചുറ്റും എലമെൻറ് ചലിപ്പിക്കുന്നു](/6-space-game/3-moving-elements-around/README.md)                           |          ക്രിസ്          |
|  18   |           [സ്പേസ് ഗെയിം](/6-space-game/solution/README.md)           |                          കോളിഷൻ  കണ്ടെത്തൽ                          | കീപ്രസ്സുകൾ ഉപയോഗിച്ച് ഘടകങ്ങൾ കൂട്ടിമുട്ടുകയും പരസ്പരം പ്രതികരിക്കുകയും ഗെയിമിന്റെ പ്രകടനം ഉറപ്പാക്കുന്നതിന് ഒരു കൂൾഡൗൺ ഫംഗ്ഷൻ നൽകുകയും ചെയ്യുക    |                              [കൂട്ടിയിടി കണ്ടെത്തൽ](/6-space-game/4-collision-detection/README.md)                              |          ക്രിസ്          |
|  19   |           [സ്പേസ് ഗെയിം](/6-space-game/solution/README.md)           |                             സ്കോർ നിലനിർത്തൽ                              | ഗെയിമിന്റെ നിലയെയും പ്രകടനത്തെയും അടിസ്ഥാനമാക്കി ഗണിത കണക്കുകൂട്ടലുകൾ നിർവഹിക്കുക                                                                |                                    [സ്കോർ നിലനിർത്തൽ](/6-space-game/5-keeping-score/README.md)                                    |          ക്രിസ്          |
|  20   |           [സ്പേസ് ഗെയിം](/6-space-game/solution/README.md)           |                     ഗെയിം അവസാനിപ്പിക്കുകയും പുനരാരംഭിക്കുകയും ചെയ്യുന്നു                     | ആസ്തികൾ വൃത്തിയാക്കുന്നതും വേരിയബിൾ മൂല്യങ്ങൾ പുനക്രമീകരിക്കുന്നതും ഉൾപ്പെടെ ഗെയിം അവസാനിപ്പിക്കുന്നതിനെകുറിച്ചും പുനരാരംഭിക്കുന്നതിനെ കുറിച്ചും അറിയുക                              |                                [അവസാനങ്ങളുടെ നിബന്ധനകൾ ](/6-space-game/6-end-condition/README.md)                                 |          ക്രിസ്          |
|  21   |         [ബാങ്കിംഗ് ആപ്പ്](/7-bank-project/solution/README.md)          |                 HTML ഒരു വെബ് ആപ്പിലെ ടെംപ്ലേറ്റുകളും റൂട്ടുകളും                 | റൂട്ടിംഗും എച്ച്ടിഎംഎൽ ടെംപ്ലേറ്റുകളും ഉപയോഗിച്ച് ഒരു മൾട്ടിപേജ് വെബ് സൈറ്റിന്റെ ആർക്കിടെക്ചറിന്റെ സ്കഫോൾഡ് എങ്ങനെ സൃഷ്ടിക്കാമെന്ന് മനസിലാക്കുക                            |                            [HTML ടെംപ്ലേറ്റുകളും റൂട്ടുകളും](/7-bank-project/1-template-route/README.md)                             |          യോഹാൻ          |
|  22   |         [ബാങ്കിംഗ് ആപ്പ്](/7-bank-project/solution/README.md)          |                  ലോഗിൻ, രജിസ്ട്രേഷൻ ഫോം നിർമ്മിക്കുക                   | ഫോമുകൾ നിർമ്മിക്കുന്നതിനെ കുറിച്ചും വാലിഡേഷൻ റുട്ടീൻ കൈമാറുന്നതിനെ കുറിച്ചും അറിയുക                                                                          |                                           [ഫോമുകൾ](/7-bank-project/2-forms/README.md)                                           |          യോഹാൻ          |
|  23   |         [ബാങ്കിംഗ് ആപ്പ്](/7-bank-project/solution/README.md)          |                  ഡാറ്റ കൊണ്ടുവരുന്നതും ഉപയോഗിക്കുന്നതുമായ രീതികൾ                   | ഡാറ്റ നിങ്ങളുടെ ആപ്പിലേക്ക് എങ്ങനെ ഒഴുകുന്നു, അത് എങ്ങനെ കൊണ്ടുവരാം, സംഭരിക്കാം, ഉപേക്ഷിക്കാം                                                 |                                            [ഡാറ്റ](/7-bank-project/3-data/README.md)                                            |          യോഹാൻ          |
|  24   |         [ബാങ്കിംഗ് ആപ്പ്](/7-bank-project/solution/README.md)          |                      സ്റ്റേറ്റ് മാനേജ്മെന്റിന്റെ ആശയങ്ങൾ                      | നിങ്ങളുടെ ആപ്പ് എങ്ങനെ സ്റ്റേറ്റ്നിലനിർത്തുന്നു, പ്രോഗ്രാമായി എങ്ങനെ കൈകാര്യം ചെയ്യണമെന്ന് അറിയുക                                                              |                                [സ്റ്റേറ്റ് മാനേജ്മെന്റ്](/7-bank-project/4-state-management/README.md)                                |          യോഹാൻ          |

## ഓഫ്‌ലൈൻ ആക്‌സസ്സ്

നിങ്ങൾക്ക് ഈ ഡോക്യുമെന്റേഷൻ [Docsify](https://docsify.js.org/#/) ഉപയോഗിച്ച്  ഓഫ്‌ലൈനിൽ പ്രവർത്തിപ്പിക്കാനാകും. ഈ റിപ്പോ ഫോർക്ക് ചെയ്യുക, [Docsify ഇന്സ്റ്റോള് ചെയ്യുക](https://docsify.js.org/#/quickstart) നിങ്ങളുടെ പ്രാദേശിക മെഷീനിൽ,തുടർന്ന് ഈ റിപ്പോയുടെ റൂട്ട് ഫോൾഡറിൽ `docsify serve` ടൈപ്പ് ചെയ്യുക.  നിങ്ങളുടെ ലോക്കൽഹോസ്റ്റിൽ പോർട്ട് 3000 ൽ വെബ്സൈറ്റ് കാണാം : `localhost:3000`.

## പിഡിഫ്

എല്ലാ പാഠങ്ങളുടെയും ഒരു PDF കാണാം [ഇവിടെ](https://microsoft.github.io/Web-Dev-For-Beginners/pdf/readme.pdf)

## മറ്റ് പാഠ്യപദ്ധതികൾ

ഞങ്ങളുടെ ടീം മറ്റ് പാഠ്യപദ്ധതികൾ നിർമ്മിക്കുന്നു! പരിശോധിക്കുക :

- [തുടക്കക്കാർക്കായുള്ള മെഷീൻ ലേണിംഗ്](https://aka.ms/ml-beginners)
- [തുടക്കക്കാർക്കായുള്ള IoT](https://aka.ms/iot-beginners)
